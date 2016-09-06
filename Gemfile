source "https://rubygems.org"

gemspec

gem "rdf",                '~> 2.0.2'
gem "jruby-openssl",      platforms: :jruby
gem "nokogiri",           '~> 1.6'

group :development, :test do
  gem "redcarpet",      platform: :ruby
  gem 'simplecov',      require: false, platform: :mri
  gem 'coveralls',      require: false, platform: :mri
end

group :debug do
  gem 'shotgun'
  gem "byebug", platforms: :mri
end

platforms :rbx do
  gem 'rubysl', '~> 2.0'
  gem 'rubinius', '~> 2.0'
end
