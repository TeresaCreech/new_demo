source 'https://rubygems.org'

ruby '1.9.3'

gem 'rails', '3.2.16'

# Use 1.3.5 version of sqlite3 only in development environment tac
group :development do
	gem 'sqlite3', '1.3.5'
end

# Changed sass-rails from ~=3.2.3   tac
# Changed coffee-rails from ~=3.2.1 tac
# Changed uglifier from >=1.0.3     tac
# Do not allow upgrades (removed >= and ~=)

  gem 'sass-rails',   '3.2.4'
  gem 'coffee-rails', '3.2.2'
  gem 'uglifier', '1.2.3'

# Did not add 2.0.0 to jquery-rails. Not available this system. tac
   gem 'jquery-rails'
   gem 'jbuilder', '1.0.2'
   gem 'turbolinks', '1.1.1'


group :production do
     gem 'pg', '0.15.1'
     gem 'rails_12factor', '0.0.2'
end