# DeathStarAdmin

This repository contains an intentionally vulnerable web app in PHP that students will have to find and correct.

The web app scenario is an administration page for the Star Wars Death Star.

The project is written in PHP and it is tested on PHP version `7.2`. It does not depend on any external libraries.

# Functionalities

## Authentication
User has to log in in order to access the platform. System has 2 permission rights:

- user
- admin

Only user with administrator right can destroy a planet.

## Planet Search
Using a form to search for planet by name. The system returns planet coordinator.

## Navigation
Move Dearth Star to a selected planet.

## Planet Destruction
Launch a destruction of a planet. This requires administrator permission.

## Stormtrooper Management
(N/A)

## User Management
This allow administrator to do CRUD on user.

# Deployment

## Using docker

- build image using docker compose `docker-compose build`
- to run it, `docker-compose up` or `docker-compose up -d` as in background
- point your browser to `http://localhost:8080`

## Using apache or nginx

Make sure web server point to the root folder of the project folder `app`