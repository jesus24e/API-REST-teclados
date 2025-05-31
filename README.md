# API REST - Teclados

Proyecto final de Ingeniería de Software: API REST básica con Docker.

## Estructura del proyecto

El proyecto consta de dos elementos principales:

- Codigo fuente del proyecto

- Archivo `docker-compose.yml`

En el código fuente de la API REST se incluye:
- Entidades
- Repositorios
- Controladores
- Excepciones
- Servicios

El archivo `docker-compose.yml` junto al `dockerfile` permiten levantar el proyecto mediante Docker.

### Cómo levantar el proyecto en docker

- clone el repositorio:

	```git clone https://github.com/jesus24e/teclados-api.git proyectoapiteclados```

- levante los contenedores en docker desde la carpeta del proyecto

	```docker compose up```

- acceda al api rest

	```http://localhost:8081/api/v1/teclados/```

### pruebas de funcionalidad del api-rest con postman:

- `GET http://localhost:8081/api/v1/teclados/` – Obtener todos los teclados

- `GET http://localhost:8081/api/v1/teclados/1` – Obtener teclado por ID

- `POST http://localhost:8081/api/v1/teclados/` – Crear nuevo teclado

- `PUT http://localhost:8081/api/v1/teclados/1` – editar teclado

- `PATCH http://localhost:8081/api/v1/teclados/1` – Actualización parcial

- `DELETE http://localhost:8081/api/v1/teclados/1` – Eliminar teclado
