# Aani Beta Jekyll Site

This site uses [Jekyll](https://jekyllrb.com/) so you can write content in Markdown and have it automatically converted to HTML for GitHub Pages.

## Editing Content
- Edit or add Markdown files in the `_posts` folder for blog-style updates.
- Edit `index.md` for the homepage content.

## Local Development
1. Install Ruby and Bundler if you haven't already.
2. Run `bundle install` in this directory.
3. Start the local server:
   ```sh
   bundle exec jekyll serve
   ```
4. Visit `http://localhost:4000` to preview your site.

## Deploying to GitHub Pages
- Push your changes to the `main` branch.
- In your repo settings, set GitHub Pages to build from the `/static-site` folder (or root, if you move the site there).

## Custom Domain
- Add your domain to the `CNAME` file if using a custom domain.
