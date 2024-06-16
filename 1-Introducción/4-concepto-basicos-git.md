## Teoría para el Examen de GitHub para Programadores Web

### Parte 1: Conceptos Básicos de Git y GitHub

#### Define Git y GitHub:

**¿Qué es Git?**
Git es un sistema de control de versiones distribuido que permite a los desarrolladores rastrear cambios en su código, colaborar con otros y mantener un historial completo de todos los cambios realizados. Git permite la creación de ramas para trabajar en paralelo y fusionar cambios sin perder el historial.

**¿Qué es GitHub y cómo se diferencia de Git?**
GitHub es una plataforma de alojamiento de código basada en la web que utiliza Git para la gestión de versiones. Además de proporcionar almacenamiento remoto para repositorios Git, GitHub ofrece herramientas adicionales para la colaboración, como pull requests, issues, y GitHub Actions. La principal diferencia entre Git y GitHub es que Git es un sistema de control de versiones y GitHub es una plataforma que utiliza Git y añade características colaborativas y de integración continua.

#### Comandos Básicos de Git:

**Explica los siguientes comandos de Git:**

- **`git init`**: Inicializa un nuevo repositorio de Git en el directorio actual.
- **`git clone [URL]`**: Clona un repositorio existente desde una URL a tu máquina local.
- **`git status`**: Muestra el estado de los archivos en el directorio de trabajo y el área de preparación.
- **`git add [archivo]`**: Añade un archivo específico al área de preparación.
- **`git commit -m "[mensaje]"`**: Registra los cambios en el repositorio con un mensaje descriptivo.
- **`git push [nombre-remoto] [rama]`**: Envía los commits locales a la rama remota especificada.
- **`git pull [nombre-remoto] [rama]`**: Descarga y fusiona los cambios desde el repositorio remoto a la rama local.
- **`git branch`**: Muestra una lista de todas las ramas locales en el repositorio.
  
#### Flujo de Trabajo Básico:

**Describe el flujo de trabajo básico en Git desde la clonación de un repositorio hasta el envío de cambios al repositorio remoto:**

1. **Clonar el repositorio:** `git clone [URL-del-repositorio]`.
2. **Navegar al directorio del repositorio clonado:** `cd [nombre-del-repositorio]`.
3. **Crear una nueva rama (opcional):** `git branch [nombre-de-la-rama]`.
4. **Cambiar a la nueva rama (opcional):** `git checkout [nombre-de-la-rama]`.
5. **Hacer cambios en los archivos del proyecto.**
6. **Añadir los cambios al área de preparación:** `git add [archivos]`.
7. **Hacer un commit de los cambios:** `git commit -m "Descripción de los cambios"`.
8. **Enviar los cambios al repositorio remoto:** `git push [nombre-remoto] [rama]`.

### Parte 2: Gestión de Repositorios y Colaboración

#### Creación y Gestión de Ramas:

**¿Cómo crear una nueva rama en Git?**
Para crear una nueva rama, se utiliza el comando `git branch [nombre-de-la-rama]`. Para cambiar a la nueva rama, se usa `git checkout [nombre-de-la-rama]`.

**¿Cuál es el propósito de utilizar ramas en un proyecto?**
Las ramas permiten a los desarrolladores trabajar en diferentes características o correcciones de errores de manera aislada. Esto facilita la colaboración y evita conflictos entre los cambios realizados por diferentes desarrolladores. Además, permite experimentar con nuevas ideas sin afectar la rama principal del proyecto.

#### Pull Requests:

**¿Qué es un pull request y cuál es su propósito?**
Un pull request es una solicitud para fusionar cambios desde una rama a otra, generalmente desde una rama de características a la rama principal (main o master). Su propósito es facilitar la revisión y discusión de los cambios propuestos antes de integrarlos al código base.

**Describe el proceso de creación y revisión de un pull request en GitHub:**

1. **Crear una nueva rama y realizar cambios.**
2. **Enviar los cambios al repositorio remoto:** `git push [nombre-remoto] [nombre-de-la-rama]`.
3. **Crear un pull request en GitHub:**
   - Navegar al repositorio en GitHub.
   - Ir a la pestaña "Pull requests" y hacer clic en "New pull request".
   - Seleccionar la rama base y la rama con los cambios.
   - Añadir un título y una descripción detallada.
   - Crear el pull request.
4. **Revisión del pull request:**
   - Los colaboradores revisan los cambios, dejan comentarios y sugieren mejoras.
   - El autor realiza cambios adicionales si es necesario.
5. **Aprobación y fusión del pull request.**

#### Conflictos de Fusión:

**¿Qué es un conflicto de fusión y cómo se puede resolver?**
Un conflicto de fusión ocurre cuando Git no puede resolver automáticamente las diferencias entre dos ramas. Esto suele suceder cuando los mismos archivos han sido modificados en ambas ramas. Para resolver un conflicto:
1. **Identificar los archivos en conflicto** utilizando `git status`.
2. **Editar los archivos en conflicto** para elegir qué cambios mantener.
3. **Marcar los conflictos como resueltos** usando `git add [archivo-resuelto]`.
4. **Hacer un commit** para completar la fusión: `git commit`.

### Parte 3: Características Avanzadas de GitHub

#### GitHub Actions:

**¿Qué son las GitHub Actions y para qué se utilizan?**
GitHub Actions es una plataforma de integración continua y entrega continua (CI/CD) que permite automatizar flujos de trabajo directamente en GitHub. Se utiliza para compilar, probar y desplegar código automáticamente cada vez que se realizan cambios en un repositorio.

#### Pages de GitHub:

**¿Cómo se puede usar GitHub Pages para alojar un sitio web estático?**
GitHub Pages permite alojar sitios web estáticos directamente desde un repositorio de GitHub. Para usar GitHub Pages:
1. **Crear un repositorio en GitHub.**
2. **Subir los archivos del sitio web estático al repositorio.**
3. **Ir a la configuración del repositorio y habilitar GitHub Pages.**
4. **Seleccionar la rama y la carpeta desde donde se publicará el sitio.**

**Describe el proceso de configuración de GitHub Pages para un proyecto:**
1. **Subir el proyecto al repositorio de GitHub.**
2. **Ir a "Settings" en el repositorio.**
3. **En la sección "Pages", seleccionar la fuente (branch y carpeta) para los archivos del sitio.**
4. **Guardar los cambios.**
5. **El sitio estará disponible en `https://[nombre-de-usuario].github.io/[nombre-del-repositorio]`**.

#### Issues y Proyectos:

**¿Cómo se utilizan los issues en GitHub para la gestión de tareas?**
Los issues son tickets que permiten rastrear tareas, mejoras, errores y solicitudes de características en un proyecto. Los desarrolladores pueden crear, asignar y etiquetar issues para organizar el trabajo y facilitar la colaboración.

**Explica cómo se puede utilizar la función de proyectos (projects) en GitHub para organizar y planificar el trabajo:**
GitHub Projects proporciona tableros Kanban para organizar y planificar el trabajo. Los issues y pull requests se pueden añadir a estos tableros, permitiendo una visión clara del estado de las tareas. Los desarrolladores pueden crear columnas (como "To Do", "In Progress", "Done") y mover los issues a lo largo del flujo de trabajo.

---

Estas son las bases teóricas necesarias para abordar el examen de GitHub para programadores web. Asegúrate de entender cada concepto y práctica para tener éxito en el examen.

### Hotkeys
- W: Yes, Continue
- A: Alt
- S: Explain
- D: Iterate, Improve, Evolve