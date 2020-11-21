Installation
-------------
To build project and start development on host machine must be installed Linux (recommended) or MacOS and some required software:
latest version of `Docker (version 19.03.0+)` [https://docs.docker.com/install/] 
and `docker-compose` [https://docs.docker.com/compose/compose-file/], 
`Git`, `Java 10+` (to run Gradle tasks) and `PHP 7.4+`.  

You should run commands below to install application correctly:

        ./gradlew build
        
Next you can check services status:

        docker-compose ps

Default port mapping (see `.env` file):

        http://127.0.0.1:8085 - App
        http://127.0.0.1:8086 - phpMyAdmin