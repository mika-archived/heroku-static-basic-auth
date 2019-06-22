# heroku-static-basic-auth

Static website hosting with BASIC authentication using Heroku.

```bash
$ git clone https://github.com/mika-sandbox/heroku-static-basic-auth
$ heroku create heroku-static-basic-auth
$ heroku config:set APP_USERNAME=YOUR_USERNAME
$ heroku config:set APP_PASSWORD=YOUR_PASSWORD
$ git push heroku master
$ heroku open
```
