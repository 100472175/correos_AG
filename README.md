# correos_AG

Moodle antes tenía una opción para descargar todos los correos de un curso, pero ahora no está disponible.
Este script te permite descargar todos los correos de un curso de AG.

## Requisitos
- Python 3
- pip
```pip install -r requirements.txt```
- Excel

## Uso
1. Ve a AG y selecciona con el ratón, desde la página de lista de clase, todos los usuarios.
2. Copia y pega en el excel links.xlsm (en la hoja 1)
3. Ve a la hoja 2 y pulsa el botón de generar
4. Guarda el archivo como xlsx y dale el nombre que quieras.
5. Ejecuta el script de python
```python main.py <nombre del archivo.xslx>```
6. Espera a que termine y ya está


## Notas
Este programa modifica la columna al lado del nombre de la persona a la vez que al finalizar, genera un txt con todos los correos.
- El script no es perfecto, puede fallar en algunos casos, pero en la mayoría funciona.
- Si falla, puedes volver a ejecutarlo y no debería haber problema.
# correos_AG
