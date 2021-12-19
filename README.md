# Docker-Django Container

## Project goal

I wanted a bootstrap project for my contractor & personal work with the Django-Framework. 
This configuration can be easily use in any of the major cloud providers like AWS, DO or Azure. 

## Static Files

* Uses Nginx as a reverse proxy and whitenoise for static files 

## Usage

### Production

* Just set up your .env file following env-example
* docker-compose up

### Development

* You can run the project locally, and use the composer dev file to launch a Postgres instance
* Check the docker-compose dev file and env variables. Everything is pretty much self-explanatory

## License

* [Omar Gonzalez](https://omar-gonzalez.github.io/dev/) &copy; 2019 - Code released under the MIT license.
