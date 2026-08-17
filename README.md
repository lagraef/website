# Lindsay Graef personal website

This is a simple Quarto + GitHub Pages website.

## Local preview

1. Install Quarto: https://quarto.org/docs/get-started/
2. Open this folder in RStudio or VS Code.
3. Run:

```bash
quarto preview
```

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload these files.
3. In `_quarto.yml`, replace `YOUR-GITHUB-USERNAME` and `YOUR-REPO-NAME`.
4. Run:

```bash
quarto render
```

5. Commit the generated `docs/` folder.
6. In GitHub, go to Settings > Pages.
7. Set the source to deploy from the `docs/` folder on the main branch.

## CV

Replace `cv/Lindsay-Graef-CV.pdf` with your actual CV using the same filename.
