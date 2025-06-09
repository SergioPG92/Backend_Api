⚽ SOCCER MANAGER - Backend API

Este proyecto es una API desarrollada con **Laravel**. Está diseñada para ser consumida desde un frontend, puedes encontrar el oficial de Soccer Manager [aquí](https://github.com/SergioPG92/FrontEnd_Soccer_Manager)

---

📦 **Requisitos**

  Asegúrate de tener instalado en tu entorno local:

- PHP 8.1 o posterior
- Composer
- MySQL (u otro gestor de base de datos compatible)

---

⚙️ Instalación del proyecto

**1. Clonar el repositorio**

```bash
git clone https://github.com/SergioPG92/Backend_Api.git
cd ruta_del_proyecto
```

**2. Instalar dependencias de PHP**

```bash
composer install
```

**3. Configurar variables de entorno**

    Copia el archivo .env.example y renómbralo a .env


    Edita el archivo .env configurando corectamente las siguientes variables:
- APP_URL:   URL BASE DEL BACKEND
- DB_DATABASE: Nombre de la base de datos
- DB_USERNAME: Usuario de la base de datos
- DB_PASSWORD: Contraseña del usuario de base de datos
  
**4. Generar clave de aplicación**

```bash
php artisan key:generate
```

**5. Ejecutar migraciones**
```bash
php artisan migrate
```
    
