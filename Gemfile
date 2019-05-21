source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.4.6'

gem 'pry-rails'
gem 'puma', '~> 3.11'
gem 'rails', '~> 5.2.3'
gem 'rails-csrf-test-engine', github: 'drcapulet/rails-csrf-test-engine'
# Uncomment to work locally
# gem 'rails-csrf-test-engine', path: '../rails-csrf-test-engine'

group :development, :test do
  gem 'pry-byebug', platform: :mri
end
