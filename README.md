# Ruby On Rails 7 Devise Demo Api Authentication with JWT

This is a simple API Ruby on Rails devise and JWT Auth API

This tutorial has been based [this here](https://enlear.academy/how-to-create-a-rails-6-api-with-devise-jwt-46fa35085e85) I put some modifications, but did you can change for yours works! Enjoe!

## Requirement gems:

- devise
- figaro
- devise-jwt
- rake-cors

## Step 1. Creating rails app

```sh
rails new app-name-here --database=postgresql --api -T
cd app-name-here
```
## Step 2. Install Cors


*Create a file in ```config/initialize/cors.rb```*

```ruby
Rails.application.config.middleware.insert_before 0, Rack::Cors do
  allow do
    origins '*'

    resource '*',
      headers: :any,
      methods: [:get, :post, :put, :patch, :delete, :options, :head]
  end
end
```


# This README is DEVELOPMENT

### Please keep me a touch if you that see this tutorial.

Marvio Rocha - [marviorocha@marviorocha.com](mailto:marviorocha.com)

