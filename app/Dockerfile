FROM python:latest

# Crea el directorio de la aplicación
RUN ["mkdir", "/app"]

# Establece el directorio de trabajo
WORKDIR /app

# Copia el script y los archivos necesarios
COPY [".", "."]

# Instala las dependencias desde requirements.txt
RUN ["pip", "install", "--upgrade", "pip"]
RUN ["pip", "install", "-r", "requirements.txt"]

# Comando predeterminado para ejecutar cuando se inicie el contenedor
CMD ["/bin/bash", "./loop.sh"]