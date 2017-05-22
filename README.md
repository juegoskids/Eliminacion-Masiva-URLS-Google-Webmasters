#Extensión para Google Chrome para eliminar de forma masiva URLS en Google Webmasters
##Instalación
1. Descarga la extensión de Github y descomprímela.
2. Ver a **chrome://extensions/** y habilita modo de Desarrollo.
3. Clic en **Load unpacked extension . . .** y carga la extensión.

##Uso
1. Crea una lista de las URLS que vayas a eliminar y guarda el archivo (en formato .txt), una URL por renglón.
2. Entra a Google Webmasters.
3. Clic en Índice de Google -> Eliminación de URL
4. Verás un Drop-Down donde hay diferentes opciones a escoger (Eliminación de caché, eliminación de directorio, eliminación de los resultados de búsqueda y de la caché), junto al botón de "Seleccionar archivo".
5. Clic en el botón "Seleccionar archivo".
6. Selecciona el archivo creado en el paso 1. En el caso de [JuegosKids](http://www.juegoskids.com/) seleccionamos las URL que se duplicaron al probar un plugin de traducción automática, no realizó la traducción correctamente y generó cientos de URLS duplicadas todas con el mismo contenido, solo cambiando la URL por la versión del idioma que debería traducir, por ejemplo EN, DE, IT, PT... En resumen, jamás usen traductores automáticos ni siquiera para probarlos en su website, la opción adecuada es usar WPML y traducir el contenido manualmente.

##Este script fue desarrollado por https://github.com/noitcudni
