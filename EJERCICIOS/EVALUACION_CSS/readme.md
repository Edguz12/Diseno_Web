## 5. LENGUAJE CSS

Objetivo: Verificar el dominio de implementación de estilos (CSS) sobre el código html de
una página web.

Indicaciones: Pedir subrayar, encerrar en un círculo, o escribir la respuesta que
consideren correcta.

Preguntas:

1. ¿Qué significa CSS? (valor 0.25)

          a) Cascading Style Sheets
          
          
2. ¿Cuál es el HTML correcto para hacer referencia a una hoja de estilo externa?
(valor 0.25)

         
          b) <link rel="stylesheet" type="text/css" href="style.css">
          
          
3. ¿En qué parte de un documento HTML es el lugar correcto para hacer referencia a
una hoja de estilo externa? (valor 0.25)

          a) En la sección <head>
          
          
 4. ¿Qué etiqueta HTML se utiliza para definir una hoja de estilo interna? (valor 0.25)
 
         
          c) <style>
          
 5. ¿Qué atributo HTML se usa para definir estilos en línea? (valor 0.25)

         
          c) class
          
 6. ¿Cuál es la sintaxis CSS correcta? (valor 0.25)

          a) {body;color:black;}
          
          
 7. ¿Cómo se inserta un comentario en un archivo CSS? (valor 0.25)

          a) /* esto es un comentario */
         
8. ¿Qué propiedad se utiliza para cambiar el color de fondo? (valor 0.25)

          
          b) background-color
          
          
9. ¿Cómo se agrega un color de fondo para todos los elementos h1 (valor 0.25)
  
          
          b) h1 {background-color:#FFFFFF;}
          
  
10. ¿Qué propiedad CSS se usa para cambiar el color del texto de un elemento? (valor 0.25)
  
     
          c) color
  
 11. ¿Qué propiedad CSS controla el tamaño del texto? (valor 0.25
  
          
          c) font-size
         
  
 12. ¿Cuál es la sintaxis CSS correcta para poner en negrita todos los elementos p?(valor 0.25)
  
         
          c) p {font-weight:bold;}
          
  
13. ¿Cómo hacer que cada palabra en un texto comience con una letra mayúscula? (valor 0.25)
  
          
          d) text-style:capitalize
  
14. ¿Qué propiedad se utiliza para cambiar la fuente de un elemento? (valor 0.25)
  
          
          c) font-style
  
15. ¿Cómo pones el texto en negrita? (valor 0.25)
  
          
          c) font-weight:bold;
  
16. ¿Cómo se muestra un borde como este? (valor 0.25)

El borde superior = 10 píxeles

El borde inferior = 5 píxeles

El borde izquierdo = 20 píxeles

El borde derecho = 1 píxel
  
          a) border-width:10px 1px 5px 20px;
     (valor 0.25)
          
17. ¿Qué propiedad se usa para cambiar el margen izquierdo de un elemento? (valor 0.25)

          
          b) margin-left
          
18. Al usar la propiedad de relleno (padding); ¿Está permitido usar valores negativos? (valor 0.25)

            a) No
            
            
 19. ¿Cómo se selecciona un elemento con id 'demo'? (valor 0.25)
 
           
             #demo
           
            
20.¿Cómo se seleccionan elementos con el nombre de clase 'test'? (valor 0.25)

           
            b) .test
            
            
21. ¿Cómo se seleccionan todos los elementos p dentro de un elemento div? (valor 0.25)

            a) div.p
           
            
22.¿Cómo se agrupan los selectores? (valor 0.25)

            
            c) Separe cada selector con una coma
            
23. ¿Cuál es el valor predeterminado de la propiedad posición? (valor 0.25)

            a) absolute
            
            
 24.¿Cómo se hace una lista que enumere sus elementos con cuadrados? (valor 0.25)
 
            a) list-type: square;
            
            
Realiza la maquetación del siguiente ejemplo de página: (se aplica la rúbrica de la
maquetación en código html y css, valor 36)

![image](https://user-images.githubusercontent.com/91554777/166742177-b3cc2bfc-7768-42e4-b4f0-dcc2a1473935.png)

● Este ejercicio lo deberás realizar con las etiquetas de HTML5, haciendo uso de los elementos semánticos de HTML5.

● Deberás, en un bloc de notas, colocar todo el código html5 y guárdalo con extensión .html

● Lo mismo harás con el código CSS3, deberás guardar en un bloc de notas el código css3 con extensión .css.

● Guardar ambos archivos, el código html5 y css3, en una misma carpeta.

● Recuerda usar el elemento link para llamar dentro del código html5 los estilos guardados en el archivo con extensión .css.

-Hay tres imágenes que utilizarás para realizar esta actividad:
Imagen del logo institucional.
https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/assets/images/logo.svg

Imagen del vector blanco que se encuentra antes del texto “Aprende a programar”. https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero-vector.svg

Imagen paisaje de la Ciudad de México
https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero.jpg

-El texto alternativo para la primer imagen imagen debe ser “Gobierno de la Ciudad de México”


          INGRESA AQUI EL CÓDIGO HTML
          
          DOCTYPE html>
          <html lang="en">
          <head>
                    <title>EvaluacionCSS</title>
                    <link rel="stylesheet" href="css/estilos.css">
          </head>
          <body>
                    <header>

                              <img src="https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/assets/images/logo.svg" alt"logo"> 
                              <nav>
                                        <ul>
                                                  <li>
                                                            <a href="https://Residentes.com">Residentes</a>
                                                  </li>
                                                  <li>
                                                            <a href="https://Negocios.com">Negocios</a>
                                                  </li>
                                                  <li>
                                                            <a href="https://Visitantes.com">Visitantes</a>
                                                  </li>
                                                  <li>
                                                            <a href="https://Gobierno.com">Gobierno</a>
                                                  </li>
                                        </ul>
                              </nav>
                    </header>
                    <main>
                              <section>

                                        <h1>>APRENDE A PROGRAMAR EN LAS ESCUELAS DE CODIGO DE LA CDMX</h1>

                              </section>
                    </main>
                    <footer>
                              <h2>¿Quién se puede inscribir?</h2> <br>
                              <p>Cualquier persona que quiera aprender a programar código y cuente con 4-8 horas disponibles a la semana.</p> <br>
                              <p>*Menores de edad deberan entrar a las instalaciones acompañados de un adulto</p>
                    <footer>
          </body>
          </html>


          
          INGRESA AQUI EL CSS
          
          /* Aqui esta el estilo de header */
          ul { list-style-type: none;
          display: flex;
          justify-content: right;}
          a {

                    display:block;
                    padding-right: 10%;
                    color: rgb(0, 128, 0)
          }
          /*Aqui esta el main */
          main{background: url(https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero.jpg);}


           Ingresa el link a tu página del proyecto final
