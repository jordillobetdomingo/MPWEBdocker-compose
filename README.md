# Entrega Tema 4 de Entorno web de MPWEB

## Commands

# Spin up all services defined in docker-compose.yml:
$ docker-compose up -d

# Observe the services output in the logs. (Exit with Ctrl+C):
$ docker-compose logs -f

# Obtain a list of running containers
$ docker-compose ps

# Obtain a list of running processes
$ docker-compose top

# Once you're finished, stop all running services:
$ docker-compose down

# Resultados 
Para comprobar si funciona, acceder en el navegador "http://localhost:8085/php-status.php" y deberia salir la información de configuración del PHP
