# Vector Deployment in Heroku

Simple way to deploy vector to heroku for use in logplex forwarding


Once this is deployed on your heroku, simply add the heroku project as a drain 

`heroku drains:add https://<your-vector-heroku-app>.herokuapp.com/events?env=<env>&service=<service>&heroku_app_name=<source-app>`
