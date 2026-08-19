# Math + Science Club

Barebones Jekyll site intended for GitHub Pages.

## Local preview

If you have Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## Publishing

1. Create a GitHub repository for this directory and push its `main` branch.
2. In **Settings → Pages**, deploy from `main` at the repository root.
3. Set the custom domain to `www.mathscienceclub.org`; the tracked `CNAME` file
   keeps that setting with the site.
4. At the domain's DNS host, set the `www` CNAME to `knowingant.github.io`
   (not a repository path). See GitHub's custom-domain documentation before
   changing live records.

The apex name (`mathscienceclub.org`) can redirect to `www.mathscienceclub.org`
after it has an A record pointing to GitHub Pages.
