# Bitácoras de Audición

Plataforma web colaborativa para que profesores de música en Chile gestionen, compartan y consulten "bitácoras de audición" para uso curricular. 

## Enlace al Proyecto
🔗 **[Ver la aplicación en vivo (GitHub Pages)](https://diegoveraniego.github.io/bitacoras-musica/)**

## Características Principales
- **Arquitectura Serverless:** Desarrollada como una Single Page Application (SPA) en Vanilla JS, sin necesidad de compilación (build steps).
- **Base de Datos Colaborativa:** Utiliza **Supabase** (PostgreSQL) para almacenamiento en la nube, reemplazando la base de datos SQLite local anterior.
- **Autenticación sin contraseñas:** Ingreso seguro mediante Magic Links enviados al correo (Supabase Auth).
- **Gestión de Permisos (RLS):**
  - Cualquier visitante puede navegar, filtrar y leer el catálogo de canciones aprobadas de forma pública.
  - Los profesores autenticados pueden proponer nuevas canciones (que ingresan en estado "pendiente").
  - Panel administrativo integrado para que usuarios logueados revisen los aportes recientes y aprueben las bitácoras pendientes.
- **Detalle Analítico Musical:** Sistema robusto de categorización (métrica, tempo, instrumentos, idiomas, clasificaciones curriculares) e ingreso de estructuras y progresiones armónicas de las secciones tonales.
- **Interfaz Fluida:** Estética inspirada en Adwaita/GNOME.
