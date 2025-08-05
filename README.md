# Web API Dragon Ball

Aplicación web que muestra personajes de Dragon Ball utilizando una API externa.

## Estructura del proyecto

```
.
├── css/
│   └── index.css
├── js/
│   └── index.js
├── index.html
├── dockerfile
├── package.json
└── README.md
```
como instalar
1. clone el repositorio
2. tener docker instalado (docker desktop)    
3. Crear imagen dockefile
   docker build -t web-api-dragonball .
4. ejecutar el contendor
   docker run -d -p 80:80 web-api-dragonball
# DragonBallAPI

Aplicación web que muestra personajes de Dragon Ball utilizando una API externa.


## Instalación y uso

### Opción 1: Usar Docker

1. Clona el repositorio.
2. Asegúrate de tener Docker instalado (por ejemplo, Docker Desktop).
3. Construye la imagen Docker:
   ```
   docker build -t web-api-dragonball .
   ```
4. Ejecuta el contenedor:
   ```
   docker run -d -p 80:80 web-api-dragonball
   ```
5. Accede a la aplicación en [http://localhost](http://localhost).

#### Imagen existente en Docker Hub

1. Bajar el contenedor desde Docker Hub:
   ```
   docker pull jmgranabuab74/web-api-dragonball:latest
   ```
2. Ejecuta el contenedor:
   ```
   docker run -d -p 80:80 web-api-dragonball
   ```


## Créditos

Desarrollado por JM

## Licencia

Este proyecto está licenciado bajo los términos de la licencia MIT. Consulta el archivo LICENSE para más información.