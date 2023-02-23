# frozen_string_literal: true

source 'http://rubygems.org'

ruby '3.2.0'

gem 'byebug'
gem 'rspec'

group :production do
gem 'pg' # for Heroku deployment
end
group :development, :test do
gem 'sqlite3'
end