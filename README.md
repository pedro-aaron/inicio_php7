# inicio_php7
Docker settings for Apache-PHP7  and MariaDB

# Para correr el contenedor en docker (con LINUX CONTAINERS) en WINDOWS 10:
1. Crear una carpeta llamada www en raíz...ésta será la carpeta  pública
2. Modificar las variables de docker-compose.yml
      MYSQL_ROOT_PASSWORD: root
      MYSQL_DATABASE: db_name
      MYSQL_USER: db_user
      MYSQL_PASSWORD: db_pass
      
3. Abrir power shell
4. ir a la carpeta
  ej. cd c:/docker/inicio_php7
5. correr el contenedor
  docker-compose up

6. otras instrucciones
docker container ls
docker container stop IDXXXX
