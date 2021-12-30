# Vector Deployment in Heroku

Simple way to deploy vector to heroku for use in logplex forwarding


## Setup

1. Fork this [starter repository](https://github.com/anglinb/heroku-logplex-vector-example/blob/main/README.md)
2. Make changes to your vector.toml 
3. Visit https://heroku.com/deploy?template=https://github.com/YOUR_USERNAME/heroku-logplex-vector-example
4. Once this is deployed on your heroku, simply add the heroku project as a drain 
  - `heroku drains:add https://<your-vector-heroku-app>.herokuapp.com/events?env=<env>&service=<service>&heroku_app_name=<source-app>`



