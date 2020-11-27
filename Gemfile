source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.2'

gem 'rails', '~> 6.0.3', '>= 6.0.3.4'

gem 'bootsnap', '>= 1.4.2', require: false
gem 'image_processing', '~> 1.2'
gem 'jbuilder', '~> 2.7'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 4.1'
gem 'redis', '~> 4.0'
gem 'sass-rails', '>= 6'
gem 'turbolinks', '~> 5'
gem 'webpacker', '~> 4.0'

# Custom gems
gem 'devise', '~> 4.7', '>= 4.7.3'
gem 'friendly_id', '~> 5.4', '>= 5.4.1'
gem 'name_of_person', '~> 1.1', '>= 1.1.1'
gem 'sidekiq', '~> 6.1', '>= 6.1.2'
gem 'stripe_event', '~> 2.3', '>= 2.3.1'
gem 'simple_discussion', '~> 1.2'
gem 'stripe', '~> 5.28'
gem 'whenever', '~> 1.0'
gem "inline_svg", "~> 1.7"
gem "pagy", "~> 3.10"
gem "pay", "~> 2.2"

group :development, :test do
  gem 'annotate', '~> 3.1', '>= 3.1.1'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'faker', '~> 2.15', '>= 2.15.1'
  gem "pry-rails", "~> 0.3.9"
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
