# A simple Ruby on Rails application

## Getting started

To start clone the repo then install the needed gems

```
$ bundle install --without production
```

then migrate the database
```
$ rails db:migrate
```

run tests to make sure everything is setup
```
$ rails test
```

if the test suite passes, run the server
```
$ rails server
```

to run the server on c9
```
rails server -b 0.0.0.0 -p 8080
```