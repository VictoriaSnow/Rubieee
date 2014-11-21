Ruby-on-Rails
=============

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

Ruby on Rails
-------------

This application requires:

- Ruby 2.1.4
- Rails 4.1.7


To clone this repo (run ```git clone git@github.com:VictoriaSnow/Ruby-on-Rails.git```) in your terminal. Cd into the directory, run ```bundle install --without production``` and migrate your database, then start your server. (If you have trouble running the bundle install, try running ```rvm use 2.1.4``` in your terminal first).

Please make sure you consistently keep your repo up to date by running ```git pull origin master```.  You can try ```bundle install --without production``` if there's a pg gem issue. Run ```rake db:migrate``` if there's a pending migration error.

Note that the posts are not pre-generated. You need to sign up for an account and post for the pins to show on the index page.