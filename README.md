# Install Bootstrap To Rails 5 Project


## Getting Started

note: don't forget to add rails jquery gem below after you create new app

```
gem "jquery-rails"
```
add this line to application.js on the top of the require rails-ujs
```
//= require jquery
```

then ``` bundle install ``` 

1. Add Gem To Gemfile.file
```
gem 'bootstrap', '~> 4.0.0.alpha6'
gem 'rails-assets-tether', '>= 1.3.3', source: 'https://rails-assets.org'
```
then ``` bundle install ``` 
2. change application.css to application.scss and then add this line to application.scss
```
@import "bootstrap";
@import "sticky-footer";
@import "announcements";
```
3. and then add this line to application.js
```
//= require tether
//= require bootstrap
```
