source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.1.5'
gem 'therubyracer', platforms: :ruby, github: 'cowboyd/therubyracer'

gem 'mysql2', '>= 0.3.18', '< 0.5'

gem 'puma', '~> 3.7'

gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'turbolinks', '~> 5'
gem 'bootstrap'
gem 'jquery-rails'
gem 'popper_js'
gem 'tether-rails'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rubocop'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'annotate'
end

group :test do
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'database_cleaner'
end
