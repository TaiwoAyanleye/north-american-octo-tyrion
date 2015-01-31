source 'https://rubygems.org'
ruby '2.2.0'

gem 'rails', '4.1.6'
gem 'bootstrap-sass', '2.0.0'
gem 'bcrypt-ruby', '3.0.1'
gem 'faker', '1.0.1'
gem 'will_paginate', '~> 3.0.6'
gem 'will_paginate-bootstrap'

group :development do
	gem 'sqlite3', '~> 1.3.10'
	gem 'annotate', '~> 2.4.1.beta'
end

group :assets do
	gem 'sass-rails', '~> 4.0.3'
	gem 'uglifier', '>= 1.3.0'
	gem 'coffee-rails', '~> 4.0.0'
end

gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0',          group: :doc
gem 'spring',        group: :development

group :test, :development do
	gem 'rspec-rails', '2.10.0'
	gem 'guard-rspec', '0.5.5'
	gem 'guard-spork', '0.3.2'
	gem 'spork', '0.9.0'
end

group :test do
	# gem "minitest"
	# gem 'rubysl-test-unit'
	gem 'test-unit'
	gem 'selenium-webdriver', '~> 2.35.1'
	gem 'capybara', '1.1.2'
	gem 'factory_girl_rails'
	gem 'cucumber-rails', '1.2.1', require: false
	gem 'database_cleaner', '~> 1.4.0'
end

group :production do
	gem 'pg', '~> 0.18.1'
end