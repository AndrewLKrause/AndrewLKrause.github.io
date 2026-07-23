# Quarto Reveal.js Presentation

This project is set up to create a presentation using Quarto and Reveal.js, and it is configured for deployment to GitHub Pages.

## Project Structure

- **_quarto.yml**: Main configuration file for the Quarto project.
- **index.qmd**: The main content file for the presentation, written in Quarto Markdown format.
- **.github/workflows/pages.yml**: GitHub Actions workflow for deploying the site to GitHub Pages.
- **docs/.nojekyll**: Prevents GitHub Pages from processing the site with Jekyll.
- **README.md**: Documentation for the project.

## Building the Presentation

To build the presentation, run the following command in your terminal:

```bash
quarto render index.qmd
```

This will generate the necessary HTML files for the presentation.

## Deploying to GitHub Pages

1. Ensure that your GitHub repository is set up to use GitHub Pages.
2. Push your changes to the main branch.
3. The GitHub Actions workflow defined in `.github/workflows/pages.yml` will automatically build and deploy your presentation to GitHub Pages.

## Viewing the Presentation

Once deployed, you can view your presentation at:

```
https://<your-username>.github.io/<your-repo-name>/
```

Replace `<your-username>` and `<your-repo-name>` with your GitHub username and repository name, respectively.