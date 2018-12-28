source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.1'

# Pg is the Ruby interface to the PostgreSQL RDBMS [http://www.postgresql.org/]
gem 'pg', '~> 1.1', '>= 1.1.3'

# Use Puma as the app server
gem 'puma', '~> 3.11'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

# JSON API(jsonapi.org) serializer that works with rails and can be used to serialize any kind of ruby objects
gem 'fast_jsonapi', '~> 1.5'

# Great Ruby dubugging companion: pretty print Ruby objects to visualize their structure. Supports custom object formatting via plugins
gem 'awesome_print', '~> 1.8'

# Help to kill N+1 queries and unused eager loading.
gem 'bullet', '~> 5.9'

# Automatic Ruby code style checking tool. Aims to enforce the community-driven Ruby Style Guide.
gem 'rubocop', '~> 0.60.0'

# Extends Rails seeds to split out complex seeds into multiple files and lets each environment have it's own seeds.
gem 'seedbank', '~> 0.4.0'

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem 'rack-cors'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
