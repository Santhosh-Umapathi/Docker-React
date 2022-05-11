![image](https://wallpaperaccess.com/full/2982327.jpg)

# Docker React

Basic React Js Application with Docker

# Live

- http://dockerreact-env.eba-n9m2kmcp.eu-south-1.elasticbeanstalk.com/
- http://dockerreact-env.eba-64j8veny.eu-central-1.elasticbeanstalk.com/

## Features

- Docker Compose - Dev, Prod
- Docker File - Dev, Prod
- CI/CD - GitHub Actions, Travis CI
- AWS - Beanstalk Hosting for Single Container
- nginX Server for Production
- Deploy only from master branch
- Multiple - Stages, Containers
- Automatic changes from Local to Container (Volumes)

## Instructions

- Github Actions - Add the secrets into Github Repo -> Settings -> Secrets -> Actions -> New Repository Secret (Add key/value pairs)
- Travis CI - Add the secrets into Travis Github Repo -> More Options -> Settings -> Environment Variables (Add key/value pairs)
- AWS - Create new Elastic Bean Stalk application, Create IAM user for Github Actions/Travis CI
- AWS - Copy all the required fields
