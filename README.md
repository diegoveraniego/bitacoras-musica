<div align="center">
  <img src="logo.svg" alt="Bitácoras de Audición Logo" height="80" style="filter: invert(0);">

  # Bitácoras de Audición

  Plataforma web colaborativa para que profesores de música en Chile gestionen, compartan y consulten **bitácoras de audición** para uso curricular.

  🔗 **[Ver la aplicación en vivo](https://diegoveraniego.github.io/bitacoras-musica/)**

</div>

---

## Características Principales

- **Arquitectura Serverless** — Single Page Application en Vanilla JS, sin build steps.
- **Base de Datos en la Nube** — [Supabase](https://supabase.com/) (PostgreSQL) para almacenamiento colaborativo.
- **Acceso por clave** — Login simple con nombre de usuario y clave para editar y agregar bitácoras.
- **Filtros avanzados** — Filtra el catálogo por género, instrumento, idioma, país y estado.
- **Historial de Cambios** — Registro estilo Wikipedia de quién editó cada bitácora y cuándo.
- **Covers cuadrados** — Visualización tipo Spotify de los álbumes.
- **Detalle Musical** — Secciones tonales, BPM, métrica, progresiones armónicas, clasificación curricular.
- **Panel de Actividad Reciente** — Revisión de bitácoras pendientes de aprobación.
- **Interfaz Adwaita** — Estética inspirada en GNOME/Adwaita.

## Uso

| Usuario   | Contraseña | Rol       |
|-----------|------------|-----------|
| `diego`   | `1234`     | Editor    |
| `gustavo` | `1234`     | Editor    |
| `alvaro`  | `1234`     | Editor    |

Los visitantes sin sesión pueden **navegar y filtrar** el catálogo libremente. Solo los usuarios autenticados pueden **crear y editar** bitácoras.

## Stack Técnico

| Capa       | Tecnología              |
|------------|-------------------------|
| Frontend   | HTML + Vanilla JS + CSS |
| Base datos | Supabase (PostgreSQL)   |
| Hosting    | GitHub Pages            |
| Auth       | localStorage (testing)  |
