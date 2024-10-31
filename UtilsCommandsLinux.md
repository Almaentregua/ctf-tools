# Buscar flags con strings en un archivo
strings archivo | grep -E "flag{.*}" 

# Filtrar por longitud mínima (útil para eliminar texto corto irrelevante)
strings -n 8 archivo  # Cambia el 8 por el número de caracteres mínimo deseado

# Exiftool: Extrae metadatos de archivos de imágenes y otros tipos
exiftool archivo.jpg

# Explorar el archivo en hexadecimal
xxd archivo.ext

