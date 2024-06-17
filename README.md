# Tic-Tac-Toe

Este proyecto es un juego de Tic-Tac-Toe (Tres en línea) desarrollado con React y TypeScript, y utiliza Vite para el desarrollo y la construcción del proyecto.

## Estructura del proyecto

El proyecto se organiza en varios archivos y directorios:

- src/App.tsx: Este es el componente principal de la aplicación.
- src/components/: Este directorio contiene los componentes de React utilizados en la aplicación, incluyendo Board.tsx (el tablero del juego), Square.tsx (un cuadrado individual en el tablero), Turn.tsx (muestra el turno actual) y WinnerDialog.tsx (muestra un diálogo cuando hay un ganador).
- src/constants.ts: Este archivo contiene las constantes utilizadas en toda la aplicación.
- src/logic/: Este directorio contiene la lógica del juego, incluyendo board.ts (la lógica del tablero del juego) y storage/index.ts (la lógica para almacenar y recuperar el estado del juego).
- src/main.tsx: Este es el punto de entrada de la aplicación.

## Cómo ejecutar el proyecto

Para ejecutar este proyecto en su entorno local, siga estos pasos:

1. Clona el repositorio.
2. Ejecuta `npm install` para instalar las dependencias.
3. Ejecuta `npm run dev` para iniciar el servidor de desarrollo de Vite.
4. Ahora puedes abrir tu navegador y navegar a http://localhost:5000 para ver la aplicación en acción.

## Cómo construir el proyecto

Para construir este proyecto para producción, ejecuta `npm run build`. Esto generará una versión optimizada de la aplicación en el directorio dist.

## Linting

Este proyecto utiliza ESLint para el linting del código. Puedes ejecutar el linter con `npm run lint`.

## Dependencias

Este proyecto utiliza varias dependencias, incluyendo:

- react y react-dom para la creación de la interfaz de usuario.
- canvas-confetti para la animación de confeti cuando un jugador gana.
- vite para el desarrollo y la construcción del proyecto.
- typescript para el tipado estático y las características de ESNext.
- eslint y varios plugins para el linting del código.

Para más detalles, consulta el archivo package.json.
