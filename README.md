# Proyecto Final Web2

Este proyecto es una aplicación web desarrollada con Node.js, Express y EJS, que incluye autenticación de usuarios, panel de administración, y una divertida tierlist de sabores Boing.

## Características
- Registro y login de usuarios con JWT y bcrypt
- Panel de administración para gestión de usuarios
- Tierlist visual de sabores Boing en diferentes situaciones
- Diseño moderno, colorido y responsivo
- Motor de plantillas EJS con layouts y parciales
- Base de datos MySQL

## Instalación
1. Clona el repositorio:
	```bash
	git clone https://github.com/victorHugoLeija/Proyecto-Final-Web2.git
	cd Proyecto-Final-Web2
	```
2. Instala las dependencias:
	```bash
	npm install
	```
3. Configura tu archivo `.env`:
	```env
	PORT=3000
	DB_HOST=localhost
	DB_USER=root
	DB_PASSWORD=tu_contraseña
	DB_NAME=UserDB
	JWT_SECRET=tu_clave_secreta
	```
4. Crea la base de datos y tabla ejecutando el script en `database/db.sql`.

## Uso
- Inicia el servidor en modo desarrollo:
  ```bash
  npm run dev
  ```
- Accede a `http://localhost:3000` en tu navegador.
- Regístrate, inicia sesión y explora la tierlist de Boing.

## Estructura del proyecto
```
├── src/
│   ├── server.js
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── public/
│   │   ├── css/
│   │   └── img/
│   ├── routes/
│   └── views/
│       ├── admin/
│       ├── auth/
│       ├── layouts/
│       ├── pages/
│       ├── partials/
│       ├── tierlist/
│       └── user/
├── database/db.sql
├── package.json
├── .env
└── README.md
```

## Créditos
- Desarrollado por Victor Hugo Leija
- Imágenes de Boing tomadas de Wikipedia y Google Images

## Licencia
Este proyecto está bajo la licencia ISC.
# Proyecto-Final-Web2
En este repositorio se subira un proyecto de node.js con un login y una pagina principal
