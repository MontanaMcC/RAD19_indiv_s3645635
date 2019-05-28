# RAD Assignment

Montana McCallum - s3645635 
Highest Level Attempted - DI
Time Spent - Around 50 hours on Stage 2 (5 hours a day across 10 days) with another 30 on Stage 1. Total 80 hours. 
Heroku - https://shielded-bastion-59596.herokuapp.com/ 

Last Heroku Log - 
Counting objects: 756, done.
Compressing objects: 100% (619/619), done.
Writing objects: 100% (756/756), 971.16 KiB | 13.87 MiB/s, done.
Total 756 (delta 47), reused 0 (delta 0)
remote: Compressing source files... done.
remote: Building source:
remote: 
remote:  !     Warning: Multiple default buildpacks reported the ability to handle this app. The first buildpack in the list below will be used.
remote:                         Detected buildpacks: Ruby,Node.js
remote:                         See https://devcenter.heroku.com/articles/buildpacks#buildpack-detect-order
remote: -----> Ruby app detected
remote: -----> Compiling Ruby/Rails
remote: -----> Using Ruby version: ruby-2.5.3
remote: -----> Installing dependencies using bundler 1.15.2
remote:        Running: bundle install --without development:test --path vendor/bundle --binstubs vendor/bundle/bin -j4 --deployment
remote:        Your Gemfile lists the gem carrierwave (>= 0) more than once.
remote:        You should probably keep only one of them.
remote:        While it's not a problem now, it could cause errors if you change the version of one of them later.
remote:        Warning: the running version of Bundler (1.15.2) is older than the version that created the lockfile (1.17.2). We suggest you upgrade to the latest version of Bundler by running `gem install bundler`.
remote:        Fetching gem metadata from https://rubygems.org/............
remote:        Fetching version metadata from https://rubygems.org/..
remote:        Fetching dependency metadata from https://rubygems.org/.
remote:        Fetching rake 12.3.2
remote:        Fetching concurrent-ruby 1.1.5
remote:        Fetching minitest 5.11.3
remote:        Installing minitest 5.11.3
remote:        Installing rake 12.3.2
remote:        Installing concurrent-ruby 1.1.5
remote:        Fetching thread_safe 0.3.6
remote:        Installing thread_safe 0.3.6
remote:        Fetching builder 3.2.3
remote:        Installing builder 3.2.3
remote:        Fetching erubi 1.8.0
remote:        Installing erubi 1.8.0
remote:        Fetching mini_portile2 2.4.0
remote:        Installing mini_portile2 2.4.0
remote:        Fetching crass 1.0.4
remote:        Installing crass 1.0.4
remote:        Fetching rack 2.0.7
remote:        Installing rack 2.0.7
remote:        Fetching nio4r 2.3.1
remote:        Fetching websocket-extensions 0.1.3
remote:        Installing nio4r 2.3.1 with native extensions
remote:        Installing websocket-extensions 0.1.3
remote:        Fetching mini_mime 1.0.1
remote:        Installing mini_mime 1.0.1
remote:        Fetching arel 8.0.0
remote:        Installing arel 8.0.0
remote:        Fetching execjs 2.7.0
remote:        Installing execjs 2.7.0
remote:        Fetching bcrypt 3.1.12
remote:        Installing bcrypt 3.1.12 with native extensions
remote:        Fetching rb-fsevent 0.10.3
remote:        Installing rb-fsevent 0.10.3
remote:        Fetching ffi 1.11.1
remote:        Installing ffi 1.11.1 with native extensions
remote:        Using bundler 1.15.2
remote:        Fetching mime-types-data 3.2019.0331
remote:        Installing mime-types-data 3.2019.0331
remote:        Fetching coffee-script-source 1.12.2
remote:        Installing coffee-script-source 1.12.2
remote:        Fetching method_source 0.9.2
remote:        Installing method_source 0.9.2
remote:        Fetching thor 0.20.3
remote:        Installing thor 0.20.3
remote:        Fetching pg 0.20.0
remote:        Installing pg 0.20.0 with native extensions
remote:        Fetching puma 3.12.1
remote:        Installing puma 3.12.1 with native extensions
remote:        Fetching tilt 2.0.9
remote:        Installing tilt 2.0.9
remote:        Fetching turbolinks-source 5.2.0
remote:        Installing turbolinks-source 5.2.0
remote:        Fetching tzinfo 1.2.5
remote:        Installing tzinfo 1.2.5
remote:        Fetching nokogiri 1.10.3
remote:        Installing nokogiri 1.10.3 with native extensions
remote:        Fetching i18n 1.6.0
remote:        Installing i18n 1.6.0
remote:        Fetching websocket-driver 0.6.5
remote:        Installing websocket-driver 0.6.5 with native extensions
remote:        Fetching mail 2.7.1
remote:        Installing mail 2.7.1
remote:        Fetching rack-test 1.1.0
remote:        Installing rack-test 1.1.0
remote:        Fetching sprockets 3.7.2
remote:        Installing sprockets 3.7.2
remote:        Fetching autoprefixer-rails 9.5.1.1
remote:        Installing autoprefixer-rails 9.5.1.1
remote:        Fetching uglifier 4.1.20
remote:        Installing uglifier 4.1.20
remote:        Fetching mime-types 3.2.2
remote:        Installing mime-types 3.2.2
remote:        Fetching coffee-script 2.4.1
remote:        Installing coffee-script 2.4.1
remote:        Fetching rb-inotify 0.10.0
remote:        Installing rb-inotify 0.10.0
remote:        Fetching turbolinks 5.2.0
remote:        Installing turbolinks 5.2.0
remote:        Fetching activesupport 5.1.7
remote:        Installing activesupport 5.1.7
remote:        Fetching sass-listen 4.0.0
remote:        Installing sass-listen 4.0.0
remote:        Fetching globalid 0.4.2
remote:        Installing globalid 0.4.2
remote:        Fetching activemodel 5.1.7
remote:        Installing activemodel 5.1.7
remote:        Fetching jbuilder 2.9.1
remote:        Installing jbuilder 2.9.1
remote:        Fetching sass 3.7.4
remote:        Installing sass 3.7.4
remote:        Fetching activejob 5.1.7
remote:        Installing activejob 5.1.7
remote:        Fetching activerecord 5.1.7
remote:        Installing activerecord 5.1.7
remote:        Fetching carrierwave 1.3.1
remote:        Installing carrierwave 1.3.1
remote:        Fetching bootstrap-sass 3.3.6
remote:        Installing bootstrap-sass 3.3.6
remote:        Fetching rails-dom-testing 2.0.3
remote:        Fetching loofah 2.2.3
remote:        Installing rails-dom-testing 2.0.3
remote:        Installing loofah 2.2.3
remote:        Fetching rails-html-sanitizer 1.0.4
remote:        Installing rails-html-sanitizer 1.0.4
remote:        Fetching actionview 5.1.7
remote:        Installing actionview 5.1.7
remote:        Fetching actionpack 5.1.7
remote:        Installing actionpack 5.1.7
remote:        Fetching actionmailer 5.1.7
remote:        Fetching railties 5.1.7
remote:        Fetching actioncable 5.1.7
remote:        Installing actionmailer 5.1.7
remote:        Installing actioncable 5.1.7
remote:        Installing railties 5.1.7
remote:        Fetching sprockets-rails 3.2.1
remote:        Installing sprockets-rails 3.2.1
remote:        Fetching jquery-rails 4.3.3
remote:        Fetching coffee-rails 4.2.2
remote:        Fetching rails 5.1.7
remote:        Installing coffee-rails 4.2.2
remote:        Installing rails 5.1.7
remote:        Fetching rails-ujs 0.1.0
remote:        Installing rails-ujs 0.1.0
remote:        Installing jquery-rails 4.3.3
remote:        Fetching sass-rails 5.0.7
remote:        Installing sass-rails 5.0.7
remote:        Bundle complete! 23 Gemfile dependencies, 63 gems now installed.
remote:        Gems in the groups development and test were not installed.
remote:        Bundled gems are installed into ./vendor/bundle.
remote:        Post-install message from i18n:
remote:        
remote:        HEADS UP! i18n 1.1 changed fallbacks to exclude default locale.
remote:        But that may break your application.
remote:        
remote:        Please check your Rails app for 'config.i18n.fallbacks = true'.
remote:        If you're using I18n (>= 1.1.0) and Rails (< 5.2.2), this should be
remote:        'config.i18n.fallbacks = [I18n.default_locale]'.
remote:        If not, fallbacks will be broken in your app by I18n 1.1.x.
remote:        
remote:        For more info see:
remote:        https://github.com/svenfuchs/i18n/releases/tag/v1.1.0
remote:        
remote:        Post-install message from sass:
remote:        
remote:        Ruby Sass has reached end-of-life and should no longer be used.
remote:        
remote:        * If you use Sass as a command-line tool, we recommend using Dart Sass, the new
remote:          primary implementation: https://sass-lang.com/install
remote:        
remote:        * If you use Sass as a plug-in for a Ruby web framework, we recommend using the
remote:          sassc gem: https://github.com/sass/sassc-ruby#readme
remote:        
remote:        * For more details, please refer to the Sass blog:
remote:          https://sass-lang.com/blog/posts/7828841
remote:        
remote:        Bundle completed (45.38s)
remote:        Cleaning up the bundler cache.
remote: -----> Installing node-v10.14.1-linux-x64
remote: -----> Detecting rake tasks
remote: -----> Preparing app for Rails asset pipeline
remote:        Running: rake assets:precompile
remote:        Yarn executable was not detected in the system.
remote:        Download Yarn at https://yarnpkg.com/en/docs/install
remote:        I, [2019-05-28T13:08:23.868444 #1497]  INFO -- : Writing /tmp/build_943fc98459748fd57245b7180732f530/public/assets/fallback/default-781422d08c8ff5597ad80028f059a8142325ab5bc07e5d67b5407e223d51b14a.png
remote:        I, [2019-05-28T13:08:28.328993 #1497]  INFO -- : Writing /tmp/build_943fc98459748fd57245b7180732f530/public/assets/application-35d1dc7a8b5019ffbe4b0abf8e63d2c9f7b1e1608a1e1efa24567e98f0e3d2a1.js
remote:        I, [2019-05-28T13:08:28.329782 #1497]  INFO -- : Writing /tmp/build_943fc98459748fd57245b7180732f530/public/assets/application-35d1dc7a8b5019ffbe4b0abf8e63d2c9f7b1e1608a1e1efa24567e98f0e3d2a1.js.gz
remote:        I, [2019-05-28T13:08:34.537830 #1497]  INFO -- : Writing /tmp/build_943fc98459748fd57245b7180732f530/public/assets/application-58b5e1ef277621d3e652de1322a4bb2db58836aad219b062b7d992c124249e5d.css
remote:        I, [2019-05-28T13:08:34.538543 #1497]  INFO -- : Writing /tmp/build_943fc98459748fd57245b7180732f530/public/assets/application-58b5e1ef277621d3e652de1322a4bb2db58836aad219b062b7d992c124249e5d.css.gz
remote:        I, [2019-05-28T13:08:34.538986 #1497]  INFO -- : Writing /tmp/build_943fc98459748fd57245b7180732f530/public/assets/bootstrap/glyphicons-halflings-regular-13634da87d9e23f8c3ed9108ce1724d183a39ad072e73e1b3d8cbf646d2d0407.eot
remote:        I, [2019-05-28T13:08:34.539259 #1497]  INFO -- : Writing /tmp/build_943fc98459748fd57245b7180732f530/public/assets/bootstrap/glyphicons-halflings-regular-13634da87d9e23f8c3ed9108ce1724d183a39ad072e73e1b3d8cbf646d2d0407.eot.gz
remote:        I, [2019-05-28T13:08:34.539739 #1497]  INFO -- : Writing /tmp/build_943fc98459748fd57245b7180732f530/public/assets/bootstrap/glyphicons-halflings-regular-fe185d11a49676890d47bb783312a0cda5a44c4039214094e7957b4c040ef11c.woff2
remote:        I, [2019-05-28T13:08:34.540299 #1497]  INFO -- : Writing /tmp/build_943fc98459748fd57245b7180732f530/public/assets/bootstrap/glyphicons-halflings-regular-a26394f7ede100ca118eff2eda08596275a9839b959c226e15439557a5a80742.woff
remote:        I, [2019-05-28T13:08:34.543764 #1497]  INFO -- : Writing /tmp/build_943fc98459748fd57245b7180732f530/public/assets/bootstrap/glyphicons-halflings-regular-e395044093757d82afcb138957d06a1ea9361bdcf0b442d06a18a8051af57456.ttf
remote:        I, [2019-05-28T13:08:34.544615 #1497]  INFO -- : Writing /tmp/build_943fc98459748fd57245b7180732f530/public/assets/bootstrap/glyphicons-halflings-regular-e395044093757d82afcb138957d06a1ea9361bdcf0b442d06a18a8051af57456.ttf.gz
remote:        I, [2019-05-28T13:08:34.545019 #1497]  INFO -- : Writing /tmp/build_943fc98459748fd57245b7180732f530/public/assets/bootstrap/glyphicons-halflings-regular-42f60659d265c1a3c30f9fa42abcbb56bd4a53af4d83d316d6dd7a36903c43e5.svg
remote:        I, [2019-05-28T13:08:34.548705 #1497]  INFO -- : Writing /tmp/build_943fc98459748fd57245b7180732f530/public/assets/bootstrap/glyphicons-halflings-regular-42f60659d265c1a3c30f9fa42abcbb56bd4a53af4d83d316d6dd7a36903c43e5.svg.gz
remote:        Asset precompilation completed (12.54s)
remote:        Cleaning assets
remote:        Running: rake assets:clean
remote: -----> Detecting rails configuration
remote: 
remote: ###### WARNING:
remote: 
remote:        You have not declared a Ruby version in your Gemfile.
remote:        To set your Ruby version add this line to your Gemfile:
remote:        ruby '2.5.3'
remote:        # See https://devcenter.heroku.com/articles/ruby-versions for more information.
remote: 
remote: ###### WARNING:
remote: 
remote:        Detecting rails configuration failed
remote:        set HEROKU_DEBUG_RAILS_RUNNER=1 to debug
remote: 
remote: ###### WARNING:
remote: 
remote:        No Procfile detected, using the default web server.
remote:        We recommend explicitly declaring how to boot your server process via a Procfile.
remote:        https://devcenter.heroku.com/articles/ruby-default-web-server
remote: 
remote: 
remote: -----> Discovering process types
remote:        Procfile declares types     -> (none)
remote:        Default types for buildpack -> console, rake, web
remote: 
remote: -----> Compressing...
remote:        Done: 36.6M
remote: -----> Launching...
remote:        Released v6
remote:        https://shielded-bastion-59596.herokuapp.com/ deployed to Heroku
remote: 
remote: Verifying deploy... done.
To https://git.heroku.com/shielded-bastion-59596.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from heroku.
