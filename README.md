# MkDocs Aula Starter

Projecte base per publicar apunts amb **MkDocs + GitHub Pages** i mostrar-los **progressivament**.

## Ús ràpid

1) Substitueix `<el-teu-usuari>` i `<el-teu-repo>` a `mkdocs.yml`.
2) Fes `git add . && git commit -m "mkdocs starter" && git push` a la branca `main`.
3) A GitHub: **Settings → Pages → Source: Deploy from a branch → Branch: gh-pages**.
4) Obre `https://<el-teu-usuari>.github.io/<el-teu-repo>/`.

### Afegir noves unitats de forma gradual

- Escriu el contingut a `docs/unitat2/` (o la unitat que correspongui).
- **Fes-la visible** afegint-la al menú `nav:` del `mkdocs.yml` (descomenta el bloc).
- Fes push a `main`; el workflow publicarà automàticament a `gh-pages`.

> Pots amagar temporalment una unitat **treient els enllaços del menú**; els fitxers poden seguir existint al repo, però no apareixeran a la web.
