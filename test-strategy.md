PLAN DE ATAQUE

El primer error que se encontró es en esta línea de código const lowOrHi = document.querySelector('lowOrHi'); en donde se está asignando a la variable lowOrhi el elemento html que tiene la clase lowOrhi pero en su sintaxis le hace falta un punto (.) .lowOrhi

El siguiente error se encontró en la línea guessSubmit.addeventListener('click', checkGuess); 
en donde hay un evento que se le está asignando al botón gessSubmit pero el evento addEventListener estaba escrito de manera incorrecta; addeventListener y debió escribirse como addEventListener

El siguiente error está en la línea randomNumber = Math.floor(Math.random()) + 1;
en donde math.random() solamente está generando un número aleatorio de 0 a 1 y a ese número se le está sumando un numero 1, lo cual no cumple la condición de generar numeros de 1 a 100, por lo que es necesario multiplicarlo por 100 quedando de ésta forma: randomNumber = Math.floor(Math.random() * 100) + 1;

Los siguientes mensajes: Pérdistes debe de mosrarse en color rojo y está en color negro; Felicitaciones! adivinaste el número! debe de mostrarse en color verde y se mostraba en color rojo; Incorrecto! debe de mostrarse en color se estaba mostrando en color verde y debe de mostrarse en color negro. 