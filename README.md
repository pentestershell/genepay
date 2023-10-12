Uso: 
   git clone https://github.com/pentestershell/genepay/
   cd genepay
   chmod +x GenePay
   python3 GenePay
   Empezar a generar el payload deseado.

   ____________________________________________________________
   

Script es un generador de payloads para diferentes tipos de lenguajes y conexiones (reverse/bind).

1. **Banner:**
   - Al inicio, se muestra un banner en la consola con el título "GenePay". Este banner tiene un fondo rojo y utiliza caracteres ASCII para darle un aspecto visual llamativo.

2. **Selección de Payload:**
   - Luego, el programa solicita al usuario que ingrese el tipo de payload que desea generar. Las opciones son: python, bash, php, ruby, powershell, y batch.

3. **Ingreso de Comando:**
   - Después, el usuario ingresa el comando deseado que se ejecutará cuando se use el payload.

4. **Nombre del Archivo:**
   - Se pide al usuario que ingrese el nombre del archivo en el cual se guardará el payload.

5. **Selección de Conexión:**
   - El usuario elige el tipo de conexión, ya sea reverse o bind.

6. **Generación y Guardado del Payload:**
   - Según las opciones seleccionadas, el programa utiliza funciones específicas para generar el payload en el lenguaje correspondiente y con la conexión especificada.
   - Luego, el payload se guarda en un archivo en una carpeta llamada "payloads" con el nombre ingresado por el usuario.

7. **Mensaje de Éxito o Error:**
   - Se imprime un mensaje indicando si el payload se ha guardado correctamente o si ha ocurrido algún error durante el proceso.

En resumen, el programa interactúa con el usuario para solicitar información sobre el tipo de payload, comando, nombre de archivo y tipo de conexión. Luego, genera un payload según estas especificaciones y lo guarda en un archivo.
