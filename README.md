# Gestión LocalStorage

Demo en JavaScript y HTML que muestra el uso básico de la API `localStorage` del navegador para persistir datos clave-valor.

## Características

- Guardar un dato asociando un nombre de usuario a una categoría (Administrador, Editor o Usuario) mediante `localStorage.setItem`.
- Leer el valor asociado a un nombre concreto.
- Listar todos los pares clave-valor almacenados actualmente en `localStorage`.
- Borrar el dato asociado a un nombre concreto (`localStorage.removeItem`).
- Vaciar por completo el almacenamiento local (`localStorage.clear`).
- Mensajes de aviso (`alert`) para validar que los campos requeridos estén rellenos antes de operar.

## Tecnologías

- HTML5
- JavaScript vanilla (API `localStorage`, sin frameworks ni dependencias externas)

## Instalación / Cómo ejecutarlo

No requiere instalación ni servidor:

1. Clona el repositorio.
2. Abre `public/index.html` directamente en un navegador (Chrome, Firefox, Edge, etc.).

Ejercicio académico que practica el uso de la API `localStorage` para almacenar datos en el navegador de forma persistente, sin depender de cookies ni de un servidor.

## Licencia

GPL versión 3 (ver archivo [LICENSE](LICENSE)).
