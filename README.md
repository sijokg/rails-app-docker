# WHAT IS THIS?
A sample Rails CRUD application. 

# Pre-requisites
Install Ruby Version 2.4.1 and Postgresql

## Steps
To run this, clone this repo. Modify the config/database.yml file. Then execute the following steps from the application root folder. Finally open http://localhost:3000/fruits from browser.


        $ bundle exec rake db:create

        $ bundle exec rake db:migrate

        $ bundle exec rails s 
