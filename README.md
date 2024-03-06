Pasos para subir un flow y un custom field a Github

1. Preparar playground

Crear un custom field para algún objeto

Crear un flow que incluya el custom field

Crear un paquete nuevo que incluya un flow definition

2. Crear el proyecto

Usar SFDX: create project with manifest para crear el proyecto y seleccionamos que sea empty para no tener archivos que no nos sirven.

Modificar el archivo package.xml para solo incluir las partes que usa nuestro flow

Recuperar la información desde nuestra Org

3. Subir a Github

Iniciar un repositorio en nuestra carpeta

Crear un gitignore para los archivos sf y sfdx

Hacer un commit

Publicar en Github
