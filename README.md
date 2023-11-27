Project info:
* Ruby version 3.2.2
* Link to project description: https://www.theodinproject.com/lessons/ruby-on-rails-websockets-and-actioncable#streams

This is a rails app which allows users to:
* sign in 
* participate in a messenger chatroom

This app makes use of:
* websockets
* actioncable
* a turbolinks:load event listener

I hope to gain more familiarity with all of the above.

Misc terminal setup:
* rails new actioncable-messenger -T
* bundle add devise
* bundle exec rails generate devise:install
* bundle exec rails generate devise user && bundle exec rails db:migrate
* bundle exec rails db:seed (after adding users to the seeds.rb file)
* bundle exec rails generate controller hangouts index
* bundle add bulma-rails
* bundle exec rails generate channel message
* bundle exec rails generate model message body:string user:references
* bundle exec rails db:migrate
* bundle exec rails generate controller messages
