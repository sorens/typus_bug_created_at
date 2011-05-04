Create the initial rails application

    > rails new typus1

      create  
      create  README
      create  Rakefile
      create  config.ru
      create  .gitignore
      create  Gemfile
      create  app
      create  app/controllers/application_controller.rb
      create  app/helpers/application_helper.rb
      create  app/mailers
      create  app/models
      create  app/views/layouts/application.html.erb
      create  config
      create  config/routes.rb
      create  config/application.rb
      create  config/environment.rb
      create  config/environments
      create  config/environments/development.rb
      create  config/environments/production.rb
      create  config/environments/test.rb
      create  config/initializers
      create  config/initializers/backtrace_silencers.rb
      create  config/initializers/inflections.rb
      create  config/initializers/mime_types.rb
      create  config/initializers/secret_token.rb
      create  config/initializers/session_store.rb
      create  config/locales
      create  config/locales/en.yml
      create  config/boot.rb
      create  config/database.yml
      create  db
      create  db/seeds.rb
      create  doc
      create  doc/README_FOR_APP
      create  lib
      create  lib/tasks
      create  lib/tasks/.gitkeep
      create  log
      create  log/server.log
      create  log/production.log
      create  log/development.log
      create  log/test.log
      create  public
      create  public/404.html
      create  public/422.html
      create  public/500.html
      create  public/favicon.ico
      create  public/index.html
      create  public/robots.txt
      create  public/images
      create  public/images/rails.png
      create  public/stylesheets
      create  public/stylesheets/.gitkeep
      create  public/javascripts
      create  public/javascripts/application.js
      create  public/javascripts/controls.js
      create  public/javascripts/dragdrop.js
      create  public/javascripts/effects.js
      create  public/javascripts/prototype.js
      create  public/javascripts/rails.js
      create  script
      create  script/rails
      create  test
      create  test/fixtures
      create  test/functional
      create  test/integration
      create  test/performance/browsing_test.rb
      create  test/test_helper.rb
      create  test/unit
      create  tmp
      create  tmp/sessions
      create  tmp/sockets
      create  tmp/cache
      create  tmp/pids
      create  vendor/plugins
      create  vendor/plugins/.gitkeep
      
Change directory into the new rails app and run `bundle install`.     

    cd typus1

    > bundle install
    Updating git://github.com/fesplugas/typus.git
    Fetching source index for http://rubygems.org/
    Using rake (0.8.7) 
    Using abstract (1.0.0) 
    Using activesupport (3.0.5) 
    Using builder (2.1.2) 
    Using i18n (0.5.0) 
    Using activemodel (3.0.5) 
    Using erubis (2.6.6) 
    Using rack (1.2.2) 
    Using rack-mount (0.6.14) 
    Using rack-test (0.5.7) 
    Using tzinfo (0.3.25) 
    Using actionpack (3.0.5) 
    Using mime-types (1.16) 
    Using polyglot (0.3.1) 
    Using treetop (1.4.9) 
    Using mail (2.2.15) 
    Using actionmailer (3.0.5) 
    Using arel (2.0.9) 
    Using activerecord (3.0.5) 
    Using activeresource (3.0.5) 
    Using bcrypt-ruby (2.1.4) 
    Using bundler (1.0.10) 
    Using fastercsv (1.5.4) 
    Using thor (0.14.6) 
    Using railties (3.0.5) 
    Using rails (3.0.5) 
    Using render_inheritable (1.0.0) 
    Using sqlite3 (1.3.3) 
    Using will_paginate (3.0.pre2) 
    Using typus (3.0.10) from git://github.com/fesplugas/typus.git (at master) 
    Your bundle is complete! Use `bundle show [gemname]` to see where a bundled gem is installed.

Generate the typus files.

    > rails g typus
    
      create  config/initializers/typus.rb
      create  config/initializers/typus_resources.rb
       exist  public
      create  public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-bg_diagonals-thick_18_b81900_40x40.png
      create  public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-bg_diagonals-thick_20_666666_40x40.png
      create  public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-bg_flat_10_000000_40x100.png
      create  public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-bg_glass_100_f6f6f6_1x400.png
      create  public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-bg_glass_100_fdf5ce_1x400.png
      create  public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-bg_glass_65_ffffff_1x400.png
      create  public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-bg_gloss-wave_35_f6a828_500x100.png
      create  public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-bg_highlight-soft_100_eeeeee_1x100.png
      create  public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-bg_highlight-soft_75_ffe45c_1x100.png
      create  public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-icons_222222_256x240.png
      create  public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-icons_228ef1_256x240.png
      create  public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-icons_ef8c08_256x240.png
      create  public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-icons_ffd27a_256x240.png
      create  public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-icons_ffffff_256x240.png
      create  public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/jquery-ui-1.8.9.custom.css
      create  public/vendor/jquery-ui-1.8.9.custom/js/jquery-1.4.4.min.js
      create  public/vendor/jquery-ui-1.8.9.custom/js/jquery-ui-1.8.9.custom.min.js
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/blank.gif
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_close.png
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_loading.png
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_nav_left.png
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_nav_right.png
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_shadow_e.png
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_shadow_n.png
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_shadow_ne.png
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_shadow_nw.png
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_shadow_s.png
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_shadow_se.png
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_shadow_sw.png
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_shadow_w.png
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_title_left.png
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_title_main.png
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_title_over.png
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_title_right.png
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/fancybox-x.png
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/fancybox-y.png
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/fancybox.png
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/jquery.easing-1.3.pack.js
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/jquery.fancybox-1.3.4.css
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/jquery.fancybox-1.3.4.js
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/jquery.fancybox-1.3.4.pack.js
      create  public/vendor/jquery.fancybox-1.3.4/fancybox/jquery.mousewheel-3.0.4.pack.js
      create  public/vendor/typus/javascripts/application.js
      create  public/vendor/typus/javascripts/jquery.application.js
      create  public/vendor/typus/javascripts/jquery.rails.autocomplete.js
      create  public/vendor/typus/javascripts/jquery.rails.js
      create  public/vendor/typus/javascripts/jquery.searchField.js
      create  public/vendor/typus/stylesheets/application.css
      create  public/vendor/typus/stylesheets/reset.css
      create  public/vendor/typus/stylesheets/screen.css
      create  app/controllers/admin/foos_controller.rb
      invoke  test_unit
      create    test/functional/admin/foos_controller_test.rb
      create  config/typus/README
      create  config/typus/20110504161759_application.yml
      create  config/typus/20110504161759_application_roles.yml

Create a simple model with a field.

      > rails g model Foo bar:string
      
      invoke  active_record
      create    db/migrate/20110504161536_create_foos.rb
      create    app/models/foo.rb
      invoke    test_unit
      create      test/unit/foo_test.rb
      create      test/fixtures/foos.yml

Now, push it to git...

     > git init
    Initialized empty Git repository in typus1/.git/
    > git add .
    > git commit -m "first"
    [master (root-commit) 060bcb0] first
     102 files changed, 14415 insertions(+), 0 deletions(-)
     create mode 100644 .gitignore
     create mode 100644 Gemfile
     create mode 100644 Gemfile.lock
     create mode 100644 README
     create mode 100644 Rakefile
     create mode 100644 app/controllers/admin/foos_controller.rb
     create mode 100644 app/controllers/application_controller.rb
     create mode 100644 app/helpers/application_helper.rb
     create mode 100644 app/models/foo.rb
     create mode 100644 app/views/layouts/application.html.erb
     create mode 100644 config.ru
     create mode 100644 config/application.rb
     create mode 100644 config/boot.rb
     create mode 100644 config/database.yml
     create mode 100644 config/environment.rb
     create mode 100644 config/environments/development.rb
     create mode 100644 config/environments/production.rb
     create mode 100644 config/environments/test.rb
     create mode 100644 config/initializers/backtrace_silencers.rb
     create mode 100644 config/initializers/inflections.rb
     create mode 100644 config/initializers/mime_types.rb
     create mode 100644 config/initializers/secret_token.rb
     create mode 100644 config/initializers/session_store.rb
     create mode 100644 config/initializers/typus.rb
     create mode 100644 config/initializers/typus_resources.rb
     create mode 100644 config/locales/en.yml
     create mode 100644 config/routes.rb
     create mode 100644 config/typus/20110504161759_application.yml
     create mode 100644 config/typus/20110504161759_application_roles.yml
     create mode 100644 config/typus/README
     create mode 100644 db/migrate/20110504161536_create_foos.rb
     create mode 100644 db/schema.rb
     create mode 100644 db/seeds.rb
     create mode 100644 doc/README_FOR_APP
     create mode 100644 lib/tasks/.gitkeep
     create mode 100644 public/404.html
     create mode 100644 public/422.html
     create mode 100644 public/500.html
     create mode 100644 public/favicon.ico
     create mode 100644 public/images/rails.png
     create mode 100644 public/index.html
     create mode 100644 public/javascripts/application.js
     create mode 100644 public/javascripts/controls.js
     create mode 100644 public/javascripts/dragdrop.js
     create mode 100644 public/javascripts/effects.js
     create mode 100644 public/javascripts/prototype.js
     create mode 100644 public/javascripts/rails.js
     create mode 100644 public/robots.txt
     create mode 100644 public/stylesheets/.gitkeep
     create mode 100644 public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-bg_diagonals-thick_18_b81900_40x40.png
     create mode 100644 public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-bg_diagonals-thick_20_666666_40x40.png
     create mode 100644 public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-bg_flat_10_000000_40x100.png
     create mode 100644 public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-bg_glass_100_f6f6f6_1x400.png
     create mode 100644 public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-bg_glass_100_fdf5ce_1x400.png
     create mode 100644 public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-bg_glass_65_ffffff_1x400.png
     create mode 100644 public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-bg_gloss-wave_35_f6a828_500x100.png
     create mode 100644 public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-bg_highlight-soft_100_eeeeee_1x100.png
     create mode 100644 public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-bg_highlight-soft_75_ffe45c_1x100.png
     create mode 100644 public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-icons_222222_256x240.png
     create mode 100644 public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-icons_228ef1_256x240.png
     create mode 100644 public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-icons_ef8c08_256x240.png
     create mode 100644 public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-icons_ffd27a_256x240.png
     create mode 100644 public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/images/ui-icons_ffffff_256x240.png
     create mode 100644 public/vendor/jquery-ui-1.8.9.custom/css/ui-lightness/jquery-ui-1.8.9.custom.css
     create mode 100644 public/vendor/jquery-ui-1.8.9.custom/js/jquery-1.4.4.min.js
     create mode 100644 public/vendor/jquery-ui-1.8.9.custom/js/jquery-ui-1.8.9.custom.min.js
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/blank.gif
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_close.png
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_loading.png
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_nav_left.png
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_nav_right.png
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_shadow_e.png
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_shadow_n.png
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_shadow_ne.png
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_shadow_nw.png
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_shadow_s.png
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_shadow_se.png
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_shadow_sw.png
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_shadow_w.png
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_title_left.png
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_title_main.png
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_title_over.png
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/fancy_title_right.png
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/fancybox-x.png
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/fancybox-y.png
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/fancybox.png
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/jquery.easing-1.3.pack.js
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/jquery.fancybox-1.3.4.css
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/jquery.fancybox-1.3.4.js
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/jquery.fancybox-1.3.4.pack.js
     create mode 100644 public/vendor/jquery.fancybox-1.3.4/fancybox/jquery.mousewheel-3.0.4.pack.js
     create mode 100644 public/vendor/typus/javascripts/application.js
     create mode 100644 public/vendor/typus/javascripts/jquery.application.js
     create mode 100644 public/vendor/typus/javascripts/jquery.rails.autocomplete.js
     create mode 100644 public/vendor/typus/javascripts/jquery.rails.js
     create mode 100644 public/vendor/typus/javascripts/jquery.searchField.js
     create mode 100644 public/vendor/typus/stylesheets/application.css
     create mode 100644 public/vendor/typus/stylesheets/reset.css
     create mode 100644 public/vendor/typus/stylesheets/screen.css
     create mode 100755 script/rails
     create mode 100644 test/fixtures/foos.yml
     create mode 100644 test/functional/admin/foos_controller_test.rb
     create mode 100644 test/performance/browsing_test.rb
     create mode 100644 test/test_helper.rb
     create mode 100644 test/unit/foo_test.rb
     create mode 100644 vendor/plugins/.gitkeep

Setup a Heroku instance.

     > heroku create
     Creating morning-sky-193.... done
     http://morning-sky-193.heroku.com/ | git@heroku.com:morning-sky-193.git
     Git remote heroku added

Push it to heroku.

     > git push heroku master
    Counting objects: 144, done.
    Delta compression using up to 2 threads.
    Compressing objects: 100% (121/121), done.
    Writing objects: 100% (144/144), 249.30 KiB, done.
    Total 144 (delta 5), reused 0 (delta 0)

    -----> Heroku receiving push
    -----> Rails app detected
    -----> Detected Rails is not set to serve static_assets
           Installing rails3_serve_static_assets... done
    -----> Configure Rails 3 to disable x-sendfile
           Installing rails3_disable_x_sendfile... done
    -----> Configure Rails to log to stdout
           Installing rails_log_stdout... done
    -----> Gemfile detected, running Bundler version 1.0.7
           Unresolved dependencies detected; Installing...
           Using --without development:test
           Fetching source index for http://rubygems.org/
           Fetching git://github.com/fesplugas/typus.git
           Installing rake (0.8.7) 
           Installing abstract (1.0.0) 
           Installing activesupport (3.0.5) 
           Installing builder (2.1.2) 
           Installing i18n (0.5.0) 
           Installing activemodel (3.0.5) 
           Installing erubis (2.6.6) 
           Installing rack (1.2.2) 
           Installing rack-mount (0.6.14) 
           Installing rack-test (0.5.7) 
           Installing tzinfo (0.3.25) 
           Installing actionpack (3.0.5) 
           Installing mime-types (1.16) 
           Installing polyglot (0.3.1) 
           Installing treetop (1.4.9) 
           Installing mail (2.2.15) 
           Installing actionmailer (3.0.5) 
           Installing arel (2.0.9) 
           Installing activerecord (3.0.5) 
           Installing activeresource (3.0.5) 
           Installing bcrypt-ruby (2.1.4) with native extensions 
           Installing fastercsv (1.5.4) 
           Using bundler (1.0.7) 
           Installing thor (0.14.6) 
           Installing railties (3.0.5) 
           Installing rails (3.0.5) 
           Installing render_inheritable (1.0.0) 
           Installing sqlite3 (1.3.3) with native extensions 
           Installing will_paginate (3.0.pre2) 
           Using typus (3.0.10) from git://github.com/fesplugas/typus.git (at master) 
           Your bundle is complete! It was installed into ./.bundle/gems/
           Compiled slug size is 10.2MB
    -----> Launching... done
           http://morning-sky-193.heroku.com deployed to Heroku

           To git@heroku.com:morning-sky-193.git
           * [new branch]      master -> master
           
Once you create and startup the application on Heroku, you need to use Typus to create a new `foo`
and enter a string into the `bar` field. Once it's created, you can then use `heroku db:pull` to
bring the database down to your development environment
           
    heroku db:pull --confirm morning-sky-193
    Receiving schema
    Schema:        100% |==========================================| Time: 00:00:03
    Receiving indexes
    schema_migrat: 100% |==========================================| Time: 00:00:00
    Receiving data
    2 tables, 400 records
    schema_migrat: 100% |==========================================| Time: 00:00:00
    foos:          100% |==========================================| Time: 00:00:00
    Resetting sequences
    
Now, you can run `rails s` locally and go to http://0.0.0.0.:3000/admin/foo

    > rails s
    
    => Booting WEBrick
    => Rails 3.0.5 application starting in development on http://0.0.0.0:3000
    => Call with -d to detach
    => Ctrl-C to shutdown server
    [2011-05-04 09:25:17] INFO  WEBrick 1.3.1
    [2011-05-04 09:25:17] INFO  ruby 1.8.7 (2010-06-23) [i686-darwin10.4.0]
    [2011-05-04 09:25:17] INFO  WEBrick::HTTPServer#start: pid=30420 port=3000


    Started GET "/admin/foos" for 127.0.0.1 at Wed May 04 09:25:25 -0700 2011
      Processing by Admin::FoosController#index as HTML
      Foo Load (0.2ms)  SELECT "foos".* FROM "foos" LIMIT 15 OFFSET 0
    Rendered .rvm/gems/ruby-1.8.7-p299/bundler/gems/typus-a281aaeb4258/app/views/admin/helpers/sidebar/_sidebar.html.erb (1.3ms)
    Rendered .rvm/gems/ruby-1.8.7-p299/bundler/gems/typus-a281aaeb4258/app/views/admin/resources/_index.html.erb (0.3ms)
      SQL (0.2ms)  SELECT COUNT(*) FROM "foos"
      Foo Load (0.2ms)  SELECT "foos".* FROM "foos"
    Rendered .rvm/gems/ruby-1.8.7-p299/bundler/gems/typus-a281aaeb4258/app/views/admin/resources/index.html.erb within layouts/admin/base (21.8ms)
    Completed   in 58ms

    ActionView::Template::Error (undefined method `created_at' for #<ActiveRecord::Relation:0x103638c20>):
        22:   <% end %>
        23: </ul>
        24: 
        25: <% if (build_filters || search) %>
        26:   <div class="filters">
        27:     <%= build_filters %>
        28:     <%= search %>
  

    Rendered .rvm/gems/ruby-1.8.7-p299/gems/actionpack-3.0.5/lib/action_dispatch/middleware/templates/rescues/_trace.erb (1.5ms)
    Rendered .rvm/gems/ruby-1.8.7-p299/gems/actionpack-3.0.5/lib/action_dispatch/middleware/templates/rescues/_request_and_response.erb (7.6ms)
    Rendered .rvm/gems/ruby-1.8.7-p299/gems/actionpack-3.0.5/lib/action_dispatch/middleware/templates/rescues/template_error.erb within rescues/layout (31.5ms)
    
note: slightly edited to remove extraneous path info that make it less confusing (hopefully)

In case it is relevant, the heroku instance is at: http://morning-sky-193.heroku.com/admin/foos/