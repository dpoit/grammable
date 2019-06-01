# Grammable

An Instagram clone that was built using industry-standard, test-driven development following numerous red/green/refactor cycles.

## URL

[https://grammable-danny-poit.herokuapp.com/](https://grammable-danny-poit.herokuapp.com/)

## Users

Use the 'Sign up' and 'Sign in' links at the top right to create a user and log into it.

<img src="https://i.imgur.com/npVu622.png" alt="Sign up and Sign in links" width="500"/>

Creating a user will allow you to create new posts (called "grams"), edit your existing grams, and comment on grams. Once you are signed in, you will see a greeting with your login at the top of the page. Grams will display on the page sorted by the date they were posted.

## Create a gram

To create a gram, click 'New Gram' from the top right.

<img src="https://i.imgur.com/BhBF9L6.png" alt="New Gram link" width="500"/>

Then, enter a message and choose the image file you want to upload, then click 'Post!'

<img src="https://i.imgur.com/RyArM91.png" alt="New Gram page" width="500"/>

For grams you have created, you will also see 'Edit' and 'Delete' links that will allow you to manage your grams.

## Comments

To add a comment to a gram, scroll to the box beneath the gram. Type your comment into the text field, then click 'Add Comment'.

<img src="https://i.imgur.com/SROH3SV.png" alt="Comments" width="500"/>

Your comment will be displayed, along with any other comments that have been added to that gram.

## RSpec

This application has been developed with Test-Driven Development using RSpec. To run all tests, once you have cloned the repository to your local environment and installed all gems, run the following command:

```ruby
bundle exec rspec
```

## Tech used

* [Rails](https://rubyonrails.org/) (5.0.7.2)
* [RSpec](https://rspec.info/) (3.8.2)
* [Bootstrap](https://getbootstrap.com/) (4.3.1)
* [simple_form](https://github.com/plataformatec/simple_form) (4.1.0)
* [Devise](https://github.com/plataformatec/devise) (4.6.2)
* [CarrierWave](https://github.com/carrierwaveuploader/carrierwave) (1.3.1)
* [Figaro](https://github.com/laserlemon/figaro) (1.1.1)
* [AWS](https://aws.amazon.com/)/[fog-aws](https://github.com/fog/fog-aws) (3.4.0)

## Authors

* **[Danny Poit](https://github.com/dpoit)**

## Acknowledgments

* [The Firehose Project](http://thefirehoseproject.com/)
