# docker-compose-laravel
A pretty simplified Docker Compose workflow that sets up a LEMP network of containers for local Laravel development.


## Usage

To get started, make sure you have docker and docker-compose on your system, and then clone this repository.

Next, navigate in your terminal to the directory you cloned this, and spin up the containers for the web server by running `mkdir src && docker-compose up -d --build site`.

After that completes, create a new blank laravel project by running `docker-compose run --rm composer create-project laravel/laravel .`

Finally, just visit `localhost` on your browser and check that your laravel app is up and running.

You can read more info about all the available exposed commands on this project by heading over to [EXTRA.md](EXTRA.md)
