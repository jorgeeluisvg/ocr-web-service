
# OCR-Web-Service

Mediante el uso de la herramienta Optical Character Recognition(OCR)
Se busca generar un codigo el cual nos permita que ingresemos un PDF y mediante los procesos de escaneo del archivo, convertirlo a imagen, escanear dicha imagen y usando ciertos parametros extraer el texto guardandolo en un archivo .txt


## Caracteristicas

* **Extracción de Texto Utilizando OCR:** Mediante el uso de EasyOCR, comunmente para la extracción de texto desde imágenes y documentos escaneados.

* **Soporta Diversos Formatos de PDF:** Por el uso de la herramienta 'Fitz' se pueden ingresar diversos formatos de PDF, como los que contienen imagenes o capas multiples.

* **Preprocesamiento de Imágenes:** Con la biblioteca 'Pillow' nos ayuda a optimizar la imagen antes de la extracción de texto, mejorando la precisión del OCR.



## Tecnologías Utilizadas para este proyecto

**EasyOCR:** Modulo de Phyton utilizado para extraer texto desde imagenes.

**Phyton:** Lenguaje de programación utilizado en el proyecto.

**Pillow:** Utilizado para la manipulación de imagenes en Phyton.

**Fitz:** Utilizado para la manipulacion de archivos a nivel codigo.


## Instalacion
[PARA ENTORNOS UBUNTU LINUX]

  1. Clona el repositorio desde [GitHub](https://github.com/jorgeeluisvg/ocr-web-service).
  2. Instala las dependencias necesarias con **pip3 install -r requirements.txt**.
  3. Ejecuta el script con el comando **python3 -m uvicorn server:app --reload**.
  4. El resultado de la ejecucion se mostrara en consola o en un archivo de salida especificado.

  [PARA ENTORNOS NO UBUNTU]
  1. pip3 install fastapi
  2. pip3 install python-multipart
  3. pip3 install uvicorn
  4. pip3 install pydantic
  5. pip3 install opencv-python-headless
  6. pip3 install easyocr
  7. pip3 install PyMuPDF

    
## Autores

- [@jorgeeluisvg](https://github.com/jorgeeluisvg)
- [@BrianPina2002](https://github.com/BrianPina2002)
- [@alejandronunezq](https://github.com/alejandronunezq)
- Esmeralda Solano Basurto


