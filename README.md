<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/744/744465.png" />

# 🚗 Car Rental Management System

### Plataforma web de gestión y renta de vehículos con Symfony 🚀

<p align="center">
  <b>Car Rental Management System</b> es una aplicación web desarrollada bajo arquitectura MVC utilizando Symfony, diseñada para gestionar alquileres de vehículos, reservas, usuarios y facturación desde una plataforma moderna y centralizada.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CarRental-WebPlatform-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Symfony-MVCFramework-000000?style=for-the-badge&logo=symfony&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/OpenSource-RentalSystem-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-módulos-del-sistema">Módulos</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-vista-previa">Vista previa</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Car Rental Management System** es una plataforma web desarrollada utilizando el framework Symfony y arquitectura MVC, enfocada en la administración de renta de vehículos y gestión empresarial de alquileres.

La plataforma permite gestionar reservas, vehículos, usuarios, pagos y estadísticas administrativas desde una interfaz intuitiva y moderna.

El sistema fue diseñado para:

- 🚗 Gestionar vehículos
- 👥 Administrar usuarios
- 📅 Gestionar reservas
- 💳 Controlar facturación
- 📊 Visualizar estadísticas
- 🔐 Gestionar accesos
- 🛒 Administrar pre-reservas
- 🌐 Automatizar operaciones

---

# ✨ Características

## 🚘 Gestión de vehículos

- 🚗 Visualización de vehículos disponibles
- 📍 Gestión de disponibilidad
- 💰 Configuración de tarifas
- 📋 Información detallada
- ⚡ Administración vehicular

---

## 👥 Gestión de usuarios

- 👤 Registro e inicio de sesión
- 📄 Gestión de perfiles
- 🔐 Roles administrativos
- ⚡ Dashboard personalizado
- 📊 Estadísticas de actividad

---

## 📅 Sistema de reservas

- 📆 Reservas dinámicas
- 🛒 Sistema de pre-reservas
- 📅 Selección de fechas
- ❌ Cancelación de reservas
- 💳 Gestión de facturación

---

## 📊 Dashboard administrativo

- 📈 Estadísticas generales
- 🚗 Gestión de vehículos
- 👥 Administración de usuarios
- 📅 Supervisión de reservas
- 🔐 Gestión de permisos

---

# 👨‍💼 Módulos del sistema

## 👤 Client Module

Este módulo es utilizado por clientes y empresas que rentan vehículos.

### Funcionalidades:

- 📊 Dashboard personalizado
- 🚗 Visualización de vehículos rentados
- 💳 Historial de facturación
- 📅 Gestión de reservas
- 📈 Estadísticas de alquileres

---

## 🚘 Owner Module

Este módulo administra los vehículos pertenecientes a empresas de renta.

### Funcionalidades:

- ➕ Agregar vehículos
- ✏️ Modificar automóviles
- ❌ Eliminar vehículos
- 📋 Supervisar rentas
- 💳 Visualizar facturación

---

## 🛠️ Admin Module

Este módulo funciona como administrador principal del sistema.

### Funcionalidades:

- 👥 Gestión de usuarios
- 🚗 Administración vehicular
- 📊 Dashboard administrativo
- 📅 Gestión de reservas
- 🔐 Control total del sistema

---

# 🛠️ Tecnologías utilizadas

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,bootstrap,js" />
</p>

- HTML5
- CSS3
- Bootstrap
- JavaScript

---

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=php,symfony" />
</p>

- PHP 7.4+
- Symfony Framework
- Arquitectura MVC
- Composer
- Gestión de sesiones

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

- MySQL
- Relaciones SQL
- Persistencia de datos
- Gestión de alquileres

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode" />
</p>

- Git
- GitHub
- Visual Studio Code
- Symfony CLI
- Composer

---

# 📂 Estructura del proyecto

```bash
PlataformaWebRentaVehiculosS/
│
├── src/                      # Código fuente Symfony
├── templates/                # Plantillas Twig
├── public/                   # Recursos públicos
├── assets/                   # Recursos frontend
├── config/                   # Configuración Symfony
├── migrations/               # Migraciones SQL
├── database/                 # Scripts SQL
├── tests/                    # Pruebas
├── .env                      # Variables de entorno
├── composer.json
├── README.md
└── LICENSE
```

---

# ⚡ Instalación

## 📋 Requisitos

- PHP >= 7.4
- Composer
- Symfony CLI
- MySQL
- Navegador moderno

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone --single-branch -b master https://github.com/isairey/PlataformaWebRentaVehiculosS.git
```

---

## 2️⃣ Instalar dependencias

```bash
composer install
```

---

## 3️⃣ Configurar base de datos

Editar archivo:

```bash
.env
```

Agregar:

```env
DATABASE_URL="mysql://root:password@127.0.0.1:3306/car_rental_system"
```

---

## 4️⃣ Crear base de datos

```bash
php bin/console d:d:c --if-not-exists
```

---

## 5️⃣ Importar SQL

Importar:

```bash
database/db.sql
```

---

## 6️⃣ Ejecutar proyecto

```bash
symfony server:start
```

Abrir:

```bash
http://127.0.0.1:8000
```

---

# 👥 Usuarios de prueba

| Nombre | Email | Contraseña | Rol |
|---|---|---|---|
| Hubert Pichet | hubert.pichet@gmail.com | Azerty123 | Empresa |
| Jerome Aurore | jerome.aurore@hotmail.com | Azerty123 | Empresa |
| Easy Rent | easyrent@easyrent.com | Azerty123 | Loueur |
| Sixt | sixt@sixt.com | Azerty123 | Loueur |

---

# 📊 Funcionalidades principales

## 🚗 Gestión vehicular

- Administración de automóviles
- Gestión de disponibilidad
- Configuración de tarifas
- Control de reservas

---

## 👥 Administración de usuarios

- Registro y autenticación
- Gestión de perfiles
- Roles administrativos
- Dashboard personalizado

---

## 📅 Gestión de reservas

- Pre-reservas dinámicas
- Selección de fechas
- Confirmaciones rápidas
- Facturación integrada

---

# 📸 Vista previa

## 🖥️ Interfaces del sistema

<div align="center">

### 🚗 Página principal
![Home](https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?q=80&w=1200&auto=format&fit=crop)

### 🔐 Inicio de sesión
![Login](https://images.unsplash.com/photo-1522202176988-66273c2fd55f?q=80&w=1200&auto=format&fit=crop)

### 🚘 Catálogo de vehículos
![Cars](https://images.unsplash.com/photo-1503376780353-7e6692767b70?q=80&w=1200&auto=format&fit=crop)

### 📅 Gestión de reservas
![Reservations](https://images.unsplash.com/photo-1550355291-bbee04a92027?q=80&w=1200&auto=format&fit=crop)

### 👥 Panel de usuarios
![Users](https://images.unsplash.com/photo-1521737604893-d14cc237f11d?q=80&w=1200&auto=format&fit=crop)

### 📊 Dashboard administrativo
![Dashboard](https://images.unsplash.com/photo-1460925895917-afdab827c52f?q=80&w=1200&auto=format&fit=crop)

### 💳 Facturación
![Billing](https://images.unsplash.com/photo-1554224155-6726b3ff858f?q=80&w=1200&auto=format&fit=crop)

### ⚙️ Configuración del sistema
![Settings](https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?q=80&w=1200&auto=format&fit=crop)

</div>

---

# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y administración

- Desarrollo web full stack
- Arquitectura MVC
- Symfony Framework
- Bases de datos relacionales
- CRUD administrativos
- Gestión vehicular
- Automatización de reservas

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Aplicación móvil
- ☁️ Infraestructura cloud
- 💳 Integración de pagos online
- 🤖 Reportes inteligentes
- 🌐 API REST moderna
- 🔔 Notificaciones en tiempo real
- 📍 Seguimiento GPS

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Java Developer

Desarrollador apasionado por programación orientada a objetos, sistemas administrativos y aplicaciones Java 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source bajo licencia MIT orientado al aprendizaje y administración de plataformas de renta vehicular.

---

<div align="center">

### 🚗 Car Rental Management System — administración moderna de vehículos y reservas 🚀

</div>
