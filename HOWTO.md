1. Make a Gemfile in the 2022 folder with the following lines
```bash
source 'https://rubygems.org'
gem 'github-pages', group: :jekyll_plugins
gem 'jekyll-feed', group: :jekyll_plugins
gem 'jekyll-seo-tag', group: :jekyll_plugins
gem 'jekyll-sitemap', group: :jekyll_plugins
```

2. Install Ruby on your machine if you don't have it yet. Alternatively, you can use [rvm](https://rvm.io). The site uses Ruby 2.5.3.
3. Install Bundler if you don't have it yet.
```bash
gem install bundler
```

4. Install Jekyll dependencies.
```bash
bundle install
```

5. Run site locally.
```bash
bundle exec jekyll serve
```