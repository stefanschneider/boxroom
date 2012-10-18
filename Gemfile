source 'http://rubygems.org'

gem 'rails', '3.2.8'
gem 'cloudfoundry-jquery-rails'
gem 'dynamic_form'
gem 'acts_as_tree'
gem 'paperclip'

   # If you use a different database in development, hide it from Cloud Foundry.
   group :development do
     gem 'sqlite3'
   end

   # Rails 3.1 can use the latest mysql2 gem.
   group :production do
     gem 'mysql2'
   end

   # For Ruby 1.9 Cloud Foundry requires a tweak to the jquery-rails gem.
   # gem 'jquery-rails'
   gem 'cloudfoundry-jquery-rails'

   # For Ruby 1.9 Cloud Foundry requires a tweak to devise.
   # Uncomment next line if you plan to use devise.
   # gem 'cloudfoundry-devise', :require => 'devise'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
  gem 'jquery-fileupload-rails'
end

group :test do
  gem 'factory_girl_rails'
end
