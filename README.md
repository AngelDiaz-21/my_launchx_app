# Semana 3 - Proyecto 1: Creación de Proyectos en JS

1. Crear nuevo proyecto de JS
Así como directorios y archivos para organizar nuestro código. Así como inicializaremos nuestro proyecto JavaScript con el comando *`npm init`*, dando como resultado la creación del archivo *package.json*
![Directorio de nuestro proyecto](./assets/directorio.png "Directorio del proyecto")
2. Agregar dependencias
En el archivo package.json se agregarán las dependencias necesarias, en este caso solo utilizaremos jest. Así que haremos uso del comando *`npm install --save-dev jest`*. (Esto indica que se agrega la dependencia jest, y que se agrega para el ambiente de desarrollo --save-dev). Así como también se creara la carpeta *`node_modules`*.
3. Creación de una clase y modularización
En las carpetas app se creará un archivo *missionCommander.js* y así como una clase *MissionCommander* junto a su constructor donde solo recibirá un parámetro y lo agregue en el atributo *name*. Y se exportará la clase.  
![Class missionCommander](./assets/class-MissionCommander.png "Directorio del proyeco")