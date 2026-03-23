# Aesthetic Gym App

App móvil y desktop para alumnos y profesores de Aesthetic Gym. Gestión de rutinas, comunidad, perfil, feedback y panel de gestión para profesores, con la misma identidad visual premium de la marca.

## Estructura del proyecto

```
aesthetic-app/
└── mockups/
    ├── index.html                  ← Landing: elegir tipo de usuario
    ├── socios.html                 ← Índice de pantallas del socio
    ├── profesor.html               ← Índice de pantallas del profesor
    ├── assets/
    │   └── design-system.css       ← Variables, componentes y frames reutilizables
    ├── mobile/                     ← Socio · Mobile 390×844 (iPhone)
    │   ├── 01-login.html
    │   ├── 02-registro.html
    │   ├── 03-rutina.html
    │   ├── 04-ejercicio-video.html
    │   ├── 05-perfil.html
    │   ├── 05-perfil-light.html
    │   ├── 06-comunidad.html
    │   ├── 07-feedback.html
    │   └── 08-checkin.html
    ├── desktop/                    ← Socio · Desktop 1280×800
    │   ├── 01-login.html
    │   ├── 02-rutina.html
    │   ├── 03-ejercicio-video.html
    │   ├── 04-perfil.html
    │   ├── 04-perfil-light.html
    │   ├── 05-comunidad.html
    │   ├── 06-feedback.html
    │   └── 07-checkin.html
    ├── profesor/                   ← Profesor · Mobile 390×844
    │   ├── 01-login.html
    │   ├── 02-inicio.html
    │   ├── 03-socios.html
    │   ├── 04-perfil-socio.html
    │   ├── 05-rutinas.html
    │   ├── 06-crear-rutina.html
    │   ├── 07-mensajes.html
    │   └── 08-premios.html
    └── profesor-desktop/           ← Profesor · Desktop 1280×800
        ├── 01-login.html
        ├── 02-inicio.html
        ├── 03-socios.html
        ├── 04-perfil-socio.html
        ├── 05-rutinas.html
        ├── 06-crear-rutina.html
        ├── 07-mensajes.html
        └── 08-premios.html
```

## Pantallas — Socio

| # | Pantalla | Mobile | Mobile Light | Desktop | Desktop Light |
|---|---|---|---|---|---|
| 01 | Login | ✓ | — | ✓ | — |
| 02 | Registro | ✓ | — | — | — |
| 03 | Rutina del día | ✓ | — | ✓ | — |
| 04 | Ejercicio + Video | ✓ | — | ✓ | — |
| 05 | Perfil | ✓ | ✓ | ✓ | ✓ |
| 06 | Comunidad | ✓ | — | ✓ | — |
| 07 | Feedback | ✓ | — | ✓ | — |
| 08 | Check-in | ✓ | — | ✓ | — |

## Pantallas — Profesor

| # | Pantalla | Mobile | Desktop |
|---|---|---|---|
| 01 | Login | ✓ | ✓ |
| 02 | Inicio / Dashboard | ✓ | ✓ |
| 03 | Socios | ✓ | ✓ |
| 04 | Perfil de socio | ✓ | ✓ |
| 05 | Rutinas | ✓ | ✓ |
| 06 | Crear rutina | ✓ | ✓ |
| 07 | Mensajes | ✓ | ✓ |
| 08 | Premios | ✓ | ✓ |

## Design system

- **Paleta:** Negro `#0a0a0a` + Dorado `#C9A84C`
- **Tipografía:** Cormorant Garamond (display) + Montserrat (body)
- **Frame mobile:** 390×844 px con marco de iPhone, Dynamic Island, edge-to-edge
- **Frame desktop:** 1280×800 px con sidebar + topbar
- **Responsive:** Vista real en iPhone (≤480px) con `position: fixed` en navbar y safe-area-inset
