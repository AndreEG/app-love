# CLASE PRÁCTICA
## Replicar el siguiente ejercicio
![Pagina a raplicar](assets/images/replicar.png "titulo")

### HTML
Lo primero a realizar es la maquetación HTML que tendrá un encabezado, 4 sections y un footer, dentro de los cuales se ingresará los textos e imagenes correspondientes.

```
		
//<body>
        <header>
        </header>

        <section>
        </section>

        <section>
        </section>

        <section>
        </section>

        <section>
        </section>
        
        <footer>
        </footer>
    </body>
		
```
### CSS
Al HEADER le aplicamos position FIXED y hacemos que cubra el resto de elementos mediante Z-INDEX; a los UL se les hizo flotar hacia la izquierda para que se posicionaran tal cual el ejemplo y se hace flotar al logo al lado derecho por la misma razón; a los LI se les aplico DISPLAY inline-block para que pudieran posicionarse uno al lado del otro.

Al SECTION 1 le agregamos una imagen que ocupe todo el ancho con position RELATIVE para que el resto del texto con position ABSOLUTE puedan ir sobre la imagen ya mencionada.

Al SECTION 2 se le aplico un color de fondo rosa los 2 primeros solo centrados y las siguientes cajas en con DISPLAY inline-block para que esten una al lado de la otra.

Al SECTION 3 solo se agrego texto e imagen centradas.

Al SECTION 4 se aplico la clase container para que el resultado pueda tener dimensiones fijas y overflow HIDEN para que sus elementos hijos respeten sus dimensiones, se hizo una caja por imagen la cual contenia la imagen y el texto debajo, a dicha caja se le aplico FLOAT para que flotara a la izquierda y pueda visualizarse una continua de la otra.

Al FOOTER se le dio la dimension adecuada.


