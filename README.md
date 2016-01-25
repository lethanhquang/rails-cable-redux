## README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version `2.3.0`

* Rails version `5.0.0beta1`

* System dependencies
- Redis

* Configuration

* Database creation
```bash
$ rails db:migrate
```

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
