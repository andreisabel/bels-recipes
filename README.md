# 🍳 Proyecto Fundamentos Desarrollo Web Semestre 2023/I: Bel's Recipes - Blog de Recetas Interactivo

## 🚀 1. Descripción y Objetivo General

**Bel's Recipes**, es un **Blog de Recetas Interactivo** desarrollado como **Proyecto Universitario**.

El objetivo principal del proyecto es proporcionar a los lectores **recetas detalladas, fáciles de seguir y visualmente atractivas**, brindando opciones y recursos a las personas que buscan inspiración y desean mejorar sus habilidades culinarias.

El sistema está enfocado en una arquitectura **cliente-servidor** clásica, con un fuerte énfasis en la **interacción del usuario** y la **administración del contenido**.

---

## ✨ 2. Especificación de Funcionalidades

El proyecto implementa las siguientes funcionalidades clave, que involucran el uso de **PHP y MySQL**[cite: 19]:

| No. | Funcionalidad | Descripción | Roles Involucrados |
| :---: | :--- | :--- | :--- |
| **1** | **Comentarios** | Los usuarios pueden dejar comentarios y opiniones que se almacenan y se muestran junto a la receta. | Comentarista |
| **2** | **Sistema de Búsqueda** | Permite a los usuarios encontrar recetas relevantes utilizando términos específicos. | Lector, Visitante, Comentarista |
| **3** | **Registro e Inicio de Sesión** | Los usuarios deben poseer una cuenta para acceder a funciones personalizadas como guardar recetas y comentar. | Visitante, Comentarista |
| **4** | **Sistema de Perfil** | Los usuarios pueden acceder a funciones personalizadas, incluyendo la gestión de sus **"Elementos Guardados"** (recetas favoritas). | Lector, Comentarista, Autor |
| **5** | **Administración de Entradas** | Permite a los usuarios con privilegios (Autor/Administrador) eliminar y editar las recetas o posts del blog. | Administrador |
| **6** | **Categorización** | Las recetas están clasificadas por tipo de comida para facilitar la navegación (Desayunos, Platillos, Postres, Bebidas, Tips). | Lector, Visitante |

---

## 💾 3. Estructura de la Base de Datos (`blogrecetas`)

El proyecto utiliza una base de datos relacional **MySQL** (`blogrecetas`).

---

## 🛠️ 4. Tecnologías y Dependencias

* **Backend / Lógica:** **PHP**
* **Base de Datos:** **MySQL** (MariaDB)
* **Frontend / Diseño:** **HTML, CSS, JavaScript**
* **Entorno de Desarrollo:** Se recomienda el uso de **XAMPP o Laragon**.

## ⚙️ 5. Instalación y Configuración Local

1.  **Clonar Repositorio:** Mueve el proyecto a tu directorio web (`htdocs` o `www`).
2.  **Configurar Base de Datos:**
    * Inicia tu servidor MySQL y accede a phpMyAdmin.
    * Crea una base de datos llamada `blogrecetas`.
    * Importa el archivo **`blogrecetas.sql`** para crear las tablas y datos de muestra.
3.  **Ejecutar:** Accede al proyecto a través de tu navegador local (ej. `http://localhost/Cook-Up-Web/`).

---

## 👨‍💻 6. Autora

Este proyecto fue desarrollado por:
* Andrea Isabel Vega Márquez
