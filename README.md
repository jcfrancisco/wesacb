# wesacb-api

## Local dev
1. Install deps

        bundle install
2. Install foreman

        gem install foreman
3. Run foreman

        foreman start

## Deploying
0. (Do this only once) Add the Heroku git remote

        heroku git:remote -a wesacb

1. Deploy to Heroku

        git push heroku master
