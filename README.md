sidekiqmonitor
==============

Simple repo for deploying sidekiq's monitor standalone on heroku.

To Deploy:
heroku create APP_NAME
heroku config:set REDIS_URL=XXXX SIDEKIQ_PASSWORD=the_password
git push heroku master
heroku open
