# ECMS
The goal of this Rails Engine is to a allow the creation of a functioning, fully featured, basic CMS in minutes.

It's customized for my own needs but could be of use for somebody else.

## Installation and Usage

Five minutes to go from zero to hero!

Install the latest version of Rails and other needed gem
+ Install Ruby 2.7.2 or later
+ Install Rails 6.1.1 or later
  + `$ gem install rails`
+ Install image library -- TODO to be determined
+ Install a js runtime. For example:
  + `$ gem install therubyracer`
+ Create a new Rails application
		+ `$ rails new my_app_name --database=mysql`
+ Go there
  + `$ cd my_app_name`
+ Configure the locales if needed
  + If English is not the site's default language, add the following line in the config/application.rb
		+ config.i18n.default_locale = :de
  + If you want to support other languages than English, follow the following url and copy the relevant files to the config/locales/ folder: https://github.com/svenfuchs/rails-i18n/tree/master/rails/locale
  + Add this line with the app's relevant locales. Still in application.rb
    + config.i18n.available_locales = [ :de, :fr ]
+ Change the time zone if necessary to reflect where the site or the main audience is based. Uncomment and modify the following line in application.rb
  + config.time_zone = 'Europe/Berlin'
+ Add this line to your application's Gemfile:
  + gem 'ecms'
+ Then execute:
  + `$ bundle`
+ TODO -> more setup instructions


## License
The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
