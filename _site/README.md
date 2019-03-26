netinept.github.io
==================

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