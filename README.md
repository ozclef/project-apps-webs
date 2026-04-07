# project-apps-webs


-----




# 🚗 Venta de Autos & Motos — SPA (Single File App)

Aplicación web tipo **SPA (Single Page Application)** desarrollada en un solo archivo HTML.
Incluye **landing page, login simulado y panel CRUD**, todo funcionando en el navegador sin backend.

---

# 🧠 Descripción

Este proyecto es una **simulación completa de una tienda de vehículos**, donde puedes:

* Visualizar autos y motos
* Filtrar por tipo
* Iniciar sesión (modo admin)
* Administrar vehículos (CRUD: crear, editar, eliminar)

⚠️ **Importante:**
Todo funciona en memoria (JavaScript). No hay base de datos real ni backend.

---

# ⚙️ Tecnologías usadas

* HTML5
* CSS3 (inline)
* JavaScript Vanilla (sin frameworks)
* DOM manipulation
* Estado en memoria

---

# 🧩 Estructura del proyecto

Todo el sistema está contenido en un solo archivo:

```
index.html
```

Dentro incluye:

* `<style>` → diseño visual
* `<script>` → lógica completa (app)
* HTML → vistas dinámicas

---

# 🚀 Funcionalidades

## 🏠 Landing Page

* Muestra vehículos disponibles
* Filtro por tipo:

  * Todos
  * Autos
  * Motos

---

## 🔐 Login (Simulado)

* Acceso al panel de administración
* No valida credenciales reales
* Cualquier usuario/contraseña funciona

---

## 🛠 Panel CRUD (Admin)

Permite:

* ➕ Agregar vehículos
* ✏️ Editar vehículos
* ❌ Eliminar vehículos

Datos manejados:

* Nombre
* Tipo (auto/moto)
* Precio
* Imagen

---

## 📊 Estado de la aplicación

Variables principales:

```js
let usuarioAutenticado = false;
let tipoActual = "todos";
let items = [];
```

---

# ⚠️ Limitaciones

Este proyecto es una **simulación**, por lo tanto:

❌ No guarda datos permanentemente
❌ No tiene backend
❌ No tiene base de datos
❌ No tiene autenticación real
❌ No soporta múltiples usuarios

---

# 🧪 Uso

1. Abrir el archivo `index.html` en el navegador
2. Navegar por la landing
3. Presionar **Login**
4. Acceder al panel admin
5. Gestionar vehículos

---

# 💡 Posibles mejoras

## 🔹 Nivel básico

* Usar `localStorage` para persistencia
* Separar CSS y JS en archivos externos

---

## 🔹 Nivel intermedio

* Modularizar JavaScript
* Separar lógica por archivos:

  ```
  /js/
    app.js
    auth.js
    crud.js
  ```

---

## 🔹 Nivel avanzado

* Integrar backend real
* Usar base de datos

Opciones recomendadas:

* Supabase (REST + Auth)
* Firebase
* Node.js + Express

---

# 🔐 Ejemplo mejora con localStorage

```js
localStorage.setItem("items", JSON.stringify(items));
```

---

# 🧠 Arquitectura

Este proyecto sigue un modelo tipo:

* SPA (Single Page Application)
* Render dinámico con JavaScript
* Estado global simple

---

# 📈 Objetivo del proyecto

Este proyecto sirve como:

* Base para futuras apps web
* Práctica de frontend sin frameworks
* Simulación de sistema CRUD
* Introducción a arquitectura SPA

---

# 🧑‍💻 Autor

Oscar Cruz Díaz

---

# ⚡ Nota final

Este proyecto **no es un producto final**, es una base.

👉 El siguiente paso natural es:

* agregar persistencia
* conectar backend real
* escalar a arquitectura modular

---

# 🔥 Frase clave

> “Primero hazlo funcionar, luego hazlo real.”   -Oscar

---
