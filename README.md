# Portal del Equipo - Angular y Docker

## Descripción
Aplicación web desarrollada con Angular que integra las páginas personales de los integrantes del equipo. La aplicación se compila y se sirve mediante Nginx utilizando Docker.

## Integrantes
- Amir González
- Juan
- Karen
- Lizeth
- Zabdiel

## Tecnologías utilizadas
- Angular
- Node.js y npm
- Docker
- Docker Compose
- Nginx

## Ejecución del proyecto

Construir y levantar el contenedor:

```bash
docker compose up -d --build
```

Abrir en el navegador:

http://localhost:8080/

## Detener el contenedor

```bash
docker compose down
```

## Exportar la imagen Docker

```bash
docker save -o equipo-angular.tar mi-practica-angular-angular-app
```

## Importar la imagen Docker

```bash
docker load -i equipo-angular.tar
```

## Puerto utilizado
- Host: 8080
- Contenedor: 80
