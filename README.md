What's For Lunch at Springbot?
==============================

We at Springbot don't know where to eat lunch. Please build us a Ruby on Rails
app that will help us!

## Requirements
* We need a way to add new restaurants to our app's database
* We need to be able to give each restaurant an overall rating on a scale
   of 1-5, with 1 being the lowest and 5 the highest.
* We need to be able to mark the last time we have visited the restaurant
* When we visit the root url of the app, we want to be told what restaurant we
   should go to today. That restaurant should be chosen based on a combination
   of how much we like the restaurant and the last time we have been there. It
   is up to you to decide how that's going to happen, but I never want to be told
   to go to the same restaurant two days in a row unless there is only one
   restaurant in the system.
* You should build the frontend with a library of your choice. Feel free to use
   third party packages when it simplifies your problem and aids the problem.
* It needs a well structured UI/UX. No need to worry about the CSS aesthetic but
   it should be obvious as to what elements do what.
* As an admin, I want to be able to move the operating day forward and back so
    we can easily check date logic without using a console.

## Extra Stuff:
* Bonus points if you send us a link to your app, live on Heroku (https://devcenter.heroku.com/articles/getting-started-with-ruby#introduction)
* You can code the app with a single user in mind, but even more bonus points if you
  write multi-user support in so that different people can rate restaurants.
  If you choose to do this please use the average rating for a restaurant
  when picking where we eat today. Fair is fair.

  *PLEASE* do not spend a lot of time with user authentication. All we care about
  is how you'd structure the model relationships.

## Evaluation:
We will be checking your app for functionality, code readability, and presence of (but not necessarily quality of) tests.
