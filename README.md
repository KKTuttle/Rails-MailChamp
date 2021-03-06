#  MailChamp
## *By Katarina Tuttle*

Web application that allow user to subscribe to a newsletter.

## Technologies Used

* **Application**: *Ruby on Rails 5*<br>
* **Database**: *Postgres, ActiveRecord*

Installation
------------

Install by cloning the repository.  
```
$ git clone https://github.com/KKTuttle/Rails-MailChamp
```

Check to make sure ruby and rails are installed on your machine.  
```
$ ruby -v
$ rails -v
```
If they are not installed, please follow instructions [here](http://guides.rubyonrails.org/getting_started.html#installing-rails) to install ruby on rails.

Install required gems:
```
$ bundle install
```

Run Postgres:
```
$ postgres
```

Navigate to project file and migrate database:
```
$ rake db: create
$ rake db: migrate
```

Start the Rails webserver:
```
$ rails server
```

Navigate to `localhost:3000` in your browser of choice.

## Support and contact details

_Contact by email: katka.karolcikova@gmail.com_
* Github: kktuttle
* https://github.com/KKTuttle/Rails-MailChamp

###  License

_This software is licensed under the MIT license._<br><br>
Copyright (c) 2016 **Katarina Tuttle**
