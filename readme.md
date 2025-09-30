# Inventario PWA Demo

Una aplicación web progresiva (PWA) simple para gestionar inventario.

## Descripción

Esta aplicación permite gestionar un inventario básico con funcionalidades de PWA, incluyendo capacidades offline y notificaciones.

## Características

- 📱 Progressive Web App (PWA)
- 🗄️ Base de datos MySQL
- 🌐 API REST con Express.js
- 📴 Funcionalidad offline
- 🔄 Sincronización de datos

## Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/martsilvaUADE/inventory.git
cd inventory
```

2. Instala las dependencias:
```bash
npm install
```

3. Configura la base de datos MySQL:
   - Crea una base de datos llamada `inventory_db`
   - Configura las variables de entorno (opcional):
     - `DB_HOST`: Host de la base de datos (default: localhost)
     - `DB_USER`: Usuario de MySQL (default: root)
     - `DB_PASSWORD`: Contraseña de MySQL (default: vacía)
     - `DB_NAME`: Nombre de la base de datos (default: inventory_db)

4. Ejecuta la aplicación:
```bash
npm start
```

## Uso

1. Abre tu navegador en `http://localhost:80`
2. Agrega productos al inventario
3. La aplicación funciona offline después de la primera carga

## Tecnologías

- **Backend**: Node.js, Express.js
- **Base de datos**: MySQL
- **Frontend**: HTML, CSS, JavaScript vanilla
- **PWA**: Service Worker, Web App Manifest

## Configuración de la Base de Datos

La aplicación utiliza MySQL como base de datos. Puedes configurar la conexión mediante variables de entorno:

```bash
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=tu_contraseña
DB_NAME=inventory_db
```

Las tablas se crean automáticamente al iniciar la aplicación por primera vez.

## Licencia

ISC