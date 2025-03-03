
# Generación y Uso de Clave SSH para GitHub

Este repositorio fue creado con la intención de recordar cómo hacer la clave SSH y usarla en GitHub.

## Paso a paso:

1. Crear la llave pública con el formato OpenSSH:
   ```sh
   ssh-keygen -t rsa -b 4096
   ```

2. Guardar la llave en el archivo:
   ```sh
   ~/.ssh/id_rsa
   ```
   (Es decir, le decimos sobre-escribir)

3. Leer el contenido de la llave generada:
   ```sh
   cat ~/.ssh/id_rsa.pub
   ```

4. Agregar la llave SSH a nuestra configuración de GitHub.

5. Clonar el proyecto utilizando SSH.
