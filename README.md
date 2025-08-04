# agenciaInmobiliaria



instalacion :

1. Tener node.js instalado
2. crear el package.json
3. instalar dependencia de npm (npm install) json-server

Probar Json server
    - instala for fake api
    npm install -g json-server

Ejecutar 
    json-server --watch houses.json# DragonBallAPI














como instsalar
1 clone el repositorio
2. tener docker instalado (docker desktop)    
3. ejecutar imagen dockefile
   docker build -t web-api-dragonball .
4. ejecutar el contendor
   docker run -d -p 80:80 web-api-dragonball
# DragonBallAPI

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

#### Subir la imagen a Docker Hub

1. Inicia sesión en Docker Hub:
   ```
   docker login
   ```
2. Etiqueta la imagen con tu usuario de Docker Hub:
   ```
   docker tag web-api-dragonball TU_USUARIO/web-api-dragonball:latest
   ```
3. Sube la imagen al repositorio:
   ```
   docker push TU_USUARIO/web-api-dragonball:latest
   ```
Reemplaza `TU_USUARIO` por tu nombre de usuario en Docker Hub.

### Opción 2: Uso local con Node.js

1. Tener Node.js instalado.
2. Instala las dependencias:
   ```
   npm install
   ```
3. Abre `index.html` en tu navegador para ver la aplicación.

## Créditos

Desarrollado por Jose Miguel Quesada.