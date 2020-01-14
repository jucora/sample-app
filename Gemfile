source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

gem 'rails', '~> 5.2.3'
gem 'bootstrap-sass'
gem 'jquery-rails'
gem 'rails-controller-testing'
gem 'bcrypt', '~> 3.1', '>= 3.1.11'
gem 'puma', '~> 3.11'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'bootsnap', '>= 1.1.0', require: false
gem 'faker', :git => 'https://github.com/faker-ruby/faker.git', :branch => 'master'
gem 'will_paginate'
gem 'bootstrap-will_paginate'
gem 'carrierwave',             '1.2.2'
gem 'mini_magick',             '4.7.0'

gem "loofah", ">= 2.3.1"

gem 'rubocop-faker'

group :production do
  gem 'pg'
  gem 'fog'
end

group :development, :test do
  gem 'sqlite3'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'guard'
  gem 'listen'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
  gem 'minitest-reporters', '1.0.5'
  gem 'mini_backtrace',     '0.1.3'
  gem 'guard'
  gem 'guard-minitest',     '2.3.1'

end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
