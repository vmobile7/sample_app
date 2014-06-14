source 'https://rubygems.org'
ruby '2.0.0'
#ruby-gemset=tutorial_4.0

gem 'rails', '4.1.1'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0',          group: :doc
gem 'spring',        group: :development

group :production do
    gem "pg", "0.15.1"
    gem "rails_12factor", "0.0.2"
end

group :development, :test do
    gem "rspec-rails"
    gem "sqlite3"
    gem "pry-rails"
    gem "pry-debugger"
    gem "pry-doc"
    gem "rdefs"
end

group :test do
    gem "selenium-webdriver"
    gem "capybara"
end
