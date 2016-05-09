# README

0. Install the Docker toolbox ([instructions for OS X with brew](https://gist.github.com/jeromedalbert/7476f445b7538b488c6ec34b5c4f3da4))

0. Create the Docker images for our applicaiton:

        docker-compose build

0. Set up the database:

        docker-compose run app rake db:create

0. Run the application:

        docker-compose up

0. You can now access http://192.168.99.100 (or whatever your docker-machine IP is)

