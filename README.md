## Rails-Cable-Redux

This is a basic example chatroom base on [ActionCable](https://github.com/rails/rails/tree/master/actioncable]) 
which in coming with Rails5. Combined with the [Redux](https://github.com/rackt/redux) 
implementation of [Flux](https://facebook.github.io/flux/) - and of course 
[React](https://facebook.github.io/react/) components - there's potential here for an interesting stack 
if you don't want to create a separate front-end app and use Rails5 as an API server.

Things you may want to cover:

* Ruby version `2.3.0`

* Rails version `5.0.0beta1`

* System dependencies `Redis`

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

### Getting Started

Install gem dependencies.

```bash
$ cd rails-cable-redux
$ bundle install
```

Database creation

```bash
$ rails db:migrate
```

Start redis (depend on your redis client)

```bash
$ redis start
```

Then start rails server

```bash
$ rails server
```

### Usage
Open your browser at `localhost:3000` and enjoy chatting...
