source 'https://rubygems.org'

gem 'jekyll', '3.0.3'
gem 'jekyll-assets'
gem 'sass'
gem 'uglifier'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']