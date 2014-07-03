source 'https://rubygems.org'
ruby '2.0.0'

gem 'rails', '4.1.2'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'bootstrap-sass'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'devise', '~> 3.1.0.rc2'


#only use sqlite gem in development and testing
group :development, :test do
	gem 'sqlite3'
end

#only use sqlite gem in production
group :production, :test do
	gem 'pg'
	gem 'rails_12factor'
end


gem 'sdoc', '~> 0.4.0',          group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin]
