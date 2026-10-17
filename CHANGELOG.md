# Changelog

Todos los cambios relevantes de este proyecto se documentan en este archivo.

El formato se basa en [Keep a Changelog](https://keepachangelog.com/es-ES/1.1.0/)
y el proyecto usa [Versionado Semántico](https://semver.org/lang/es/).

## [1.0.1] - 2026-10-17

### Corregido

- Media query del `<link>` de los estilos de tablet, al que le faltaba el paréntesis de cierre ([#3](https://github.com/nqs48/AmericanCharge_ADev/pull/3)).

### Cambiado

- README rediseñado con enfoque de portfolio: capturas actuales en desktop, tablet y móvil, y secciones de layout, despliegue y modelo de ramas.

## [1.0.0] - 2026-10-17

### Cambiado

- Despliegue migrado de Heroku a Netlify como sitio estático, con `netlify.toml` y caché para `assets/` y `public/` ([#1](https://github.com/nqs48/AmericanCharge_ADev/pull/1)).
- Se elimina `index.php`, que solo servía para el buildpack PHP de Heroku.

### Corregido

- Enlaces rotos de las tarjetas **Proyectos** y **Portfolio**: ahora apuntan a [nesst.tech](https://nesst.tech/).
- Enlace del sitio en el README, que ahora apunta a [americancharge-adev.netlify.app](https://americancharge-adev.netlify.app/).

[1.0.1]: https://github.com/nqs48/AmericanCharge_ADev/compare/v1.0.0...v1.0.1
[1.0.0]: https://github.com/nqs48/AmericanCharge_ADev/releases/tag/v1.0.0
