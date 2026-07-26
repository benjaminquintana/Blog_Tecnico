# Cómo organicé un proyecto de desarrollo web con HTML, Sass y Bootstrap

## Contexto

Durante el desarrollo de una landing page para un estudio creativo llamado **Nova Studio**, mi objetivo era crear un sitio moderno, responsive y fácil de mantener. El proyecto debía estar organizado de forma profesional utilizando HTML, Sass y Bootstrap.

## Problema

Al principio del proyecto toda la estructura estaba desordenada. No tenía claro cómo organizar los archivos Sass, qué estilos debían ir en cada carpeta ni cómo evitar repetir código. Además, algunas clases se superponían y era difícil mantener el proyecto a medida que agregaba nuevas secciones.

## Acciones

Para resolver el problema decidí reorganizar completamente el proyecto siguiendo una estructura más profesional.

- Separé los archivos Sass en carpetas como `base`, `layout`, `components` y `pages`.
- Centralicé las variables de colores, tipografías y espaciados en un solo archivo.
- Utilicé `@use` para importar únicamente los módulos necesarios.
- Aproveché Bootstrap para el sistema de grillas y componentes básicos, mientras que los estilos personalizados quedaron en Sass.
- Realicé commits frecuentes en GitHub para registrar cada cambio importante.

### Post-mortem

**Lo que funcionó bien**

- La estructura del proyecto quedó mucho más organizada.
- Fue más sencillo encontrar y modificar estilos.
- El uso de variables evitó repetir código.

**Lo que podría mejorar**

- Planificar la arquitectura del proyecto antes de comenzar a escribir estilos.
- Realizar commits todavía más pequeños y descriptivos.
- Documentar las decisiones desde el inicio.

## Aprendizajes

Este proyecto me permitió comprender que una buena organización es tan importante como escribir código. Aprendí a utilizar Sass de forma modular, combinarlo con Bootstrap y mantener un proyecto escalable mediante una estructura clara y el uso de control de versiones.

## Reflexión sobre feedback radicalmente sincero

Durante el desarrollo recibí observaciones sobre la organización del código y la estructura de los archivos. En lugar de tomarlas como una crítica, las utilicé para mejorar el proyecto. Gracias a ese feedback reorganicé el código, eliminé redundancias y conseguí una estructura más limpia y fácil de mantener.acepté las observaciones realizadas sobre la organización del proyecto. En lugar de interpretarlas como críticas personales, las utilicé para mejorar la estructura del código y la documentación. Esto permitió obtener un resultado más claro y profesional.
