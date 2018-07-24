# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

group :development do
  gem "pry"
end

group :test do
  gem "rspec", ">= 3.7.0"
  gem "rubocop", ">= 0.57.2"
end

gem 'simplecov',       :require => false
gem 'method_profiler', :require => false
gem 'coveralls',       :require => false

platform :rbx do
  gem 'json'
  gem 'racc'
  gem 'rubysl'
  gem 'rubinius-coverage'
end

gemspec
