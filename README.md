# RdvMedecins - Un ejemplo cliente/servidor con NestJS y React

Este repositorio acompaña a un curso sobre la reconstrucción de una aplicación cliente/servidor de gestión de citas médicas (`RdvMedecins`) con herramientas modernas. Contiene únicamente este README; el curso completo está disponible en línea.

## 📖 Lea el curso

**[https://stahe.github.io/ales-react-nestjs-sept-2026](https://stahe.github.io/ales-react-nestjs-sept-2026)**

## Acerca del curso

Este documento adapta un curso original de 2014 (*Un ejemplo cliente/servidor - AngularJS 1.x / Spring 4*) a las tecnologías actuales:
- El servidor, escrito en Java con Spring MVC, se reemplaza por un servidor **NestJS** (TypeScript);
- el cliente **AngularJS 1.x** se reemplaza por un cliente **React** (componentes funcionales, hooks);
- la funcionalidad principal y la base de datos se mantienen, en principio, sin cambios, con el añadido de la autenticación basada en roles (JWT), que no existía en el original.

Este curso fue escrito con la asistencia de la IA Claude (Anthropic), que generó la mayor parte del código y de las explicaciones; el autor probó y validó todo el curso siguiendo el documento generado.

## Contenido del curso

1. **Introducción** - Objetivos, requisitos previos, arquitectura general de la aplicación
2. **Capítulo 1** - Configuración del entorno de desarrollo
3. **Capítulo 2** - Introducción a NestJS
4. **Capítulo 3** - El servidor NestJS de la aplicación RdvMedecins
5. **Capítulo 4** - Introducción a React
6. **Capítulo 5** - El cliente React de la aplicación RdvMedecins
7. **Capítulo 6** - Conclusión y próximos pasos

## Tecnologías abordadas

- **Servidor**: NestJS, TypeORM, MySQL, autenticación JWT (`@nestjs/passport`, `@nestjs/jwt`), control de acceso basado en roles
- **Cliente**: React 19, Vite, TypeScript, hooks, i18next (internacionalización francés/inglés), Bootstrap

## Requisitos previos

No se requieren conocimientos previos de NestJS ni de React. Basta con una comprensión básica de JavaScript, HTTP y la línea de comandos para completar el curso con éxito.

## Autores

La IA Claude (principalmente) y Serge Tahé (pruebas del código y revisión del curso)
