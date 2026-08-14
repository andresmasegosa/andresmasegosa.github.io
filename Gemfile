source 'https://rubygems.org'

gem 'jekyll'
gem 'jekyll-minibundle'
gem 'coderay'
gem 'rake'
gem 'font-awesome-less'

group :jekyll_plugins do
  gem 'sass' # add only if you're using sass for your stylesheets
  gem 'github-pages'
end

# jekyll-assets, uglifier and autoprefixer-rails were removed on 2026-08-14.
# GitHub Pages only runs whitelisted plugins, so none of them ever ran on the
# live site, no template used them, and the _svg source folder they were
# configured against does not exist. Locally they pulled in execjs, which
# needs a JavaScript runtime and broke `bundle exec jekyll build` on a machine
# without node. jekyll-responsive-image went for the same reason: it needs
# rmagick, hence ImageMagick.
