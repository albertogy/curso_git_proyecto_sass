# Memoria de la práctica – Curso de Git

**Proyecto:** Proyecto de Estilos CSS  
**Alumno:** Alberto Ogayar  
**Asignatura:** Control de versiones con Git

## 1. Proyecto elegido

Para realizar esta práctica he creado un pequeño proyecto de estilos CSS, organizado mediante carpetas y archivos SCSS.

El objetivo principal ha sido aprender a utilizar Git para controlar las distintas modificaciones realizadas en un proyecto, registrar los cambios mediante commits y consultar el historial de versiones.

He elegido este ejemplo porque permite trabajar con varios archivos y carpetas, simulando la organización habitual de un proyecto de desarrollo web.

## 2. Estructura de archivos creada

He organizado el proyecto en las siguientes carpetas y archivos:

- **components/**: contiene los estilos de componentes reutilizables, como los botones (`button.scss`).
- **pages/**: contiene los estilos correspondientes a las páginas, como `home.scss`.
- **layout/**: contiene los estilos relacionados con la estructura de las pantallas, como `login.scss`.
- **build/**: carpeta destinada a los archivos CSS generados durante la compilación.
- **README.md**: documento donde explico el objetivo y la estructura del proyecto.
- **.gitignore**: archivo donde se indican los elementos que Git debe ignorar.
- **.git/**: carpeta interna de Git que almacena el historial y la información necesaria para gestionar el repositorio.

Esta estructura permite separar los archivos según su función y facilita el mantenimiento del proyecto.

## 3. Función del archivo .gitignore

He utilizado el archivo `.gitignore` para indicar a Git que debe ignorar la carpeta `build`.

La regla utilizada es:

`/build`

De esta forma, los archivos generados durante la compilación no se incorporan al control de versiones.

Esto permite mantener el repositorio más limpio, evitando guardar archivos que pueden volver a generarse a partir del código fuente.

## 4. Organización de los commits

He realizado cinco commits para registrar de forma progresiva los cambios del proyecto.

1. **Creación inicial del proyecto:** creación de la estructura inicial y los archivos básicos.
2. **Configuración de .gitignore:** incorporación de la regla para ignorar la carpeta de compilación.
3. **Estilos de componentes:** incorporación de los archivos correspondientes a los componentes.
4. **Estilos de páginas:** incorporación de los archivos correspondientes a las páginas.
5. **Estilos del login:** incorporación de los estilos de la pantalla de inicio de sesión.

He intentado organizar los commits por tareas, de manera que cada uno represente un cambio concreto y resulte sencillo identificar la evolución del proyecto.

Para consultar el historial he utilizado el comando `git log --oneline`.

## 5. Dificultades encontradas

Durante la práctica he tenido que familiarizarme con los comandos de Git y con el funcionamiento de Git Bash.

Una de las dificultades ha sido aprender a consultar correctamente el historial de commits. Inicialmente utilicé el parámetro `--online` en lugar de `--oneline`, lo que provocó un error al ejecutar el comando.

También he tenido algunas dificultades al copiar y pegar comandos en Git Bash, ya que los atajos de teclado no funcionan exactamente igual que en otras aplicaciones de Windows.

Por último, he aprendido la importancia de configurar correctamente `.gitignore` y de comprobar qué archivos se encuentran bajo el control de versiones.

## Conclusión

Esta práctica me ha permitido conocer el funcionamiento básico de Git, crear un repositorio, organizar archivos, registrar cambios mediante commits y consultar su historial.

También he comprendido la utilidad de `.gitignore` y la importancia de mantener un historial ordenado para facilitar el seguimiento de las modificaciones realizadas en un proyecto.