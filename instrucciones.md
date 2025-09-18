
# Creando tu cuenta y tu primer repositorio

### Paso 1: Crea tu cuenta de GitHub
1. Ve al sitio web: Abre tu navegador y visita [GitHub.com](https://github.com/).  
2. Regístrate: Busca haz clic en **Sign up** o **Registrarse**.  
3. Completa la información: Te pedirá un correo electrónico, una contraseña y un nombre de usuario.  
   -  **Consejo importante**:  Elige un **nombre de usuario profesional** porque será público.  
4. Verifica tu cuenta: Sigue las instrucciones para verificar tu correo electrónico.  

   ¡Felicidades! Ya eres parte de la comunidad de GitHub.  

---

### Paso 2: Instala y configura Git en tu computadora
1. Descarga Git: Ve a [git-scm.com/downloads](https://git-scm.com/downloads) y descarga el instalador para tu sistema operativo 
   (Windows, macOS o Linux). .  
2. Instala Git: Ejecuta el instalador y sigue los pasos. En la mayoría de los casos, puedes dejar las 
   opciones predeterminadas..  
3. Configura tu identidad en Git:  Es crucial que Git sepa quién eres cuando haces cambios. Abre tu **Terminal**  y ejecuta los             siguientes comandos, reemplazando con tu nombre y correo electrónico: 

   ```bash
   git config --global user.name "Tu Nombre Completo"
   git config --global user.email "tu.email@ejemplo.com"
   ```

   - El `--global` significa que esta configuración se aplicará a todos tus proyectos en esta 
   computadora. Git almacenará esto en un archivo llamado `.gitconfig`.  

4. Verifica la configuración: Para asegurarte de que todo está correcto, ejecuta:  

   ```bash
   git config --global --list
   ```

---

### Paso 3: Crea tu primer repositorio en GitHub
1. Inicia sesión en GitHub: Si no lo estás, entra a GitHub.com con tu nueva cuenta.
2. Crea un nuevo repositorio: En la esquina superior derecha, busca un signo de más (+) y haz clic en 
   "New repository" (Nuevo repositorio).   
3. Completa los detalles:  
   - **Repository name:**  Dale un nombre descriptivo a tu proyecto, por ejemplo. `mi-primer-proyecto-prepa`  
   - **Description:**  Escribe una breve descripción de tu proyecto 
   - **Public/Private:** Selecciona **"Public"** (Público) para que otros puedan verlo y 
      potencialmente contribuir (¡excelente para tu portafolio!), o **"Private"** (Privado) si prefieres 
      mantenerlo solo para ti.  
   - **Initialize this repository with:**  Marca la casilla **"Add a README file"**. El archivo 
README.md es una descripción de tu proyecto y es una buena práctica incluirlo siempre. 
4. Haz clic en **Create repository**.  
5. Modifica el archivo `README.md`: añade tus datos generales y una foto tuya, la información debe 
   de estar en formato markdown.  
6. Crea un archivo `instrucciones.md`: copia  toda la información de esta actividad al archivo en formato Markdown.

   ¡Listo! Has creado tu primer repositorio en GitHub. Ahora está vacío, excepto por el archivo README.md y 
   el archivo instrucciones.md que acabas de generar.

---

### Paso 4: Clona tu repositorio en tu computadora

   Ahora, necesitamos una copia de este repositorio en tu computadora para poder trabajar en él localmente. 

1. En tu repositorio en GitHub, busca el botón verde **Code** y haz clic en él.
2. Copia la URL HTTPS: Verás una URL. Asegúrate de que diga "HTTPS" y cópiala (generalmente 
   hay un icono para copiar al portapapeles). 
3. Abre tu Terminal: En tu computadora, navega a la carpeta donde te gustaría guardar tus proyectos 
   (ej. Documentos/Proyectos). Puedes usar el comando cd (change directory), por ejemplo: cd 
   Documents/Projects.
4. Clona el repositorio: Una vez en la carpeta deseada, ejecuta el siguiente comando, pegando la URL 
   que copiaste:  

   ```bash
   git clone [PEGA_AQUÍ_LA_URL_HTTPS_DE_TU_REPOSITORIO]
   ```
   Este comando 
   descargará una copia completa de tu repositorio (incluyendo el README.md) en una nueva carpeta 
   con el nombre de tu repositorio. 

5. Entra a la carpeta del proyecto:  

   ```bash
   cd mi-primer-proyecto-prepa
   ```
   Ahora estás dentro de la carpeta local de tu repositorio. 

---

## Conceptos clave que acabas de usar:
- **Repositorio (repo):** Espacio donde se guarda tu proyecto (local y en GitHub).  
- **Rama (branch):**  En esta actividad, usamos la rama main, que es la línea principal de desarrollo de tu 
   proyecto. En proyectos más grandes, se usan múltiples ramas para trabajar en paralelo. .  
- **Commit:** Una "fotografía" de tus cambios en un momento dado, con un mensaje descriptivo.  
- **Clonar (clone):** Descargar una copia de un repositorio remoto a tu computadora.  
- **Push:** Enviar cambios confirmados desde tu repositorio local a GitHub.   
- **Pull:** Recibir los cambios más recientes desde GitHub a tu repositorio local. (Lo usarás más cuando 
   colabores).  
- **README.md:** Un archivo que describe tu proyecto, qué hace y cómo usarlo. Se usa Markdown 
   para darle formato. 
- **.gitignore:**  Un archivo especial donde listas archivos o carpetas que Git debe ignorar y no rastrear 
   (ej. archivos de configuración locales, archivos temporales). Esto ayuda a mantener tu repositorio 
   limpio..  

---
