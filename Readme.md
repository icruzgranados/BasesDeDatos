# Instrucciones para instalar la extensión EER en Dia

## Paso 1: Descargar y copiar el archivo ZIP
- Descarga el archivo `EER.zip`.
- Copia el archivo descargado `EER.zip` a la subcarpeta `.dia` en tu directorio de usuario. Esta subcarpeta se crea automáticamente tras la primera ejecución de Dia.

  - **En Windows**: La ruta podría ser algo como `C:\Usuarios\[tu_nombre_de_usuario]\.dia\`.
  - **En Linux**: La ruta sería `/home/[tu_nombre_de_usuario]/.dia/`.
  - **En macOS**: La ruta sería `/Users/[tu_nombre_de_usuario]/.dia/`.

## Paso 2: Extraer el contenido del archivo ZIP
- Ve a la carpeta `.dia` donde copiaste el archivo `EER.zip`.
- Extrae el contenido de `EER.zip` en esta carpeta.

  Puedes hacer esto utilizando una herramienta de descompresión (como WinRAR, 7-Zip, etc.) o usando comandos en la terminal.

  - **En Windows**: Haz clic derecho en el archivo y selecciona "Extraer aquí".
  - **En Linux y macOS**: Abre una terminal y usa:
    ```bash
    cd ~/.dia
    unzip EER.zip
    ```

## Paso 3: Verificar el contenido extraído
- Asegúrate de que se hayan generado las dos carpetas `shapes` y `sheets`, y un nuevo archivo `LICENSE`.

## Paso 4: Reiniciar Dia
- Si Dia estaba abierto durante este proceso, ciérralo y vuelve a abrirlo para que cargue las nuevas extensiones.

## Paso 5: Seleccionar la nueva hoja de herramientas
- Una vez que hayas reiniciado Dia, deberías poder ver y seleccionar la nueva extensión. Debajo de las herramientas, selecciona `Otras hojas` y luego `ERE`.

---

Siguiendo estos pasos, deberías poder instalar correctamente la extensión `EER` en Dia. Si encuentras algún problema, asegúrate de que el archivo ZIP se haya extraído correctamente en la carpeta `.dia` y que los archivos estén en las ubicaciones correctas.
