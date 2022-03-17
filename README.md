# Flask

Docker - Flask (Python) - Redis

## Docker

- Para la primera vez que se levanta el proyecto con docker o se cambie los archivos de docker, ejecutar:
 
```bash
sudo docker-compose up --build -d
```

- En las siguientes oportunidades ejecutar:

Para levantar:
```bash
sudo docker-compose start
```
Para detener:
```bash
sudo docker-compose stop
```

- Para ingresar al server con docker ejecutar:
```bash
docker-compose exec server sh
```

- Para ver la web, en un navegador colocar la siguiente url:
```bash
http://localhost:8008
```