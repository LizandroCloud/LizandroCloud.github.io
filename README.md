# Página pessoal de Lizandro Santos

Site acadêmico feito com [Hugo](https://gohugo.io/) e o tema [Hugo Blox](https://hugoblox.com/) (modelo Academic CV),
publicado no GitHub Pages em https://lizandrocloud.github.io.

## Como editar

| O que mudar | Arquivo |
| --- | --- |
| Nome, cargo, biografia, links, formação, interesses | `data/authors/me.yaml` |
| Foto | `assets/media/authors/me.png` |
| Seções da página inicial (pesquisa, contato) | `content/_index.md` |
| Projetos | `content/projects/<projeto>/index.md` |
| Menu | `config/_default/menus.yaml` |
| Nome do site, cores, rodapé | `config/_default/params.yaml` |

Publicações: coloque um arquivo `publications.bib` na raiz do repositório. A action
*Import Publications From Bibtex* converte as entradas e abre um PR com as páginas.

## Publicação

Cada push na branch `main` roda `.github/workflows/deploy.yml`, que gera o site e o publica
no GitHub Pages. Em *Settings → Pages*, a origem precisa estar como **GitHub Actions**.

## Rodar localmente

Requer Hugo extended (versão em `hugoblox.yaml`), Go e Node com pnpm.

```bash
pnpm install
hugo server
```
