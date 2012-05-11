## Using nginx server under Heroku

This is a template application for [Heroku nginx buildpack](https://github.com/essh/heroku-buildpack-nginx)

### Usage
```
git clone git://github.com/guilleiguaran/heroku-nginx-template.git
mv heroku-nginx-template your-app
cd your-app
heroku create your-app --stack cedar --buildpack http://github.com/essh/heroku-buildpack-nginx.git
git add .
git commit -m "Initial commit"
git push heroku master
```
