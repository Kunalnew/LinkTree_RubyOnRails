source "https://rubygems.org"

gem "rails", "~> 7.2.1"
gem "sprockets-rails"

gem "sqlite3", ">= 1.4"

gem "puma", ">= 5.0"

gem "importmap-rails"

gem "turbo-rails"

gem "stimulus-rails"

gem "jbuilder"

# my custom gems
gem 'devise'
gem 'friendly_id', '~> 5.5.0'



# gem "bcrypt", "~> 3.1.7"

gem "tzinfo-data", platforms: %i[ windows jruby ]


gem "bootsnap", require: false


# gem "image_processing", "~> 1.2"

group :development, :test do
  
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"

  
  gem "brakeman", require: false

  
  gem "rubocop-rails-omakase", require: false
end

group :development do
  
  gem "web-console"
end

group :test do
  
  gem "capybara"
  gem "selenium-webdriver"
end
