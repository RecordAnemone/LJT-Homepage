# LJT-Homepage

Personal academic homepage of Junteng Liu, first-year PhD candidate at the HKUST NLP Group, Hong Kong University of Science and Technology.

Built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template, forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/).

## Deployment

This site is deployed via GitHub Pages. To enable it:

1. Go to **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose one of the following sources:
   - **GitHub Actions**: use the "Deploy Academic Pages template site to Pages" workflow (`.github/workflows/jekyll.yml`).
   - **Deploy from a branch**: select the `gh-pages` branch and the `/ (root)` folder. The "Build and deploy to gh-pages" workflow (`.github/workflows/deploy-gh-pages.yml`) builds the site and pushes it to `gh-pages` on every push to `master`.
3. The site will be available at `https://recordanemone.github.io/LJT-Homepage/`.

## Local development

If you are not familiar with git, you can directly edit the configuration and Markdown files in the github.com interface. To run the site locally:

1. Make sure you have ruby-dev, bundler, and nodejs installed
1. Run `bundle install` to install ruby dependencies
1. Run `jekyll serve -l -H localhost` to generate the HTML and serve it from `localhost:4000` (the local server will automatically rebuild and refresh the pages on change).

See the [Academic Pages documentation](https://github.com/academicpages/academicpages.github.io) for more details.
