# Frais

Foodies and talented chefs rejoice! This fresh, stylish full-stack Rails application crowdsources and displays the top voted recipes from users, who can log in, create a profile and submit entries to win a place in the opening night menu of local vegetarian restaurant, Frais.  

<img src="app/assets/images/FraisHomepage.png" width="440" height="300" /> <img src="app/assets/images/FraisUserProfile.png" width="440" height="300" />

Recipes can be viewed, upvoted/downvoted by the community and users can view as well as submit recipes to specific course categories. Users can also search throughout the site for recipes by category, recipe name or ingredient.  

<img src="app/assets/images/FraisCategory.png" width="440" height="300" /> <img src="app/assets/images/FraisDish.png" width="440" height="300" /> 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

```
ruby 2.3.1
bundler 1.12.5
rails 5.0.0
```

### Installing
From the command terminal, clone the repository to your local directory...
```
$ git clone https://www.gihub.com/izzydoesit/Frais.git
$ cd Frais
```

Then run bundle command to install all dependencies and run the server.  

```
$ bundle install
$ rails server
```


## Running ALL the tests

```
bundle exec rspec spec
```

## Deployment

You must have Heroku CLI installed and be logged in to Heroku in order to deploy live via Heroku servers
(Please see the [documentation](https://devcenter.heroku.com) to get set up with Heroku)

Then after installation and login, via the command line
```
$ heroku create
$ git push heroku master
$ heroku open
```

## Built With

* [Ruby on Rails](http://api.rubyonrails.org/) -  Framework used
* [Devise](https://github.com/plataformatec/devise) - Authentication solution used
* [PostgreSQL](https://www.postgresql.org/docs/) - Database used

## Authors

* **Israel Matos** - [Github](https://github.com/everysum1)
* **Youna Yang** - [Github](https://github.com/y0una)
* **Hakim Joseph** - [Github](https://github.com/HakimJoseph)
* **Kim Stephenson** - [Github](https://github.com/kimstephenson)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

Thank you for all your help!!
* Ken Rettberg
* Jenny Engard
