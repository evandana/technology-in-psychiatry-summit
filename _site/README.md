# Tech solution

1. Create Gemfile in this repo:
    ```ruby
    source 'https://rubygems.org'
    gem 'github-pages', group: :jekyll_plugins
    ```
1. In terminal 1, run: `bundle exec jekyll build --watch` 
1. In terminal 2, run: `bundle exec jekyll serve`