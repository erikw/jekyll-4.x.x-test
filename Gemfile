source 'https://rubygems.org'

gem 'jekyll', '~> 4.0'
gem 'webrick'
gem 'kramdown-parser-gfm' # Needed for kramdown v2

group :development do
  gem 'rake', '~> 13.0', require: false
end

group :jekyll_themes do
  #gem 'the-plain'
  gem 'the-plain', github: 'erikw/the-plain', branch: 'fix-48-jekyll-4.0'
end

group :jekyll_plugins do
  gem 'jekyll-feed', '~> 0.6'
  gem 'jekyll-google_search_console_verification_file', '~> 1.0'
  gem 'jekyll-glossary_tooltip', '~> 1.0'
end
