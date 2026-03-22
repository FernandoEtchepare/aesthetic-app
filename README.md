# Aesthetic Gym App

App móvil y desktop para alumnos de Aesthetic Gym. Gestión de rutinas, comunidad, perfil y feedback, con la misma identidad visual premium de la marca.

## Estructura del proyecto

```
aesthetic-app/
└── mockups/
    ├── index.html              ← Índice visual de todas las pantallas
    ├── assets/
    │   └── design-system.css  ← Variables, componentes y frames reutilizables
    ├── mobile/                 ← Mockups 390×844 (iPhone)
    │   ├── 01-login.html
    │   ├── 02-registro.html
    │   ├── 03-rutina.html
    │   ├── 04-ejercicio-video.html
    │   ├── 05-perfil.html
    │   ├── 06-comunidad.html
    │   └── 07-feedback.html
    └── desktop/                ← Mockups 1280×800
        ├── 01-login.html
        ├── 02-rutina.html
        ├── 03-ejercicio-video.html
        ├── 04-perfil.html
        ├── 05-comunidad.html
        └── 06-feedback.html
```

## Pantallas

| # | Pantalla | Mobile | Desktop |
|---|---|---|---|
| 01 | Login | ✓ | ✓ |
| 02 | Registro | ✓ | — |
| 03 | Rutina del día | ✓ | ✓ |
| 04 | Ejercicio + Video | ✓ | ✓ |
| 05 | Perfil | ✓ | ✓ |
| 06 | Comunidad + Check-in | ✓ | ✓ |
| 07 | Feedback | ✓ | ✓ |

## Design system

- **Paleta:** Negro `#0a0a0a` + Dorado `#C9A84C`
- **Tipografía:** Cormorant Garamond (display) + Montserrat (body)
- **Frame mobile:** 390×844 px con marco de iPhone
- **Frame desktop:** 1280×800 px con sidebar + topbar
