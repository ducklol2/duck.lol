# duck.lol

## Run locally

```sh
cd docs
bundle exec jekyll serve
```

## Create with

```sh
mkdir docs
cd docs
jekyll new --skip-bundle .
```

Update `Gemfile` [for Github](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site).

```sh
bundle install
bundle add webrick
```