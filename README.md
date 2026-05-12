# Physics-R1 — Project Page

Project page for **[Physics-R1: An Audited Olympiad Corpus and Recipe for Visual Physics Reasoning](https://shanyang-me.github.io/physics-r1-page/)**.

- **Page:** <https://shanyang-me.github.io/physics-r1-page/>
- **Code:** <https://github.com/shanyang-me/physics-r1-neurips2026>
- **Datasets:** [physics-r1-anonymous on Hugging Face](https://huggingface.co/physics-r1-anonymous)
- **Author:** Shan Yang &nbsp;·&nbsp; [alexyangshan@gmail.com](mailto:alexyangshan@gmail.com)

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000/
```

## Deploy

GitHub Pages → repository **Settings → Pages → Build and deployment**:
- Source: **Deploy from a branch**
- Branch: `main` / folder: `/` (root)

## Updating the paper PDF

```bash
cp /path/to/main.pdf static/pdfs/physics-r1.pdf
git add static/pdfs/physics-r1.pdf
git commit -m "docs: update paper PDF"
git push
```

## Credits

Built on top of the
[Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template)
by Eliahu Horwitz.
