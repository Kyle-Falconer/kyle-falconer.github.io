netinept.github.io
==================

[![Netlify Status](https://api.netlify.com/api/v1/badges/1b660ad8-8980-48ce-8979-b5ff222dd3cb/deploy-status)](https://app.netlify.com/sites/blissful-mahavira-094a65/deploys)

Development:
------------
This site uses the `github-pages` gem, which includes [Jekyll](https://jekyllrb.com/) and some other plugins.

Use [Ruby Version Manager](https://rvm.io/) to install Ruby 2.4.3:

```bash
rvm install 2.4.3
```

Then install the `github-pages` gem and build the site:

```bash
gem install github-pages
jekyll build
```

Then tell Jekyll to host start the local webserver to view it in a browser:

```bash
bundle exec jekyll serve
```