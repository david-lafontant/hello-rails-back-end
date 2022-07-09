# README

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


# Hello Rails Back End*

**Hello Rails Back End*  is an API. A GET request to its open end point return a random greeting message

* Ruby version : 3.12

# This project was built with

- Ruby on Rails

F# ront-End Pull request
[Front-End](https://github.com/david-lafontant/hello-react-front-end/pull/1)
# Getting Started

To get a local copy up and running follow these simple steps.

- You can clone this repo by typing `https://github.com/david-lafontant/hello-rails-back-end.git` on your terminal.

- Type `cd hello-rails-back-end` to access the project on the terminal.
- If your on windows please uncomment lines 61 and 62 in the `database.yml` file located in the config folder and follow the instructions. I f you're not on Windows, please skip this. 
  
- Run `bundle install` to install all the required dependencies.
- - Run `rails db:setup` or the following sequence:
- 
```
- rails db:drop
- rails db:create
- rails db:migrate
- rails db:seed  
  ```              
  it you run the App for the first you could skip `rails db:drop`

- Run `rails s` to start a development server.

## Errors

If you encounter any errors, run the following commands.

- Run `rails db:reset` to drop, create and migrate a new database.

- Run `rubocop && rubocop -A` to check for and fix code errors.




## Author

👤 **David Lafontant**

- GitHub: [@david-lafontant](https://github.com/david-lafontant)
- Twitter: [@manikatex](https://twitter.com/manikatex)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/david-lafontant)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/david-lafontant/hello-rails-back-end/issues).

## Show your support

Give a ⭐️ if you like this project!

## 📝 License

This project is [MIT](./LICENCE) licensed.