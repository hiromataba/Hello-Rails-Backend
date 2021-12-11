# Hello-Rails-Backend

![Microverse](https://img.shields.io/badge/Microverse-blueviolet)

> A two repo approach using rails and react

## Frontend Application PR

[GitHub PR](https://github.com/hiromataba/hello-rails-front-end/pull/1)

## Built With

- Ruby on Rails
- PostgreSQL

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

- [Ruby](https://www.ruby-lang.org/en/)
- [Rails](https://gorails.com/)

### Setup

- Make sure you have Ruby on Rails set up properly on your computer
- Clone or download this repo on your machine
- Enter project directory

### Install

```sh
bundle install
```

### Database

```sh
# Create user
sudo -u postgres createuser hello_rails_backend -s

# Create the database
rails db:create

## Apply migration
rails db:migrate

# Seed database with 5 greetings
rails db:seed
```

### Run

```sh
rails s
```

### Troubleshoot

```sh
### Undo migration
rake db:migrate VERSION=0
```
👤 **Aganze Mataba Henri**

- GitHub: [@hiromataba](https://github.com/hiromataba)
- Twitter: [@twitterhandle](https://twitter.com/MatabaHiro)
- LinkedIn: [Hiro Mataba](https://www.linkedin.com/in/hiro-mataba-1bb910)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Microverse

## 📝 License

This project is [MIT](./LICENSE.md) licensed.