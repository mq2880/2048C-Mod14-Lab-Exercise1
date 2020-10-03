# Module 14: Performing Background Processing by Using Web Workers

**Lab: Creating a Web Worker Process**

**Nombre:** Francisco Javier Moreno Quevedo

**Fecha:** 2/10/2020

**Resumen del Ejercicio:** El laboratorio se compone de un ejercicio. En el ejercicio uno se  implementa la funcionalidad del webworker para que la pagina no se congele mientras se procesa la imagen

**Dificultad o problemas presentados y como se resolvieron:** 

- Ejercicio 1
  - Se añade la funcionalidad de transformar a escala de grises la imagen
  - Se crea un webworker en el fichero grayscale.js
  - Se añade un listener 
  - Se crea la funcion que convierte los pixeles a grises
  - se añade el metodo que transforma cada pixel al webworker para que no se congele la pagina
  - se devuelve la imagen