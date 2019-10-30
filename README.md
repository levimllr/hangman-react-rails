# hangman-react-rails

Classic Hangman with a React frontend and Rails backend. 

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

## Rails 🚂

Generated with:

```ruby
rails new hangman --api -T --database=postgresql
```

## React 🧫

This React project is structured by file type.

## Troubleshooting

Since both the React client and the Rails server locally run on port 3000, I suggest doing one of the following:

  1. `rails server -p <some_number_other_than_3000>
  2. Refer to [this create-react-app Github issue](https://github.com/facebook/create-react-app/issues/1083).
