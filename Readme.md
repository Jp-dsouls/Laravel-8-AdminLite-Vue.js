# Laravel 8 + AdminLTE + Vue.js

## Comenzando

Sigue las siguientes instrucciones para clonar este repositorio en tu equipo de manera local y poder trabajar desde el principio con la plantilla AdminLTE en Laravel 8.


## Pre - Requisitos

Para clonar este repositorio, debes tener instalado un servidor Apache, PHP y MSQL (Wamp, Xampp, Laragon, Mamp o Lamp) y los generadores de dependencias para PHP (Composer) y para NodeJs (Npm).

```bash
  composer --version 
  composer -v
```

Verifica también la version de NPM en la terminal con

```bash
  npm --version
```

## Local

Clona el proyecto

```bash
  git clone https://github.com/Jp-dsouls/Laravel-8-AdminLite-Vue.js.git
```

Instale las dependencias

```bash
  composer install
```

Actualize las dependencias de Composer con

```bash
  composer update
```

Como el proyecto tiene dependencias en JS instalarlas con

```bash
  npm install
```

Actualize las dependencias de NPM con

```bash
  npm update
```

Copie el Archivo .env.example en un archivo nuevo .env con

```bash
  cp .env.example .env
```

Configure la base de datos y las demás variables de entorno en el archivo .env

Genere una nueva Key para el proyecto con

```bash
  php artisan key:generate
```

Corra las migraciones del proyecto con

```bash
  php artisan migrate
```

Corra los seeder del proyecto con

```bash
  php artisan db:seed
```

Instale las dependencias de vue

```bash
  npm artisan ui vue
```

Corra el proyecto con

```bash
  php artisan serve
```

Si todo está correcto puede acceder al proyecto en la dirección http://localhost:8000

Usuario: admin@admin.com

Contraseña: Admin



## Authors

- [@Jp-dsouls](https://github.com/Jp-dsouls)

