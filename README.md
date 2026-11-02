# SolarQuote · Photon Labs

Landing page estática del proyecto académico **“De estudiante de ingeniería a consultor en energía solar”**, correspondiente a la materia **TE1020 · Análisis de Circuitos Eléctricos**.

SolarQuote presenta la solución propuesta por Photon Labs para convertir información de consumo eléctrico en una propuesta preliminar de dimensionamiento y cotización de un sistema fotovoltaico.

> **Alcance actual:** este repositorio contiene únicamente la landing page informativa. No implementa todavía el simulador, el cálculo de dimensionamiento, el catálogo de equipos ni la generación del reporte PDF.

## Contenido del repositorio

```text
solarquote-landing-page/
├── index.html                 # Página principal; punto de entrada de GitHub Pages
├── README.md                  # Documentación del proyecto
├── .nojekyll                  # Evita el procesamiento de Jekyll
├── assets/
│   ├── solarquote-logo.png    # Logo rosa y navy de SolarQuote
│   └── favicon.svg            # Icono del sitio
├── css/
│   └── styles.css             # Estilos, paleta y diseño adaptable
└── js/
    └── main.js                # Menú móvil accesible
```

## Identidad visual

| Color | Código | Aplicación |
|---|---|---|
| Navy | `#0B1F44` | Fondos, títulos y elementos principales |
| Blue | `#2E5BFF` | Acentos técnicos |
| Pink | `#FF4FA3` | Color distintivo de SolarQuote |
| Cream | `#FFF7E0` | Fondos secundarios |
| Slate | `#CBD5E1` | Bordes y elementos neutros |

## Ver la página localmente

No requiere instalación, dependencias ni compilación.

1. Descarga o clona este repositorio.
2. Abre `index.html` en un navegador.

Para una vista local con un servidor estático opcional, ejecuta desde la carpeta del proyecto:

```bash
python -m http.server 8000
```

Después abre `http://localhost:8000`.

## Publicar con GitHub Pages

1. Sube **todos los archivos y carpetas** de este repositorio a la raíz de un repositorio de GitHub. No subas solamente `index.html`.
2. En GitHub, abre **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**.
4. Selecciona la rama `main` y la carpeta `/(root)`.
5. Presiona **Save** y espera a que GitHub Pages termine el despliegue.

La URL tendrá este formato:

```text
https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/
```

Si el repositorio se llama `TU-USUARIO.github.io`, la URL será:

```text
https://TU-USUARIO.github.io/
```

## Personalización

- Edita el contenido y las secciones en `index.html`.
- Modifica colores, tipografía, espaciado y diseño en `css/styles.css`.
- Cambia la navegación móvil en `js/main.js`.
- Sustituye el logo conservando la ruta `assets/solarquote-logo.png`, o actualiza la ruta de imagen en `index.html`.

## Nota técnica y académica

La página describe una solución conceptual y sus módulos previstos. Cualquier propuesta fotovoltaica real deberá respaldar sus resultados con datos de consumo, condiciones de irradiación, pérdidas, fichas técnicas vigentes, comprobaciones de compatibilidad eléctrica y validación profesional. El dimensionamiento presentado por el futuro simulador tendrá carácter preliminar y no sustituirá un proyecto ejecutivo autorizado.

## Créditos

**Photon Labs S.A. de C.V.** — empresa ficticia del escenario académico.  
**SolarQuote** — identidad de la aplicación de dimensionamiento y cotización fotovoltaica.  
**TE1020 · Análisis de Circuitos Eléctricos** — proyecto académico individual.
