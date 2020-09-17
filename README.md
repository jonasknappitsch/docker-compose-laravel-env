# docker-compose-laravel-env

## prerequisites
sudo apt install composer

## setup
Get a perfectly set-up laravel environment by simply cloning this repo, navigating into the folder with
```
cd docker-compose-laravel-env
```
and running
```
composer create-project laravel/laravel src/
```
in order to initialize your fresh new laravel project.

Now, as everything is set up, run your docker container (including NGINX, MySQL, PHP) with just one command:
```
docker-compose up
```

Your laravel application should now be running on **localhost:80**.

Once you're finished, simply shut everything down with `docker-compose down`.

