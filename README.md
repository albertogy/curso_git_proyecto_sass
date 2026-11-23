# Proyecto de Estilos CSS

## 1. Descripción y Finalidad
Este proyecto es una práctica desarrollada en el marco de un curso de **Git y control de versiones**. 

Su finalidad principal es servir como entorno de pruebas y aprendizaje práctico para dominar el flujo de trabajo con Git (creación de repositorios, gestión de ramas, confirmación de cambios (*commits*), etiquetas y resolución de conflictos), utilizando como ejemplo una arquitectura modular y escalable de estilos con **Sass/SCSS** y **CSS**.

---

## 2. Objetivos
- **Control de versiones:** Practicar comandos esenciales de Git (`git init`, `git add`, `git commit`, `git branch`, `git merge`, etc.).
- **Arquitectura de estilos:** Organizar una estructura limpia y desacoplada de estilos separando componentes, páginas y maquetación general.
- **Gestión de exclusiones:** Configurar correctamente el archivo `.gitignore` para controlar qué ficheros deben rastrearse y cuáles excluirse (como archivos compilados o temporales).
- **Buenas prácticas:** Fomentar la documentación y el trabajo colaborativo estándar en proyectos de desarrollo web.

---

## 3. Estructura de Carpetas

```text
proyecto-estilos-css/
├── .gitignore
├── README.md
├── build/
│   └── index.css
├── components/
│   └── button.scss
├── layout/
│   └── login.scss
└── pages/
    └── home.scss
```

---

## 4. Descripción de los Principales Archivos

| Archivo / Directorio | Descripción |
| :--- | :--- |
| **`README.md`** | Documento principal con la presentación, propósito, estructura y detalles del proyecto. |
| **`.gitignore`** | Reglas para indicar a Git qué archivos o carpetas deben ser ignorados en el repositorio. |
| **`build/index.css`** | Archivo CSS compilado final listo para ser consumido por el navegador. |
| **`components/button.scss`** | Estilos modulares y reutilizables para los botones de la interfaz. |
| **`layout/login.scss`** | Estructura y maquetación de la pantalla o sección de inicio de sesión (*login*). |
| **`pages/home.scss`** | Reglas de estilo específicas para la vista principal o página de inicio (*home*). |

---

## 5. Autor del Proyecto
- **Autor:** Alberto Ogayar
- **Contacto:** aogayar@dipujaen.es
- **Curso:** Curso de Git
