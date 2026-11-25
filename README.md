# Dashboard Orçamentos (versão estática)

Página única (`index.html`) com os dados congelados em 25/11/2026 (planilha de 25/11): planilhas (custos, etapas, datas das fases, INCC-M, capacidade) e tarefas do ClickUp.
Não precisa de servidor nem de internet: os gráficos (d3) estão dentro do arquivo.

## Publicar no GitHub Pages

1. No GitHub, crie um repositório (ex.: `dashboard-orcamentos`).
   - **Atenção:** em conta gratuita, o GitHub Pages é público mesmo com repositório privado. Os custos das obras ficariam visíveis para quem tiver o link.
2. Envie o arquivo `index.html` (e este README): botão **Add file → Upload files** → arraste → **Commit changes**.
3. Vá em **Settings → Pages**.
4. Em **Build and deployment → Source**, escolha **Deploy from a branch**; em **Branch**, escolha `main` e a pasta `/ (root)` → **Save**.
5. Em 1 a 2 minutos o endereço aparece no topo da mesma página: `https://SEU-USUARIO.github.io/dashboard-orcamentos/`.

## Atualizar os dados

Peça ao Claude para gerar um novo `index.html` com os dados do dia e substitua o arquivo no repositório (Upload files → Commit). O site atualiza sozinho.

## Escolhas da aba Planejamento

- Ficam salvas só no navegador de quem mexeu.
- **Baixar minhas escolhas** gera um arquivo `.json`; outra pessoa pode usar **Carregar escolhas** para ver o mesmo cenário.
- **Voltar às escolhas originais** descarta o que foi mexido e volta às escolhas de 25/11/2026.
