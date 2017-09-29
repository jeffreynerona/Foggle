# Foggle

[![status|abandoned](http://jeffreynerona.com/badges/status-abandoned.svg)](http://jeffreynerona.com/projects) [![type|practice-project](http://jeffreynerona.com/badges/type-practiceproject.svg)](http://jeffreynerona.com/projects/) [![language|ruby](http://jeffreynerona.com/badges/language-ruby.svg)](http://jeffreynerona.com/projects/ruby)  [![type|practice-project](http://jeffreynerona.com/badges/technology-rubyonrails.svg)](http://jeffreynerona.com/projects/)

An Airbnb clone made with Ruby on Rails 
( Abandoning this to do it in React with RoR )
![jeffreynerona|Foggle](https://raw.githubusercontent.com/jeffreynerona/Foggle/master/screenshot/foggle.png)

# Features

  - Login and Register
  - Login with Facebook or Google Plus
  - Create, View, Update, and Delete Properties
  - Create Reservations
  - Image Upload

# Gems Used

  - paperclip (Image upload)
  - bootstrap-sass (Frontend Design)
  - sass-rails (Frontend Design)
  - toastr-rails (Notifications)
  - devise (Authentication)
  - omniauth (Authentication)
  - omniauth-facebook (Authentication)
  - omniauth-oauth2 (Authentication)
  - omniauth-google-oauth2 (Authentication)
  - font-awesome-sass (Icons)
  - geocoder (Map coordinates)

# Installation
Make a project folder then open it:
```sh
$ mkdir Foggle && cd Foggle
```

Clone Repository:
```sh
$ git clone git@github.com:jeffreynerona/Foggle.git
```

Install dependencies:
```sh
$ bundle install
```

Migrate Database:
```sh
$ rake db:migrate
```

Run the server:
```sh
$ rails s
```

