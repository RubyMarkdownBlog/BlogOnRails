source "https://rubygems.org"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 8.0.2"
# The modern asset pipeline for Rails [https://github.com/rails/propshaft]
gem "propshaft", "1.1.0"
# Use sqlite3 as the database for Active Record
gem "sqlite3", ">= 2.1"
# Use the Puma web server [https://github.com/puma/puma]
gem "puma", "6.6.0"
# Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
gem "importmap-rails", "2.1.0"
# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "turbo-rails", "2.0.13"
# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem "stimulus-rails", "1.3.4"
# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem "jbuilder", "2.13.0"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ windows jruby ]

# Use the database-backed adapters for Rails.cache, Active Job, and Action Cable
gem "solid_cache", "1.0.7"
gem "solid_queue", "1.1.4"
gem "solid_cable", "3.0.7"

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", "1.18.4", require: false

# Deploy this application anywhere as a Docker container [https://kamal-deploy.org]
gem "kamal", "2.5.3", require: false

# Add HTTP asset caching/compression and X-Sendfile acceleration to Puma [https://github.com/basecamp/thruster/]
gem "thruster", "~> 0.1.12", require: false

gem "redcarpet", "~> 3.6.1" # Process markdown to html
gem "rouge", "~> 4.5.1" # Highlight code

gem "ancestry", "~> 4.3.3" # Handle 'categories' which have 'parent' and 'children'

gem "faraday", "~> 2.12.2"

gem "safe_yaml", "~> 1.0.5"

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

group :development, :test do
  gem "annotaterb", "4.14.0"

  gem "factory_bot_rails", "~> 6.4.4"
  gem "rspec-rails", "~> 7.1.1"

  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"

  # Static analysis for security vulnerabilities [https://brakemanscanner.org/]
  gem "brakeman", require: false

  # Omakase Ruby styling [https://github.com/rails/rubocop-rails-omakase/]
  gem "rubocop-rails-omakase", require: false
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "selenium-webdriver"
end
