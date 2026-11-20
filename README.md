# Gestión académica

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

Proyecto de **Introducción a la Programación — Segundo momento**. Presenta la capa visual de un portal académico para una institución educativa, con vistas para consultar información de estudiantes, docentes, matrículas, notas y asistencia.

La entrega está enfocada en la **estructura semántica HTML y su presentación con CSS puro**, de acuerdo con la guía del proyecto. Es un prototipo visual que usa JavaScript únicamente para la navegación demostrativa; no utiliza frameworks, backend ni base de datos. Los formularios, filtros y datos de las tablas no guardan ni consultan información.

## Vistas

- [Página principal](./index.html): bienvenida al portal de una institución educativa, introducción y visión institucional.
- [Inicio](./Frontend/Pages/index.html): accesos a perfil y consultas académicas.
- [Mi perfil](./Frontend/Pages/perfil.html), [matrículas](./Frontend/Pages/matriculas.html), [notas](./Frontend/Pages/notas.html), [asistencia](./Frontend/Pages/asistencia.html) y [horario](./Frontend/Pages/horario.html): consultas de solo lectura para usuarios.
- [Conócenos](./Frontend/Pages/conocenos.html): misión, visión y valores.
- [Panel administrativo](./Frontend/Admin/admin.html): acceso a estudiantes, docentes, matrículas, notas, asistencia, asignaciones y gestión académica.
- [Inicio de sesión](./Frontend/Auth/login.html) y [registro](./Frontend/Auth/register.html): vistas demostrativas.

El registro lleva a la vista de inicio de usuario. El login permite elegir entre Usuario y Administrador y abre la vista correspondiente como demostración. No hay autenticación real ni protección de las páginas.

## GitHub Pages

Enlace al proyecto publicado: `https://teost09.github.io/gestion_academica/`


## Cómo visualizarlo

1. Descarga o clona el repositorio.
2. Abre `index.html` en un navegador.
3. Usa la navegación lateral para recorrer las vistas.