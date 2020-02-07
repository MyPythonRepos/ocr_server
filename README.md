# APLICACIÓN OCR CON PYTHON

Ejemplo de aplicación en Python, basado en el artículo publicado en [Instinto Programador](https://www.instintoprogramador.com.mx/2019/06/pytesseract-reconocimiento-optico-de.html).

## Entorno

+ Ubuntu 19.10
+ Python 3.7.5

## Requerimientos

Procedemos a instalar el motor de Google [Tesseract-OCR](https://github.com/tesseract-ocr/tesseract):

+ sudo apt install tesseract-ocr
+ sudo apt install libtesseract-dev

A continuación, instalamos la librería para Python pytesseract:

+ sudo pip3 install pytesseract

Necesitaremos instalar Flask para crear una interfaz web:

+ sudo pip3 install flask
