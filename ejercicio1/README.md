1. Abrir la consola e imprimir la ubicación actual.: ctrl + shift + ñ
   pwd
   /c/Users/yuran/m-i-rS2

2. Crear una carpeta llamada ejercicios desde la consola: mkdir ejercicios

3. Cambiar la ubicación a la nueva carpeta que crearon: cd ejercicios

4. Abrir la carpeta con VSCode: code .

5. En VSCode crear una carpeta ejercicio1: Al lado del nombre del proyecto EJERCICIOS doy click sobre new folder
   luego en la terminal doy git status
   On branch master

No commits yet

Untracked files:
(use "git add <file>..." to include in what will be committed)
ejercicio1/

nothing added to commit but untracked files present (use "git add" to track)

6. Crear un archivo llamado README.md (vacío) dentro de la carpeta ejercicio1.: Me ubico sobre el proyecto y doy click en new file

7. Configurar nombre e email globalmente en git:
   git config --global user.name Yurani Estrada
   git config --global user.email tyuranie@gmail.com
   y verifico mediante git config -l

8. Inicializar el repositorio de git desde la línea de comandos desde la carpeta ejercicios
   git init

9. Crear un primer commit con el mensaje “Versión Inicial”.
   git add .
   git commit -m 'Versión Inicial'
