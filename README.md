# Beautiful Beauty Backend
![](https://yoonmikim.github.io/images/beautiful_beauty.png)
![](https://yoonmikim.github.io/images/cart.png)
*A Makeup App where user can sign up, log in, log out, go to homepage with categories with images, emojis, and gifs, go to profile page, view products, filter/sort/search products based on user inputs. If user likes certain products, user can add to cart and/or go to product pages to purchase.

+ Created a Ruby on Rails API backend to parse data from a 3rd party API. (Seed data from a complex data set - external API)
+ Use of MVC, Serializers, ActiveRecord, and custom RESTful routes to optimize database and schema for backend functionality. (belongs_to / has_many / belongs_to / has_many_through relationships in model)
+ Validations (when signing up as a new user - username should be unique)
+ Interacting with a complex API
+ This beauty-BE repository goes with beauty-FE (https://github.com/yoonmikim/Beautiful-Beauty-Frontend)

### Installing and Running the App

A step by step series of examples that tell you how to get a development env running.
You will need to have cloned the backend repo and started the rails server on port 3000.
The frontend will run on port 3001 by default if you already have the backend server up and running.
To start the frontend:

```
$ git clone
$ cd [repo location]
$ cd beautiful-beauty-backend
$ bundle install
$ rails s
```
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Built With

* React.js (front-end)
* Ruby on Rails (back-end)
* Makeup API

## Author

* **Yoonmi Kim** 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).


