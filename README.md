El proyecto Desafio #7DaysOfCode almacenara los 7 proyectos diarios solucionados para mejorar la logica de JS

***** Descripcion problema Desafio #7DaysOfCode - dia 1 *****

¡Llegó la hora, Edwin! Vas a comenzar tu jornada en el #7DaysOfCode ;)

Este primer día es muy importante. Al final de él, tendrás un nuevo conocimiento que es esencial para los próximos desafíos.

Existe una situación muy común para quienes usan Javascript: problemas con los tipos de variables al comparar los valores de dos variables entre sí. ¡A mí me ha pasado mucho!

En lenguajes de programación compilados, como Java y C#, este problema se detecta en tiempo de compilación, y tienes un aviso claro del error mientras desarrollas el código.

En JavaScript, estos errores pasan desapercibidos, ya que el código no pasa por un compilador. Es decir, los errores solo aparecen en tiempo de ejecución.

La parte más confusa para quienes están comenzando a aprender lógica con JavaScript es la operación de igualdad entre valores. Dependiendo de cómo escribas tu código, JavaScript hará una conversión de tipo a un tipo booleano de manera implícita (automática), y esto afectará a variables que eran Strings, Numbers, Object, etc.

Esto causa algunos comportamientos extraños, como todos estos ejemplos a continuación que retornan true:

console.log( false == '0' );

console.log( null == undefined );

console.log( " \t\r\n" == 0 );

console.log( ' ' == 0 );

Lo cual no tiene necesariamente mucho sentido.

(Puedes probar todo esto yendo a tu navegador, haciendo clic con el botón derecho, eligiendo la opción “Inspeccionar” y la pestaña “Consola”. En esa pestaña, basta con copiar y pegar cada una de las líneas anteriores para confirmar que todas realmente retornan true).


Por lo tanto, tu tarea de hoy es reescribir el código a continuación para que imprima la información de manera correcta, que tenga sentido y sin errores:

let numeroUn = 1

let stringUn = '1'

let numeroTreinta = 30

let stringTreinta = '30'

let numeroDiez = 10

let stringDiez = '10'

if (COMPARAR numeroUn y stringUn) {

  console.log('Las variables numeroUn y stringUn tienen el mismo valor, pero tipos diferentes')

} else {

  console.log('Las variables numeroUn y stringUn no tienen el mismo valor')

}

if (COMPARAR numeroTreinta y stringTreinta) {

  console.log('Las variables numeroTreinta y stringTreinta tienen el mismo valor y el mismo tipo')

} else {

  console.log('Las variables numeroTreinta y stringTreinta no tienen el mismo tipo')

}

if (COMPARAR numeroDiez y stringDiez) {

  console.log('Las variables numeroDiez y stringDiez tienen el mismo valor, pero tipos diferentes')

} else {

  console.log('Las variables numeroDiez y stringDiez no tienen el mismo valor')

}

 CONSEJO  
También puedes utilizar el navegador para ejecutar este programa, si aún no tienes familiaridad con editores de código como Visual Studio Code.

Para hacerlo, como mencioné antes, basta con hacer clic con el botón derecho del mouse en cualquier página, seleccionar la opción “Inspeccionar”, ir a la pestaña “Consola” y escribir tu código. ¡Muy simple, verdad?

Si deseas cambiar los nombres de las variables y los valores, siéntete libre de hacerlo. Pero nunca imprimas algo que no sea verdadero, ¿eh?

 EXTRA  
He seleccionado un artículo de Alura para que aprendas más sobre operadores de comparación.

 ***** Descripcion problema Desafio #7DaysOfCode - dia 2 *****

¿Qué tal, Edwin? ¿Conseguiste resolver el desafío de ayer?

¡Estoy seguro que sí! Pero, para que te sientas con más confianza, al final de este correo te dejo cómo yo resolvería el desafío, ¿vale?

¿Sabes cuando te registras en un site y, justo después, al iniciar sesión, te llama por tu nombre? Eso es lo que harás en el desafío de hoy.

Cuando creas un sistema, site o aplicación, es común querer agregar algunos toques personalizados para hacer la experiencia en tu aplicación más rica y dinámica.

Hacer esto mediante programación puede no ser una tarea fácil. Dependiendo del nivel de personalización que quieras implementar, la cantidad de código que necesitarás escribir puede ser inmensa.

Pero, por supuesto, puedes comenzar de una manera más sencilla. Para ello, lo importante es entender cómo capturar y almacenar valores dentro de variables. ¡Y en eso te voy a ayudar hoy!

Las variables son los bloques básicos de construcción de cualquier sistema y son esenciales para procesar cualquier tipo de información, ya sea de una persona que ha iniciado sesión en el sistema o incluso para mostrar detalles de productos en un catálogo de comercio electrónico.

Por eso, hoy te voy a enseñar a desarrollar un programa simulando una de esas aplicaciones. Debe pedir al usuario responder 3 preguntas:

 

- ¿Cuál es tu nombre?
- ¿Cuántos años tienes?
- ¿Qué lenguaje de programación estás estudiando?

A medida que se hagan las preguntas, la persona que esté usando el programa debe responder cada una de ellas.

Al final, el sistema mostrará el mensaje:

"Hola [nombre], tienes [edad] años y ya estás aprendiendo [lenguaje]!"

Observa que cada información entre [ ] es una de las respuestas dadas por la persona.

 EJERCICIO OPCIONAL

Si deseas profundizar en el tema de hoy, tengo otro ejercicio para ti.

Pero es 100% opcional.

Vas a complementar el código para que, después de mostrar el mensaje anterior, el programa pregunte:

¿Te gusta estudiar [lenguaje]? Responde con el número 1 para SÍ o 2 para NO.

Y luego, dependiendo de la respuesta, debería mostrar uno de los siguientes mensajes:

1 > ¡Muy bien! Sigue estudiando y tendrás mucho éxito.

2 > Oh, qué pena... ¿Ya intentaste aprender otros lenguajes?

 CONSEJO 

Puedes agregar tantas preguntas como desees y aprovechar las respuestas de los usuarios en el mensaje que se mostrará.

Para imprimir y recibir valores, puedes usar tanto console.log, prompt y alert, como también HTML y CSS si ya tienes conocimiento en estas dos tecnologías.

Puedes usar la estructura condicional if para resolver el Ejercicio Opcional. Algo como:

if (respuesta == 1) {

    // da la respuesta positiva

}

if (respuesta == 2) {

    // da la respuesta negativa

}

  EXTRA  

Tanto alert() como prompt() se utilizan para crear cuadros de diálogo e interactuar con el usuario, pero son diferentes entre sí.

El alert() se utiliza para mostrar un mensaje simple al usuario.

Ejemplo:

alert("¡Hola, todos!");

El prompt() requiere que el usuario ingrese algún valor, que podrás manipular.

Ejemplo:

const ciudad = prompt("Escribe tu ciudad:");

const msg = `¡Eres de ${ciudad}!`;

alert(msg);

Prueba los códigos anteriores e intenta adaptarlos a tu programa.

***** Descripcion problema Desafio #7DaysOfCode - dia 3 *****

¡Ya llegaste al tercer día!

¡Sigue así!

Por cierto, ¿qué te pareció el desafío de ayer? Al final de este correo te dejo mi idea de solución y me encantaría saber la diferencia con la tuya.

¿Alguna vez has jugado un juego que te dé más de una opción y, dependiendo de lo que elijas, el destino del personaje sea completamente diferente?

Hoy vas a desarrollar un ejemplo así con Javascript.

Quiero que trabajes con estructuras de control de flujo. Esta forma complicada de decirlo significa que, al igual que en los juegos, la historia que desarrolles debe adaptarse a las respuestas dadas por quien está jugando.

Para ello, necesitarás algunas estructuras capaces de alterar el flujo de la aplicación, como for, while, if y else. Todas estas pueden cumplir con este objetivo, dada una cierta condición.

El if y el else, que ya te he mostrado en los últimos días, son capaces de crear ramificaciones dentro de la aplicación para que se tome una u otra acción, dependiendo de la condición proporcionada.

Los bucles (como for y while) son capaces de transformar una tarea repetitiva en pocas líneas de código, sin importar cuántas veces necesites repetir esa tarea.

Tu desafío de hoy es crear los destinos posibles de un juego, en el que el usuario pueda elegir:

Si quiere seguir hacia el área de Front-End o seguir hacia el área de Back-End.
 
Si está en el área de Front-End, si quiere aprender React o aprender Vue. Si está en el área de Back-End, podrá aprender C# o aprender Java.

Después, independientemente de las elecciones anteriores, el usuario podrá elegir entre seguir especializándose en el área elegida o desarrollarse para convertirse en Fullstack. Debes mostrar en pantalla un mensaje específico para cada elección.

Finalmente, pregunta en qué tecnologías le gustaría a la persona especializarse o conocer. Aquí, la persona puede responder N tecnologías, una a la vez. Entonces, mientras continúe respondiendo **ok** a la pregunta: "¿Hay alguna otra tecnología que te gustaría aprender?", sigue presentando el Prompt, para que complete el nombre de la tecnología en cuestión. Y, justo después, presenta un mensaje comentando algo sobre la tecnología ingresada.
 
Lo importante es que la persona que esté jugando siempre pueda elegir qué decisión tomar para aprender y desarrollarse en el área de programación.

Además, también es esencial que, al final del juego, pueda ingresar tantas tecnologías como desee en la lista de aprendizaje.

 CONSEJO 
Ya tienes una idea de cómo hacer que toda esta historia suceda, ¿verdad? ¡Principalmente recordando cómo usar estructuras condicionales y bucles en Javascript!

Si aún no sabes cómo imprimir y recibir valores en páginas web con HTML y CSS, puedes usar console.log, prompt y alert para desarrollar tu juego, como ya has visto en los últimos días.

Recuerda que siempre puedes personalizar el juego de la forma que desees.

 EXTRA 
Ya has visto estructuras condicionales en Javascript anteriormente, pero vamos a recapitular. El if se usa para verificar si una determinada condición es verdadera.

Ejemplo:

if (ciudad === "Roma") {

    // muestra la foto del "Coliseo"

}
Además, también puede usarse con uno o varios else if, que verificará si la condición anterior era falsa y comprobará si la actual es verdadera.

Finalmente, existe el else solo, sin ninguna condición, y el código dentro de él se ejecutará siempre que todas las condiciones anteriores encadenadas sean falsas.

if (ciudad === "Roma") {

    // muestra la foto del "Coliseo"

} else if (ciudad === "París") {

    // muestra la foto de la "Torre Eiffel"

} else {

    // da la respuesta "No escribiste una ciudad válida"

}
Además, para la parte 4, necesitarás una estructura de repetición (bucle) como el while. Para usarlo, es bastante fácil:
let edad = 0;

while (edad < 8) {

    // algún comando para imprimir la edad

    edad = edad + 1;

}

Este código comenzará con la edad en cero y, al entrar en el while, ese valor se imprimirá y, justo después, se incrementará en 1.

Es decir, después de la primera vez que pase, el valor de la edad será igual a 1, que es menor que 8, y por eso, la condición del while tendrá un resultado verdadero y continuará ejecutándose.

Solo se detendrá cuando el valor de la variable edad llegue a 8, que no es menor que 8, y por eso la condición del while tendrá un resultado falso.

***** Descripcion problema Desafio #7DaysOfCode - dia 4 *****

¡Has llegado a un nuevo día de #7DaysOfCode!

¿Y el desafío de ayer? ¿Lograste resolverlo? Como siempre, al final del correo te dejaré la solución que yo utilizaría.

¿Alguna vez has jugado a adivinar el número en el que tu amigo o amiga estaba pensando? Hoy volverás a tu infancia y harás exactamente eso. ¡Pero ahora, el juego será contra la propia computadora!

Debes crear un pequeño programa que comience con un valor específico predefinido entre 0 y 10 para el número que vas a adivinar (por ejemplo, el 7).

A continuación, el programa te preguntará cuál es el valor que deseas adivinar y, si aciertas, te felicitará. Si te equivocas, te dará 2 intentos más.

Al final, si no aciertas en ninguno de los intentos, imprimirá cuál era el número inicial.

Después de que el programa esté funcionando, intenta usar un número aleatorio en lugar de uno predefinido.

 CONSEJO 
Piensa muy bien en qué estructura de repetición utilizarás para hacer que tu programa se ejecute hasta que se agoten las 3 oportunidades o hasta que la persona acierte el número.

Recuerda que siempre puedes personalizar tu programa como desees.

No olvides compartirlo en tu GitHub y en tus redes sociales con el hashtag #7DaysOfCode.

 EXTRA 
Échale un vistazo a este site para aprender más sobre estructuras de repetición.

Para hacer que la propia máquina elija el número a adivinar, puedes utilizar algo llamado Math.random().

Para ello, utiliza el siguiente código:

Math.floor(Math.random() * (máximo - mínimo + 1) + mínimo)

Donde, por supuesto, tendrás que cambiar los valores de mínimo y máximo por los límites inferior y superior, respectivamente.


***** Descripcion problema Desafio #7DaysOfCode - dia 5 *****

¿Sabes cuando vas al supermercado con una lista de compras y terminas yendo y volviendo por los mismos pasillos hasta completar la lista?

Necesitas una manzana y vas al área de frutas. El siguiente ítem es una leche y te diriges a los lácteos. Pero luego anotaste una pera, y necesitas regresar de nuevo al área de frutas.

¡Después de resolver el desafío de hoy, con certeza no harás más eso!

Al igual que nuestra lista de compras, es muy común que los programas trabajen con listas de string, números y objetos.

Piensa en cada catálogo de e-commerce que has visto, en la lista de eventos de tu Google Calendar, o incluso en tu bandeja de entrada de correos electrónicos. Todos estos sitios utilizan listas para mostrar información de una manera simple y fácil de entender.

Además, puedes aprovechar las listas para hacer filtros, ordenaciones y otras funcionalidades muy útiles.

En este punto, ya debes haber notado que trabajar con estas colecciones es algo que necesitarás dominar, ¿verdad?

Entonces hoy, para facilitar tu visita al supermercado, debes crear un programa en Javascript que pregunte si deseas agregar un alimento a tu lista de compras, y debes poder responder con "sí" o "no".

A continuación, preguntará qué alimento deseas agregar, y escribirás su nombre, como por ejemplo "zanahoria".

Después, deberá preguntar en qué categoría se encaja ese alimento, con algunas opciones ya predefinidas, como frutas, lácteos, congelados, dulces y lo que más creas interesante. Así podrás separar todo en su respectivo grupo.

Por último, en caso de que ya no quieras agregar nada más a la lista de compras y respondas "no" a la primera pregunta, se mostrará una lista con todos los ítems agrupados, de la siguiente manera:

Si añades a tu lista:

banana, leche en polvo, tomate, leche vegetal, chicle, gominola, manzana, uva, aguacate y leche de vaca.

El programa debería imprimir, por ejemplo:

Lista de compras:
Frutas: banana, tomate, manzana, uva, aguacate
Lácteos: leche vegetal, leche de vaca, leche en polvo
Congelados: 
Dulces: chicle y gominola

 CONSEJO 
Existe un objeto dentro del lenguaje Javascript que se usa justamente para crear listas de elementos, llamado Array. ¡Úsalo y abusa de él!

Recuerda que siempre puedes estilizar tu programa de la manera que desees, incluso utilizando otras tecnologías para ello, como HTML y CSS.

Sin embargo, eso no es obligatorio en nuestra lista de lógica de programación con Javascript. Como mencioné en los días anteriores, puedes utilizar recursos como console.log, alert y prompt para desarrollar tu programa.

No olvides compartir tu código en tu GitHub y en tus redes sociales con el hashtag #7DaysOfCode.

 EXTRA 
Para crear un array vacío, puedes usar corchetes. Y luego, para insertar algo en un array, puedes usar la función .push(). Por ejemplo:

let miArray = [];
miArray.push(elemento1);

Después de eso, el array ya no estará vacío, tendrá el elemento 1.


