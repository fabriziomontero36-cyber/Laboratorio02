# Laboratorio02

Hoy utilizaremos docker compose para poder desplegar un servicio web y una base de datos

STACK Tecnico

API
    - Aplicacion JAVA dockerizarla (crear la imagen)
     - docker pull nmatsui/hello-world-api
     -peaceful_darwin 3001
     -compassionate_chandrasekhar 3000
     -docker run -d --rm -p 3000:3000 nmatsui/hello-world-api

BD PostgreSQL
docker run --name some-postgres -e POSTGRES_PASSWORD=mysecretpassword -d postgres


COMANDOS
-git clone https://github.com/nmatsui/hello-world-api.git api01
-docker compose up

-------
debugging básico de docker:
-docker exec -ti  peaceful_darwin /bin/sh
-apk
-netstat -tuln | grep :3000

lanza petición:
-curl.exe -i http://localhost:3000/
CONFIGURACIONES