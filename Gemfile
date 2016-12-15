source 'https://rubygems.org'
source 'https://code.stripe.com'
ruby "2.3.0"

gem 'rails', '~> 5.0.0', '>= 5.0.0.1'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'bootstrap-sass', '~> 3.0.3.0'
gem "paperclip", "~> 3.0"
gem "paperclip-dropbox", ">= 1.1.7"
gem "figaro"
gem 'devise'
gem 'stripe', :git => 'https://github.com/stripe/stripe-ruby'


group :production do
  gem 'pg'
  gem 'rails_12factor'
end

group :development, :test do
 
  gem 'byebug', platform: :mri
  gem 'sqlite3'

end

group :development do

  gem 'web-console'
  gem 'listen', '~> 3.0.5'
  
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :doc do
  gem 'sdoc', require: false
end


