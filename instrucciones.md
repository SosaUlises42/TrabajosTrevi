# Actividad - Git y GitHub

## Creando tu cuenta y tu primer repositorio

### Paso 1: Crea tu cuenta de GitHub
1. Ve al sitio web: [GitHub.com](https://github.com/).  
2. Regístrate: Haz clic en **Sign up** o **Registrarse**.  
3. Completa la información: correo electrónico, contraseña y nombre de usuario.  
   - 💡 Consejo: Usa un nombre profesional porque será público.  
4. Verifica tu cuenta: Sigue las instrucciones en tu correo electrónico.  

✅ ¡Listo! Ya eres parte de la comunidad de GitHub.  

---

### Paso 2: Instala y configura Git en tu computadora
1. Descarga Git: [git-scm.com/downloads](https://git-scm.com/downloads).  
2. Instala Git: Ejecuta el instalador con las opciones predeterminadas.  
3. Configura tu identidad en Git:  

   ```bash
   git config --global user.name "Tu Nombre Completo"
   git config --global user.email "tu.email@ejemplo.com"
   ```

   - `--global` aplica esta configuración a todos tus proyectos.  
   - Se guarda en el archivo `.gitconfig`.  

4. Verifica la configuración:  

   ```bash
   git config --global --list
   ```

---

### Paso 3: Crea tu primer repositorio en GitHub
1. Inicia sesión en GitHub.  
2. Crea un nuevo repositorio (**+ → New repository**).  
3. Completa los detalles:  
   - **Repository name:** ej. `mi-primer-proyecto-prepa`  
   - **Description:** opcional  
   - **Public/Private:** según prefieras  
   - **Initialize this repository with:** activa la opción *Add a README file*.  

4. Haz clic en **Create repository**.  
5. Modifica el archivo `README.md`: añade tus datos generales y una foto tuya (en formato Markdown).  
6. Crea un archivo `instrucciones.md`: copia la información de esta actividad en formato Markdown.  

---

### Paso 4: Clona tu repositorio en tu computadora
1. En tu repositorio en GitHub, haz clic en el botón verde **Code**.  
2. Copia la URL HTTPS.  
3. En tu computadora, abre la terminal y navega a la carpeta donde guardarás tus proyectos:  

   ```bash
   cd Documents/Projects
   ```

4. Clona el repositorio:  

   ```bash
   git clone https://github.com/tu-usuario/mi-primer-proyecto-prepa.git
   ```

5. Entra a la carpeta del proyecto:  

   ```bash
   cd mi-primer-proyecto-prepa
   ```

---

## Conceptos clave
- **Repositorio (repo):** Espacio donde se guarda tu proyecto (local y en GitHub).  
- **Rama (branch):** Línea de desarrollo. Por defecto se usa `main`.  
- **Commit:** Una "fotografía" de tus cambios con un mensaje descriptivo.  
- **Clonar (clone):** Descargar un repositorio remoto a tu computadora.  
- **Push:** Enviar tus cambios desde el repositorio local a GitHub.  
- **Pull:** Obtener cambios recientes desde GitHub.  
- **README.md:** Archivo que describe tu proyecto (en formato Markdown).  
- **.gitignore:** Lista de archivos o carpetas que Git debe ignorar.  

---
