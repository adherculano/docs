# Exemplo mínimo — GitHub Pages + MkDocs Material

## Como publicar (sem escrita pública)
1) Crie um repositório no GitHub.  
2) **Envie** estes arquivos (pelo navegador: *Add file → Upload files*, com o conteúdo descompactado).  
3) Em **Settings → Pages**, selecione **GitHub Actions**.  
4) Faça um commit na `main` (qualquer edição em `docs/*`). A Action gera e publica o site.

## Editar no navegador
- Abra `docs/` → clique no `.md` → ícone do lápis → salve (commit).  
- Para nova página, crie `docs/<secao>/<pagina>.md` e adicione no `nav` do `mkdocs.yml`.

## Abrir no Obsidian
- Abra a pasta `docs/` como um vault e edite normalmente.

## Imagens/PDFs
- Envie para `docs/assets/` e use: `![Figura](../assets/arquivo.png)`.

**Data:** 2025-08-10
