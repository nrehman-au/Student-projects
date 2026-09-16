# Student Project Portfolio

This is the Quarto source for the BSc and MSc Student Project Portfolio in Graph ML, self-supervised time-series learning, and vision foundation models.

## Preview locally

1. Install Quarto from <https://quarto.org/docs/get-started/>.
2. From this folder, run `quarto preview`.

## Render the static website

Run `quarto render`. The complete site is written to `_site/`.

## Publish with GitHub Pages

1. Create a public GitHub repository and push this folder to its `main` branch.
2. Replace `YOUR-USERNAME` in `_quarto.yml` with your GitHub username and repository name if needed.
3. In repository settings, give GitHub Actions read/write workflow permission.
4. Run the **Quarto Publish** workflow once, or run `quarto publish gh-pages` locally.
5. In **Settings → Pages**, select the `gh-pages` branch if GitHub has not selected it automatically.

The included workflow republishes the website whenever `main` is updated.
