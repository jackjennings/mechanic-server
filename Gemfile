source 'https://rubygems.org'
ruby '2.2.2'

gem 'rack', '1.5.2'
gem 'activerecord', '~> 4.2'
gem 'grape', '0.6.1'
gem 'rack-cors'
gem 'octokit', '~> 2.0'
gem 'sinatra'
gem 'builder'
gem 'puma'

group :test do
  gem 'minitest', '~> 5'
  gem 'rack-test'
  gem 'guard'
  gem 'guard-minitest'
end

group :development, :test do
  gem 'rack-env'
  gem 'sqlite3'
end

group :production do
  gem 'pg'
end
