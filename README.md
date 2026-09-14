# Aplicación de CEDICA - Equinoterapia

**Desarrollada por el Grupo42**

---

## 🔏Auth

Para autenticarte puedes seguir la siguiente tabla:
|Rol|E-mail|Contraseña|
|---|------|----------|
|System Admin|KITT2000@gmail.com|Firebird1982|
|Administracion|aaaa@gmail.com|Valorant|
|Tecnica|rere@gmail.com|12345678|
|Ecuestre|ornitorrinco@gmail.com|Perri|
|Voluntariado|Ver login con google| --- |

---

## 🚀 Funcionalidades principales

1. **Módulo de Usuarios**

   - CRUD de usuarios.
   - Asignación de roles y manejo de estado (activación/bloqueo).
   - Paginación, ordenamiento y búsqueda.

2. **Gestión de Equipos**

   - CRUD de miembros del equipo.
   - Asociación a usuarios.
   - Subida de documentos con MinIO.

3. **Registros de Pagos**

   - Gestión de pagos a empleados y gastos institucionales.
   - Seguimiento de pagos de Jinete & Amazonas.
   - Filtros avanzados por campos clave.

4. **Módulo Jinete & Amazonas (J&A)**

   - CRUD de miembros J&A.
   - Manejo de documentos.
   - Visualización de pagos y deudas.

5. **Gestión de Caballos**

   - CRUD de caballos.
   - Subida de documentos.

6. **Reportes y Estadísticas**
   - Visualización de 3 reportes clave.
   - Gráficos interactivos para análisis de datos.

---

## 🛠️ Tecnologías utilizadas

- **Backend**: Python (Flask, Pydantic)
- **Frontend**: Vue.js
- **Base de datos**: PostgreSQL
- **Almacenamiento**: MinIO
- **Estilos**: Tailwind CSS (configuración limitada).

---

## ⚙️ Instalación y configuración

### Requisitos previos

- Python 3.10 o superior.
- Node.js 16 o superior.
- PostgreSQL.
- MinIO configurado en tu entorno.
- Virtual env usado: <a href="https://python-poetry.org/docs/">poetry</a>
- Gestor de paquetes de node usado: <a href="https://docs.npmjs.com/downloading-and-installing-node-js-and-npm">npm</a>

### Pasos de instalación

1. Clona este repositorio.
2. Ejecuta

```bash
  cd admin
  poetry install
  cd ..
  cd portal
  npm install
```

### Gestion del dotenv

**Comunicarse con los miembros del equipo.**
