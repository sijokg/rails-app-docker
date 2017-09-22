# WHAT IS THIS?
A sample Rails application which is in one docker container and it connects to a postgres db which is in another container. 

#Pre-requisites
Install docker as well as docker-compose

## Steps
To run this, clone this repo, Then execute the following steps from the application root folder. Then open http://localhost:3000/fruits from browser.


        $ docker-compose build 

        $ docker-compose up
        
        $ docker-compose run web rake db:create
        
        $ docker-compose run web rake db:migrate
