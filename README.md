#  Docker for WordPress!

![Landing Page](cover.png)
  
A Docker stack ready to easily run the best ever CMS!

* Docker
* PHP
* MySQL
* phpMyAdmin
##  Installation
 
* Clone this repository on your local computer
* configure .env as needed 
* Run the `docker-compose up -d`.

```shell
git clone https://github.com/danilocgsilva/docker-php74-mysql-phpmyadmin-wp.git
cd docker-compose-lamp/
cp sample.env .env
// modify sample.env as needed
docker-compose up -d
// visit localhost
```

Your WordPress stack is now ready!! You can access it via `http://localhost`.

## Thanks to SprintCube

I have forked the [docker-compose-lamp](https://github.com/sprintcube/docker-compose-lamp) project from the [Sprintcube](https://github.com/sprintcube) repository to create this one. The heavy duty for the stack creation are entirely done the thoses guys. Thank you!
