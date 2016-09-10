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

to run the server on c9 (IP=0.0.0.0 PORT=8080)
```
$ rails server -b $IP -p $PORT
```

Setup heroku from c9
```
$ heroku login
$ heroku keys:add
$ heroku create
$ git push master heroku
$ heroku create
$
```