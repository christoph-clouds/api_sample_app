# API sample application

This is a sample application for learning about buidling APIs in Rails.

It is based on the sample application for the 4th edition of [*Ruby on Rails Tutorial: Learn Web Development with Rails*](http://www.railstutorial.org/) by [Michael Hartl](http://www.michaelhartl.com/) and on the [rails 5 api tutorial](https://github.com/vasilakisfil/rails5_api_tutorial) by Filippos Vasilakis


## License

This source code is available jointly under the MIT License and the Beerware License. See [LICENSE.md](LICENSE.md) for details.

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ cd ~/tmp
$ git clone https://github.com/backend-development/api_sample_app.git
$ cd api_sample_app
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Now you are ready to run the app in a local server:

```
$ rails server
```


## what to do?

Follow the explanation in the [API chapter of the backend-development book](https://backend-development.github.io/apis.html)

