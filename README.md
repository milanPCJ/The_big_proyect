# The_big_proyect
Repositorio para organizar los códigos del proyecto

# Tutorial de Uso de Git y GitHub con Visual Studio Code
(Asegúrate de tener Git instalado en tu máquina. Si no lo tienes, puedes descargarlo desde https://git-scm.com/)
¡Olaa!, Tremendo tutorial básico para empezar:

1. **Abrir la terminal en Visual Studio Code**: 
   - Abre Visual Studio Code.
   - Ve a la parte superior y selecciona `Ver` y luego `Terminal`.
   - Esto abrirá una terminal integrada en la parte inferior de tu editor.

2. **Clonar el repositorio**: 
   - En la terminal, ingresa:
     ```
     git clone https://github.com/milanPCJ/The_big_proyect.git
     ```
   ![Imagen de cómo clonar un repositorio](link_a_imagen_de_clonar)

3. **Cambiar al directorio del repositorio**:
   - Una vez clonado el repositorio, cambia al directorio del mismo con el comando:
     ```
     cd The_big_proyect
     ```
   ![Imagen de cómo cambiar al directorio del repositorio](link_a_imagen_de_cd)

4. **Crear una nueva rama**: 
   - En la terminal, ingresa:
     ```
     git checkout -b [nombre_de_la_rama]
     ```
   ![Imagen de cómo crear una rama](link_a_imagen_de_rama)
   
5. **Hacer y guardar cambios**: 
   - Realiza tus cambios en el código.
   - Una vez listo, en la terminal, ingresa:
     ```
     git add .
     git commit -m "Mensaje descriptivo"
     ```
   ![Imagen de cómo hacer y guardar cambios](link_a_imagen_de_cambios)
   
6. **Subir cambios**: 
   - En la terminal, ingresa:
     ```
     git push origin [nombre_de_la_rama]
     ```
   ![Imagen de cómo hacer push](link_a_imagen_de_push)
   
7. **Obtener actualizaciones**: 
   - En la terminal, ingresa:
     ```
     git pull origin [nombre_de_la_rama]
     ```
   ![Imagen de cómo hacer pull](link_a_imagen_de_pull)
   
8. **Fusionar ramas**: 
   - Si necesitas fusionar tu rama con otra, primero asegúrate de estar en la rama que quieres actualizar (por ejemplo, `master` o `main`).
   - Luego, en la terminal, ingresa:
     ```
     git merge [nombre_de_la_rama]
     ```
   ![Imagen de cómo fusionar ramas](link_a_imagen_de_merge)
   
9. **Resolución de conflictos**: 
   - Si hay conflictos, Git te lo indicará. Abre los archivos con conflictos y busca las marcas `<<<<<<<`, `=======` y `>>>>>>>` para resolver los conflictos manualmente.
   - Una vez resueltos, guarda los cambios y en la terminal, ingresa:
     ```
     git add .
     git commit -m "Resuelto conflictos"
     ```
   ![Imagen de cómo resolver conflictos](link_a_imagen_de_conflictos)
   
10. **Git Bash**: 
   - Git Bash es una aplicación para Microsoft Windows que proporciona una emulación de la interfaz de línea de comandos de Git. Puedes usarlo en lugar de la terminal integrada de VS Code si prefieres una experiencia más cercana a la de una terminal Unix.
   ![Imagen de Git Bash](link_a_imagen_de_gitbash)



