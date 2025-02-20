# Lectura-de-Archivos-con-CURL

Script de Lectura de Archivos con URL
Este script en Bash permite leer el contenido de archivos especificados a través de una URL usando curl y maneja la salida de forma colorida y amigable.

Descripción
El script realiza una solicitud HTTP GET a una URL proporcionada junto con el nombre de archivo, y muestra el contenido del archivo de forma colorida. Además, incluye una función para manejar la salida con Ctrl+C y un panel de ayuda.

Requisitos
Tener Bash instalado.

Tener curl instalado.

Uso
Clona el repositorio:

bash
git clone <URL_del_repositorio>
cd <nombre_del_repositorio>

Asigna permisos de ejecución al script:
bash
chmod +x leer_archivo.sh

Ejecuta el script con la ruta del archivo y la URL del servidor:
bash
./leer_archivo.sh -f <ruta_del_archivo> -u <url_del_servidor>

Para mostrar el panel de ayuda:
bash
./leer_archivo.sh -h
