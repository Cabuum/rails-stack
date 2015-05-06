# Rails Stack
![App Version](https://img.shields.io/badge/app%20version-1.4.2-brightgreen.svg)
![Built With](https://img.shields.io/badge/built%20with-love-ff69b4.svg)
![License MIT](https://img.shields.io/badge/licence-MIT-blue.svg)

*A pre configured Ruby on Rails stack to be a kick ass in your awesome projects*

#### Contents

- [Front-End](#front-end-things)
- [Gems](#gems-for)
- Test structure
- What is pre-configured
- [First steps to do the magic!](#first-steps-to-do-the-magic)
 

### Front-End things *

 - **Javascript** libraries: 
   - [angular.js][angular]: *HTML is great for declaring static documents, but it falters when we try to use it for declaring dynamic views in web-applications.*
   - [bower.js][bower]: *Bower manages all front-end things like css frameworks, javascript libraries, for you.*
   - [jquery.js][jquery]: *jQuery is a fast, small, and feature-rich JavaScript library.*
 - **CSS** frameworks:
   - [lumx][lumx]: *The first responsive front-end framework based on AngularJS & Google Material Design specifications.*
   - [grid][bootstrap-grid]: *We customized the bootstrap to only get the grid, use sparingly.*


### Gems for*

 - **Tests**: 
   - [byebug][byebug]: *Byebug is a simple to use, feature rich debugger for Ruby 2.*
   - [rspec-rails][rspec-rails]: *Behaviour Driven Development for Ruby.*
   - [factory_girl_rails][factory_girl_rails]: *factory_girl is a fixtures replacement with a straightforward definition syntax, support for multiple build strategies, and support for multiple factories for the same class, including factory inheritance.*
   - [forgery][forgery]: *Easy and customizable generation of forged data.*
   - [awesome_print][awesome_print]: *Pretty print your Ruby objects with style -- in full color and with proper indentation*
   - [shoulda-matchers][shoulda-matchers]: *Collection of testing matchers extracted from Shoulda.*
   - [capybara][capybara]: *Acceptance test framework for web applications*
   - [database_cleaner][database_cleaner]: *Strategies for cleaning databases in Ruby. Can be used to ensure a clean state for testing.*
   
 - **Infraestructure**: 
   - [rails][rails]: *Rails is a web-application framework that includes everything needed to create database-backed web applications according to the Model-View-Controller (MVC) pattern.*
   - [pg][pg]: *PostgreSQL is a powerful, open source object-relational database system. It has more than 15 years of active development and a proven architecture that has earned it a strong reputation for reliability, data integrity, and correctness.*
   - [enumerate_it][enumerate_it]: *Enumerations for Ruby with some magic powers!*
   - [dotenv][dotenv]: *Loads environment variables from `.env`.*
   - [spring][spring]: *Rails application preloader.*
   - [devise][devise]: *Flexible authentication solution for Rails with Warden.*
   - [unicorn][unicorn]: *Unicorn is an HTTP server for Rack applications designed to only serve fast clients on low-latency, high-bandwidth connections and take advantage of features in Unix/Unix-like kernels.*

 - **Form Helpers**: 
   - [simple_form][simple_form]: *Forms made easy for Rails! It's tied to a simple DSL, with no opinion on markup.*
   - [responders][responders]: *A set of Rails responders to dry up your application.*
   - [devise-i18n-views][devise-i18n-views]: *I18n support for devise views*
   - [jbuilder][jbuilder]: *Create JSON structures via a Builder-style DSL*

 - **Deployment and Production**: 
   - [rails_12factor][rails_12factor]: *Makes running your Rails app easier. Based on the ideas behind 12factor.net*

 - **Front-end**: 
   - [uglifier][uglifier]: *Ruby wrapper for UglifyJS JavaScript compressor.*
   - [bower][bower]: *Bower manages all front-end things like css frameworks, javascript libraries, for you.*
   - [turbolinks][turbolinks]: *Turbolinks makes following links in your web application faster (use with Rails Asset Pipeline)*

 - **Tracking and Metrics**: 
   - [codeclimate-test-reporter][codeclimate-test-reporter]: *Uploads Ruby test coverage data to Code Climate.*
   - [simplecov][simplecov]: *SimpleCov is a code coverage analysis tool for Ruby.*


\* Not described any dependency.


## First Steps to do the Magic!

### CodeClimate

 - Adding your repo to CodeClimate and setting up the test coverage: 
   - Log-In with your GitHub account -> Add OpenSource Repo -> type your github repo name like -> 
   - Go to settings on tab "Test Coverage" copy the token and put on `.travis.yml` file on key called `repo_token`

### Travis CI

 - To use the Continuous Integration provided by [TravisCI][travis] you'll need to:
 - Log-In with your GitHub account -> Then access your repo's list: https://travis-ci.org/profile/YOUR_USERNAME and add one -> Click in the gear icon (settings) for your chosed repo and change the settings to this: 

### Heroku

 - Log in Heroku page -> Add a new app with a simple name like myapp -> and run inside the root app: `gem install travis` -> `travis setup heroku --force` :+1:


[angular]: https://angularjs.org/
[bower]: https://bower.io/
[lumx]: http://ui.lumapps.com/
[jquery]: http://jquery.com/
[bootstrap-grid]: http://getbootstrap.com/css/#grid
[rails]: http://rubyonrails.org/
[pg]: http://www.postgresql.org/
[uglifier]: https://github.com/lautis/uglifier
[enumerate_it]: https://github.com/cassiomarques/enumerate_it
[devise]: https://github.com/plataformatec/devise
[devise-i18n-views]: https://github.com/mcasimir/devise-i18n-views
[simple_form]: https://github.com/plataformatec/simple_form
[responders]: https://github.com/plataformatec/responders
[turbolinks]: https://github.com/rails/turbolinks
[jbuilder]: https://github.com/rails/jbuilder
[dotenv]: https://github.com/bkeepers/dotenv
[unicorn]: https://github.com/defunkt/unicorn
[byebug]: https://github.com/deivid-rodriguez/byebug
[rspec-rails]: https://github.com/rspec/rspec-rails
[factory_girl_rails]: https://github.com/thoughtbot/factory_girl_rails
[forgery]: https://github.com/sevenwire/forgery
[awesome_print]: https://github.com/michaeldv/awesome_print
[shoulda-matchers]: https://github.com/thoughtbot/shoulda-matchers
[spring]: https://github.com/rails/spring
[capybara]: http://jnicklas.github.io/capybara
[database_cleaner]: https://github.com/DatabaseCleaner/database_cleaner
[simplecov]: https://github.com/colszowka/simplecov
[codeclimate-test-reporter]: http://codeclimate.com
[rails_12factor]: https://github.com/heroku/rails_12factor
[travis]: https://travis-ci.org/
