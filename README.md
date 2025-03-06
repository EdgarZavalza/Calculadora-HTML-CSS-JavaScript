# Calculadora-HTML-CSS-JavaScript
Tarea de una calculadora web, hecha con HTML, cas y JavaScript 

Zavalza Covarrubias Edgar Enrique #22400695
https://github.com/EdgarZavalza/Calculadora-HTML-CSS-JavaScript/tree/main

1) Que hace document.querySelector(".display"); ?
Se selecciona el elemento HTML que tiene la clase "display" y lo guarda en una variable para poder manipularlo. En este caso, se usa para mostrar los resultados de las operaciones en la calculadora.

2) Que hace const buttons = document.querySelectorAll("button"); ?
Selecciona todos los elementos <button> de la página y los guarda en la variable buttons. Estos botones serán usados como entrada para la calculadora.

4) Que hace buttonText = button.textContent; ?
Se guarda en la variable buttonText el texto (número o símbolo) del botón que fue presionado.

5) Que hace y como funciona buttons.forEach((button) => { ...} ?
Ejecuta un bloque de código para cada botón dentro de la lista buttons. Se usa para recorrer todos los botones y asignarles acciones, como detectar clics.

6) Que hace y como funciona button.addEventListener("click", () => { } ) ?
Se le da un evento de clic a un botón. Cuando el usuario haga clic en el botón, se ejecutará el código dentro de { }. Esto permite que la calculadora detecte qué botón fue presionado y realice una acción.
