# pet-store2
# 🐾 pet_store

> 🏪 Sistema completo para la gestión de una tienda de mascotas, desarrollado con arquitectura monolítica utilizando tecnologías modernas del lado del servidor y cliente.

---

## 📌 Descripción

`pet_store` es una aplicación web monolítica diseñada para gestionar las operaciones de una tienda de mascotas. Incluye funcionalidades como gestión de productos, usuarios, ventas y stock. Es ideal para pequeñas y medianas tiendas que necesitan una solución sencilla y eficaz.

---

## 🧱 Tecnologías y herramientas utilizadas

| Componente         | Descripción                                               |
|--------------------|-----------------------------------------------------------|
| 💻 Backend         | PHP (en entorno XAMPP con Apache)                         |
| 🎨 Frontend        | HTML5, CSS3, JavaScript + [Bootstrap 5](https://getbootstrap.com) |
| 🗄️ Base de Datos   | PostgreSQL gestionado mediante [Supabase](https://supabase.com)  |
| 🏗️ Arquitectura    | Monolítica                                                |

---

## 📂 Estructura del proyecto

```plaintext
pet_store/
├── public/             # Archivos accesibles públicamente
│   ├── index.php
│   └── assets/         # CSS, JS, imágenes, etc.
├── src/                # Lógica del negocio (PHP)
│   ├── controllers/
│   ├── models/
│   └── views/
├── database/           # Scripts y estructura de la base de datos
├── templates/          # Plantillas de Bootstrap
└── README.md           # Este archivo

