# README
This is a template app with User registration, login, authorization, and password reset.  It has styles that need wiping and redesign to suit whatever application that might need the backend features built.

To clone and set up with a new repo w new local and remote:
1. [https://help.github.com/articles/duplicating-a-repository/](https://help.github.com/articles/duplicating-a-repository/) - use Mirroring a repository.
2. git clone https://github.com/NEW_REPO_NAME_HERE/vitstack.git

# 🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤🖤

This app has no Heroku address.  When started, this is how it need to be pushed.
$ rails test
$ git push heroku
$ heroku pg:reset DATABASE
$ heroku run rails db:migrate
$ heroku run rails db:seed
$ heroku restart

Considerations:
1. SSL certificate for your domain - for now piggy back on Heroku's
2. Database migrations

##############################

rails 5.1.4
Ruby version 2.4.1

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
