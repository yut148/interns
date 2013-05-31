source 'https://rubygems.org'

ruby '2.0.0'

gem 'rails', '~> 4.0.0.beta1'
gem 'jquery-rails'
gem 'dynamic_form'
gem 'haml-rails'
gem 'sorcery', github: 'NoamB/sorcery'
gem 'activesupport', '~> 4.0.0.beta1'
gem 'simple_form', '~> 3.0.0.beta1'
gem 'puma', require: false
gem 'redcarpet'
gem 'gravatarify'
gem 'simple_enum'
gem 'lingman', github: 'hrysd/lingman'
gem 'ranked-model'
gem 'bootstrap-sass', '~> 2.3.0.1'
gem 'i18n-js'

group :assets do
  gem 'sprockets-rails', github: 'rails/sprockets-rails'  
  gem 'sass-rails', git: 'git@github.com:rails/sass-rails.git'
  gem 'coffee-rails', git: 'git@github.com:rails/coffee-rails.git'
  gem 'uglifier', '>= 1.0.3'
  gem 'compass-rails', github: 'milgner/compass-rails', ref: '1749c06f15dc4b058427e7969810457213647fb8'
  gem "font-awesome-rails"
end

group :production do
  gem 'pg'
end

group :development do
  gem 'sqlite3'
  gem 'erb2haml'
  gem 'pry-rails'
  gem 'heroku_san'
end

group :development, :test do
  gem 'capybara', '~> 2.0.3'
  gem 'rspec-rails', '~> 2.13.0'
  gem 'factory_girl_rails'
  gem 'capybara-webkit'
  gem 'launchy'
end
