About:
This app is currently under very active development.  All of this is subject to change at any time.

Getting the app setup:
If you already have the application running on your machine, and you want to start over from scratch then run:
rake wus:demolish

If you are setting up the app for the first time or you just demolished your database then run:
rake wus:create

Now you can create all of your tables and columns by running:
rake db:migrate

Finally, setup the admin user and role:
rake wus:setup

So basically if you're brand new to the application then paste this into the terminal window:
rake wus:create
rake db:migrate
rake wus:setup

If you want to start over from scratch then do this:
rake wus:demolish
rake wus:create
rake db:migrate
rake wus:setup

If you've got a good working app and just wanna get up to date with the latest set of migrations then you can simply do:
rake db:migrate
