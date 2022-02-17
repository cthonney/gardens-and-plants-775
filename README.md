

## Generate Rails App

+ `rails new -T gardens-and-plants && cd $_`


## Push to Github

+ `git add .`

+ `git commit -m "rails new"`

+ `gh repo create`
+ `git push origin master`

## Front-end
+ Follow front-end setup guidelines (https://github.com/lewagon/rails-stylesheets/blob/master/README.md)


## Scaffold gardens (Model, View, Controller)
  + `rails g scaffold gardens name banner_url`
  + (Open your Gemfile and comment out jbuilder before generating your scaffold)
  + `rails db:create`
  + `rails db:migrate`


## Banner
+ https://uikit.lewagon.com/documentation#banners


## Generate Plant Model
+ `rails g model Plant garden:references name image_url`
+ `rails db:migrate`

## Generate Plant Controller
  + rails g controller plants`

## If you want clone this app
  




