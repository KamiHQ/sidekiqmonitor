sidekiqmonitor
==============

Simple repo for deploying sidekiq's monitor standalone on heroku. If you're running on development, the default username and password is 'sidekiq'

To Deploy:

heroku create APP_NAME

heroku config:set REDIS_URL=XXXX SIDEKIQ_PASSWORD=the_password

git push heroku master

heroku open
