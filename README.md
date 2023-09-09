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
![Imagen de cómo clonar un repositorio]([[https://drive.google.com/file/d/1-dsHYenf3qD8Q2HGAAkBlyI2cZYGHjXJ/view?usp=drive_link](https://drive.google.com/drive/u/1/folders/1CmL7lVrYRPYCITqVzyrnVPLXfma7b6H-)](https://drive.google.com/file/d/1-dsHYenf3qD8Q2HGAAkBlyI2cZYGHjXJ/view?usp=sharing))

3. **Cambiar al directorio del repositorio**:
   - Una vez clonado el repositorio, cambia al directorio del mismo con el comando:
     ```
     cd The_big_proyect
     ```

4. **Cambiar a una rama existente o crear una nueva**: 
   - Si la rama ya existe y deseas cambiar a ella:
     ```
     git checkout [nombre_de_la_rama]
     ```
   - Si deseas crear una nueva rama y cambiar a ella:
     ```
     git checkout -b [nombre_de_la_rama]
     ```

5. **Verificar el estado de tus cambios con `git status`**: 
   - Antes de hacer cualquier operación, es una buena práctica verificar el estado de tus cambios. En la terminal, ingresa:
     ```
     git status
     ```

6. **Hacer y guardar cambios**: 
   - Realiza tus cambios en el código.
   - Asegúrate de guardar esos cambios en el editor.
   - Una vez listo, en la terminal, ingresa:
     ```
     git add .
     git commit -m "Mensaje descriptivo"
     ```

7. **Subir cambios a la rama en GitHub**: 
   - En la terminal, ingresa:
     ```
     git push origin [nombre_de_la_rama]
     ```

8. **Crear un Pull Request en GitHub**: 
   - Ve a tu repositorio en GitHub.
   - Selecciona la rama que acabas de subir desde el menú desplegable de ramas.
   - Haz clic en "New pull request".
   - Selecciona la rama base (por lo general `main` o `master`) y la rama de comparación (tu rama).
   - Revisa los cambios y, si todo está bien, haz clic en "Create pull request".
   - Una vez que el Pull Request haya sido revisado, puedes fusionarlo en la rama principal desde la interfaz de GitHub.

9. **Obtener actualizaciones**: 
   - En la terminal, ingresa:
     ```
     git pull origin [nombre_de_la_rama_principal]
     ```

10. **Git Bash**: 
   - Git Bash es una aplicación para Microsoft Windows que proporciona una emulación de la interfaz de línea de comandos de Git. Puedes usarlo en lugar de la terminal integrada de VS Code si prefieres una experiencia más cercana a la de una terminal Unix.



