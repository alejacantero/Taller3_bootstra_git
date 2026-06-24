# 🌐 Portafolio Web — Alejandra Londoño Cantero

Proyecto desarrollado como parte del programa de **Análisis y Desarrollo de Software (ADSO)** en Medellín, Colombia. Construido con **Bootstrap 5.3** y **Bootstrap Icons**, sin frameworks adicionales de JavaScript.

---

## 📁 Estructura del proyecto

```
taller3/
│── app/
│    ├── forms.html       → Login y registro
│    ├── tables.html      → Tabla de jugadores del Mundial 2026
│    └── github.html      → Guía de Git y GitHub
│── assets/
│    ├── css/
│    ├── img/
│    └── js/
│── index.html            → Página principal
│── README.md
```

---

## 📄 Páginas

### `index.html` — Página principal

Página de inicio tipo portafolio/landing page. Incluye:

- **Navbar** fija con menú colapsable, dropdown de productos y botón de acceso
- **Carrusel** de imágenes automático (3 slides)
- **Sección 1:** Lista de columnas con tarjetas numeradas
- **Sección 2 (Servicios):** Tres tarjetas con íconos sobre fondo oscuro
- **Sección 3:** Cuadrícula de 4 tarjetas con ícono centrado
- **Sección 4:** Diseño de tres columnas con imagen circular central
- **Sección 5:** Layout de barra lateral izquierda y contenido principal
- **Footer** con créditos

---

### `app/forms.html` — Acceso (Login y Registro)

Página de autenticación con dos formularios lado a lado:

- **Iniciar sesión:** campos de correo y contraseña, enlace "¿Olvidaste tu contraseña?" y botón de ingreso
- **Registrarse:** campos de nombre, correo, contraseña y confirmación, con botón de creación de cuenta
- Ambos formularios usan `input-group` con íconos de Bootstrap Icons
- Botón "Salir" en la navbar que redirige al inicio

---

### `app/github.html` — Guía de Git y GitHub

Guía paso a paso para inicializar un proyecto con Git y subirlo a GitHub. Seis secciones en tarjetas con encabezados de colores:

| # | Sección | Color |
|---|---------|-------|
| 1 | Estructura del proyecto | Azul |
| 2 | Requisitos iniciales | Verde |
| 3 | Configuración de Git | Cian |
| 4 | Inicializar Git en el proyecto | Amarillo |
| 5 | Crear repositorio en GitHub | Azul |
| 6 | Conectar proyecto local con GitHub | Amarillo |

Cada sección incluye bloques de código estilo terminal (`bg-dark text-success`) y alertas informativas.

---

### `app/tables.html` — Jugadores del Mundial 2026

Tabla responsiva con 20 jugadores de la Copa Mundial de la FIFA 2026 (Canadá · México · Estados Unidos). Columnas:

`#` · `Jugador` · `Selección` · `Posición` · `Club` · `Edad` · `Dorsal` · `Goles` · `Asistencias` · `Partidos`

Las posiciones se distinguen con badges de colores: `EX` (extremo/delantero), `DE` (delantero), `MC` (mediocampista), `DF` (defensa), `PO` (portero).

---

## 🛠️ Tecnologías utilizadas

- [Bootstrap 5.3.8](https://getbootstrap.com/)
- [Bootstrap Icons 1.13.1](https://icons.getbootstrap.com/)
- HTML5 semántico

## 🚀 Cómo ejecutar el proyecto

1. Clona el repositorio:
   ```bash
   git clone https://github.com/alejacantero/Taller3_bootstra_git.git
   ```
2. Abre `index.html` en tu navegador, o usa la extensión **Live Server** de VS Code.

> No requiere instalación de dependencias ni servidor backend.

---

## 👩‍💻 Autora

**Alejandra Londoño Cantero** — Estudiante de Análisis y Desarrollo de Software · Medellín, Colombia
