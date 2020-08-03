# README

Things I've learnt while building this project:

- Installing Rails
- Troubleshooting build errors
- Needed to install Yarn onto my computer
- Run 'rails webpacker:install'
- Bundle Install
- To Start Server: rails s
- rubygems.org
- Look up bundle exec
- Generate a controller: rails g controller [NAME]
- --help for help
- Models are singular, Controllers are plural
- Markdown writing

1) Made posts controller 

`mohammadali@MacBook-Pro my_blog % rails g controller posts`

`The dependency tzinfo-data (>= 0) will be unused by any of the platforms Bundler is installing for. Bundler is installing for ruby but the dependency is only for x86-mingw32, x86-mswin32, x64-mingw32, java. To add those platforms to the bundle, run 'bundle lock --add-platform x86-mingw32 x86-mswin32 x64-mingw32 java.`

`Running via Spring preloader in process 19485`
> create  app/controllers/posts_controller.rb
> invoke  erb
> create    app/views/posts
> invoke  test_unit
> create    test/controllers/posts_controller_test.rb
> invoke  helper
> create    app/helpers/posts_helper.rb
> invoke    test_unit
> invoke  assets
> invoke    scss
> create      app/assets/stylesheets/posts.scss


This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
