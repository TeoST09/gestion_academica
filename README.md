# Gestión académica

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

Proyecto de **Introducción a la Programación — Segundo momento**. Presenta la capa visual de una aplicación académica para organizar y consultar información de estudiantes, docentes, matrículas, notas y asistencia.

La entrega está enfocada en la **estructura semántica HTML y su presentación con CSS puro**, de acuerdo con la guía del proyecto. Es un prototipo visual: no utiliza JavaScript, frameworks, backend ni base de datos. Los formularios, filtros y datos de las tablas son demostrativos y no guardan ni consultan información.

## Vistas

- [Página principal](./index.html): presentación, indicadores y accesos rápidos.
- [Inicio](./Frontend/Pages/index.html): accesos a perfil y consultas académicas.
- [Mi perfil](./Frontend/Pages/perfil.html), [matrículas](./Frontend/Pages/matriculas.html), [notas](./Frontend/Pages/notas.html), [asistencia](./Frontend/Pages/asistencia.html) y [horario](./Frontend/Pages/horario.html): consultas de solo lectura para usuarios.
- [Conócenos](./Frontend/Pages/conocenos.html): misión, visión y valores.
- [Panel administrativo](./Frontend/Admin/admin.html): acceso a estudiantes, docentes, matrículas, notas, asistencia, asignaciones y gestión académica.
- [Inicio de sesión](./Frontend/Auth/login.html) y [registro](./Frontend/Auth/register.html): vistas demostrativas.

El login es únicamente una navegación de demostración: al enviar el formulario (con Enter o con el botón) abre el panel administrativo. No autentica usuarios ni protege las páginas.

## GitHub Pages

Enlace al proyecto publicado: `https://teost09.github.io/gestion_academica/`


## Cómo visualizarlo

1. Descarga o clona el repositorio.
2. Abre `index.html` en un navegador.
3. Usa la navegación lateral para recorrer las vistas.