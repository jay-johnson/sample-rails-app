## Sample Vanilla Rails Application with Travis CI

[![Travis](https://travis-ci.org/jay-johnson/sample-rails-app.svg)](https://travis-ci.org/jay-johnson/sample-rails-app.svg)

### Install

Make sure your environment has these components:

```
$ rails -v
Rails 4.2.4
$ ruby -v
ruby 2.2.3p173 (2015-08-18 revision 51636) [x86_64-linux]
$ 
```

### How to run

rails server

### View the App

Open a browser for:

http://localhost:3000/welcome/index

### Running the Hello World Rake Test:
bundle exec rake test TEST=test/controllers/hello_world_test.rb

