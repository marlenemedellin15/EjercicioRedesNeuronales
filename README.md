## Descripción del código
El siguiente código tiene como función ser un clasificador de números escritos, en cual por medio de una entrada dibujada en el explorador (un número del 0 al 9), al dar clic en predecir intentará decir qué número es, utilizando Tensorflow.js, tomando como base a un modelo entrenado en Python con ayuda de la librería de Tensorflow.

## Cómo utilizarlo

### Descargar el repositorio
Descarga el repositorio dentro de su computadora en cualquier ubicación que desees.

### IniciaR un servidor en la carpeta
Este proyecto utiliza un modelo de Tensorflow.js, por lo tanto para cargarse requiere estrictamente que el acceso sea por medio de http/https de otro modo este no se ejecutará o marcará errores dentro de su ejecución, para esto se puede hacer uso de cualquier servidor, pero aquí se presenta una forma de realizarlo con ayuda de python:
- Descargue Python dentro de su computadora. (Enlace de descarga https://www.python.org/downloads/)
- Abre una línea de comandos o terminal.
- Navegue hasta la carpeta donde previamente guardo el repositorio.
- Una vez en dentro de la carpeta, ejecute el comando `python -m http.server 8000`
- Abra un navegador web y diríjase a http://localhost:8000

### Uso
Dentro del canvas cuadrado dibuje un numero número del 0 al 9 con ayuda del mouse o con ayuda de su dedo si cuenta con una pantalla táctil, y posteriormente de clic en el botón en "Predecir". 
Para limpiar el canvas simplemente de clic en el botón"Limpiar".
