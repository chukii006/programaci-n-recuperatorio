1. Js es un lenguaje interpretado o compilado? Justifica tu respuesta

Es un lenguaje interpretado porque su codigo es ejecutado directamente



2. En el index.html vincula el archivo helpers.js antes que el game.js, debe llevar ese orden preciso? Justifica tu respuesta. (Prueba invirtiendo las líneas de vinculación html con js)

Si debe ser en orden preciso, en el archivo "help"  hay variables definidas que se usan en el archivo "game" Y al ser JavaScript interpretado, lee linea por linea y carga el primer archivo que lee.



3. Si definimos una imagen de 600 x 600 px, realiza los cambios que correspondan en el código.

Deberia cambiar en el archivo "game.js" lo siguiente:
      const WIDTH= 600;
      const HEIGTH= 600;
    asi se adaptan las cordenadas del tesoro al tamaño de la imagen
     

4. Qué tipo de variable es “target”? Explica y ejemplifica

La variable   "target" es un objeto definido en el archivo "gams",  Es un objeto porque tiene dos propiedades claves definidas, las cordenadas x, y


5. Identifica 3 funciones definidas por javascript y 3 funciones definidas por el usuario (identificar y definir las funciones flecha). Explica la utilidad de cada una.

    Math.random()
     Esta funcion devuelve el primer decimal aleatorio entre 0 y 1
     - Es util en juegop porque  se usa para regenerar numeros aleatorios 
    
    document.querySelector.()
     Esta funcion devuelve el primer elemento del documento que coincide con un selector CSS especificado (id mapa y parrafo)
    
    alert()
     La alerta muestra en un cuadro un texto como en este caso la cantidad de clicks que le tomó 
    let getRandomNumber = size => {return Math.floor(Math.random() * size);}

        Esta función toma un parámetro size y devuelve un número entero random entre 0 y size - 1
        - Genera coordenadas aleatorias dentro de un rango específico

        let getDistance = (e, target) => {}
        Esto toma la distancia entre 2 puntos
        - Es útil en aplicaciones o juegos donde se necesita calcular qué tan lejos está un clic del usuario de un objetivo

    let getDistanceHint = distance => { ... };
       Esta función flecha toma una distancia y devuelve un mensaje de pista que indica qué tan cerca o lejos está el usuario del objetivo
       - Ayuda a entender que tan cerca o lejos está
     -

     son definidas por el usuario por el let define una varianle. 
6. Recordatorio: luego de subir el proyecto a Git / Github deberán compartir la URL, en un comentario de esta publicación, indicando los integrantes del grupo.


Usa const cuando sepas que el valor de la variable no cambiará.
Usa let (no mencionada pero importante) cuando el valor pueda cambiar.
var se recomienda evitar debido a sus problemas de alcance y hoisting.



propiedades y métodos.