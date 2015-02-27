source 'https://rubygems.org'
gem 'jekyll'

require 'json'
require 'open-uri'
require 'jekyll_asset_pipeline'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']