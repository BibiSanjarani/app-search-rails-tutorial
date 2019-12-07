source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

gem 'rails', '~> 5.2.1', '>= 5.2.1.1'
gem 'sqlite3'
gem 'puma', '~> 3.12', '>= 3.12.2'
gem 'sass-rails', '~> 5.0', '>= 5.0.7'
gem 'uglifier', '>= 1.3.0'

gem 'bootstrap', '~> 4.1.2'
gem 'jquery-rails', '>= 4.3.1'

gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 3.6.0'
  gem 'listen', '>= 3.1.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.1'
end

group :test do
  gem 'rspec-rails', '~> 3.7', '>= 3.7.2'

  gem 'capybara', '>= 3.0.1', '< 4.0'
  gem 'selenium-webdriver', '>= 3.11.0'
  gem 'chromedriver-helper', '>= 1.2.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
