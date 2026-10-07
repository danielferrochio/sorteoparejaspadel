# sorteoparejaspadel
Aplicación web para sorteo de parejas de pádel

## Descripción

`sorteoparejaspadel` es una pequeña aplicación web para generar sorteos aleatorios de parejas de pádel. Permite ingresar una lista de participantes y obtener emparejamientos de forma rápida y sencilla desde el navegador.

## Características

- Interfaz simple basada en HTML/JavaScript.
- Cada pareja une un jugador de revés con uno de drive, al azar.
- De 2 a 16 parejas; el resultado sale agrupado por cancha (con cantidad impar, una pareja espera turno).
- Avisa líneas vacías, nombres de más, repetidos o el mismo nombre en revés y drive.
- Guarda los nombres en el navegador; volver a sortear evita repetir las parejas anteriores.
- Copiar el resultado, compartirlo como imagen o descargarlo en PNG.
- Pensada para uso rápido en móviles y ordenadores (abrir `index.html`).
- `comparar.html` muestra la versión anterior (`version-anterior.html`) junto a la actual.

## Cómo usar

1. Abrir el archivo `index.html` en tu navegador (doble clic) o servir el proyecto localmente.

	 - Con Python (desde la raíz del repositorio):

		 ```bash
		 python3 -m http.server 8000
		 # luego abrir http://localhost:8000
		 ```

2. Elegir cuántas parejas y escribir los jugadores de revés y de drive, uno por línea.
3. Pulsar el botón para generar el sorteo y obtener las parejas.

Si quieres que incluya un ejemplo visual o capturas de pantalla, dímelo y las agregaré.

## Desarrollo

- Estructura mínima: el archivo principal es `index.html` en la raíz del repositorio.
- No hay dependencias externas obligatorias; es una página estática.

Si vas a desarrollar nuevas funciones, crea una rama con un nombre descriptivo y abre un pull request cuando estés listo.

## Contribuir

- Abre un issue para proponer mejoras o reportar errores.
- Haz un fork, crea una rama, realiza los cambios y envía un pull request.
- Mantén los commits pequeños y la descripción clara.

## Licencia

Este proyecto está bajo la licencia indicada en el archivo `LICENSE`.

## Autor

Daniel Ferrochio — GitHub: `danielferrochio`

Esta aplicación ha sido desarrollada con la ayuda de **Google Gemini**.

## Demo / Página pública

La aplicación está publicada usando GitHub Pages y se puede ver en:

https://danielferrochio.github.io/sorteoparejaspadel/

Esta URL sirve la versión estática del proyecto (`index.html`) desde el repositorio. Si necesitas que actualice la configuración de GitHub Pages (por ejemplo, cambiar la rama publicada o la carpeta `/docs`), puedo añadir instrucciones o un pequeño archivo `CNAME` si quieres usar un dominio personalizado.
