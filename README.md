# unity

Proyecto de Pong con unity.

## Crear el proyecto

Le damos a lo que tenemos por aquí y vamosa seleccionar lo importante es el template 2d que básicamente vamos a hacer el juego en 2d 

El proyecto elnombre pues le ponéis el que queráis yo los voy a poner por tutorial de hecho ya lo tengo creado así que no me dejaba ponerle el mismo nombre y seleccionar pues una localización y cuando lo tenga listo pues le das a create 
Cambiar layout de ventanas
Vamos a cambiar el layout así a mí así no me gusta trabajar tengo una distribución de ventanas que ya esté acostumbrado y que siempre pues es la que me pongo para cambiar esto lo que podéis hacer es iraquí arriba y seleccionar puede ser que vosotros se os adapte más a vuestra forma de trabajar y si bien ha visto ha bajado nunca pues yo que se lo recomiendo que voy a utilizar es la de 2 by 3.

##  Crear pelota

Dentro de nuestra ventana lo que vamos a hacer es clic derecho y darle a judíos el spritesquare y como veis pues directamente seme pone pues un cuadrado que es el quevamos a utilizar para la bola para losjugadores para las paredes para todoporque vamos a poder pues escalarlo enlos diferentes ejes y pues nos va aayudar a crear por como comentó el juegoen sí vamos a necesitar ni bajarnosninguna se ni nada va a ser todochocaron aquí en juniti así que buenogenera seguido un primer momento vamos acrear las paredes de arriba y de abajoentonces para ello vamos a laescala y vamos a colocarla en el eje x alo que sería un valor de 18 en este casoahoravamos a colocarlo en la posición 0 y 0en el eje x y y ahora lo que vamos ahacer es subirlo hacia arriba para ellolo que podéis hacer es pulsar w cuandotengáis este objeto seleccionado yentonces pues podréis moverlo en ese ejeen específico pues lo selección eyeshacia arribacomo veis aquí está pasando al mismo unacosa y es que mi ventana de came se estáescalando con lo grande que sea porejemplo si yo hago esto más pequeño másgrande como veis la escala se va un pocoa cuenca entonces 

## Cambiar resolución

Para evitar esto vamosa hacer vamos a poner una resolución quees la típica que se utiliza en pantallas que es la 16:9 que está se adapta muy bien pues ahora que es 1080 720 dos cada4 acá en ese caso que es la resolucióneste vertical y horizontal porquemantiene un aspecto de relación quecuadra en ese sentido entonces cuandocomo veis si yo creo a 18 y pongo estoen la posición de y a 4.5 queda perfectoahí en su posición de hecho es lo quevoy a hacer es ponerlo a 5 ya poner unpoco más arriba a mí me gusta más que sevea pero que tampoco me ocupe pues media pantalla esa pared perfecto 
Ahora lo que vamos a hacer es en vez de crear otro objeto nuevo es duplicar este que tenemos y ponerlo pues abajo del todo para ello pues lo que podéis hacer es control de o clic derecho duplicate se duplicará y ahora lo único que tenemos que hacer es en vez de ir arrastrando lo va a estar en la posición contraria a 5 en este caso pues sería menos 5 a esta 

## Paredes de los lados

Ya tengo los dos colocados perfectamente ahora vamosa crear las paredes de los datos para ello pues igual voy a este objeto voy a duplicarlo y ahora lo que pasa esque mi escala en el eje x no va a ser sino que va a ser en el eje y entonces en este caso puedo dejar la escala en el eje x a1 y la escala en el eje y a 10 así pues me quedara más o menos de una manera decente para moveros dentro de la escena si pasáis lo que sería la rueda del ratón en el medio pues lo podéis hacer una especie de paneo también bueno comentaros que si a lo mejor no sabe mucho de unity tampoco estudian en este tutorial yendo muy lentamente en ese sentido así que pues tengo una serie específico de juniti desde principio que os dejaré bleeckere en la descripción y una tarjetita pues si queréis empezar por ahí comentó que este tutorial pues no va a ser muy complicado así que si os vais que podéis ir tranquilamente con el tutorial pues ánimo a heidi y a tope vale hemos creado esta pared 
Ahora lo que quedaría es ponerlo a la derecha y ala izquierda entonces en este caso lo que vamos a hacer es poner en la posición de y a 0 y aquí vamos a modificar la posición en el eje x en este caso la podemos poner por ejemplo en ocho y más o menos vemos que se queda cerca de lo que sería pero estas paredes no se tienen que ver tienen que estar por la parte de fuera 
Vamos a colocar pues por ejemplo ahí lo quesería pues yo creo que el nueve y medio va bien estas paredes van a ser diferentes a esta nueva entre colisión en el hecho de que no van a hacer que rebote la pelota sino que cuando colisionan con esta pared va a ser como la portería de un jugador o del otro y entonces pues se añadirá un punto cuando colisiones perfecto ahora entonces con esto que tenemos aquí podemos duplicarlo y ponerlo en el lado contrario que simplemente poniéndole un negativo en el9 menos 5 o sea en el 9,5 pues se pondrá justo en el otro lado 
Nombrando los objetos
Ahora importante nombrar las cosas porque vamos a empezara tener aquí 80 objetos y nos vamos a saber que es ninguno y luego la hora de programar pues vamos a tener un quebradero de cabeza 
Para ordenar esto un poco vamosa seleccionar esta pared y hacéis doble clic o con F2 podéis nombrar lo íbamos a llamarle en goal1 porque va a ser la portería en la que tiene que colar el jugador 1 que va a estar a nuestra izquierda esto es pues si simplemente ha venido a organizarse que tengo para luego programar pero bueno pues sólo podéis nombrar como queráis como si queréis llamar de portería del número 1 o algo del estilo o portería del 2 pero luego acordaros de que hay que hacer pues seleccionar esa portería para que cuando cual el otro se suma un punto no sé qué bueno abriremos viendo tranquilamente así que no creo que preocupéis entonces 
Este otro lado de la izquierda pues sería goal2 adiós con lage mayúscula perfecto porque íbamos a pasar a hacerla línea del centro un poco para que sepamos cuál es el centro todo lo que puedes hacer es duplicar un gol que tenéis vosotros aquí colocado en la posición 0 0 y ahora es reducir un poco la escala en el eje x podéis reducir la escala también pulsando la r teniendo seleccionado huevas y entonces sancionando vuestro jugador y pulsando deseos pondrá aquí lo que sería el ritmo de escala que es lo que tenéis aquí arriba mismo de movimiento rotación escala y luego otro raro que tienen por aquí que es de escala rotación movimiento todo y vamos para ir a colom seleccionar es el de rotación y vamos a reducir esto como es si yo cojo lo quees el eje rojo y lo reduzco o el aumento pues ese aumento se reduce y se ve reflejado en la escala aquí en x vamos a colocarlo a 0 con 2 creo yo creo que ahí va guay 
## Creando los jugadores
Vamos a crear los players entonces vamos a hacer control de sobre ese amigo aquí de la derecha lo voy a arrastrar a esta posición que de hecho lo vamos a poner en la posición 8 y ahora hay que reducir la escala. Así imaginaros que vuestro player es así de grande en 3 cuando venga la bola va a rebotar sí o sí qué gracia tiene estejuego por ninguna 
## Crear jugador 2
Vamos a reducirlo unpoco a lo que sería en el eje y a 2.5 luego pues podemos modificar elmovimiento de la velocidad de la bolapodemos modificar muchas cosas pues paraque se adapte a lo que cada uno puesesté buscando en este caso como está ala derecha pues lo llamaremos player2.

## Crear jugador 1

Ahora **Ctrl+D** y duplicamos y lo llevamos a la posición contraria que sería -8 y le llamamos player1 para tenerlo ahí bien diferenciado.

Ahora lo único que ayudaría sería pues nuestra pelota del medio así que podemos hacer directamente clic derecho dentro de nuestro unit y su día dietsprite square y si la colocamos en el 0,0.

Para poder diferenciar lo mejor vamos a cambiarle el color y esto lo podéis hacer con todos los objetos en verdad que tengáis en la escena como veis son de tipo sprite renderer por tanto si lo seleccionas podéis modificar aquí el color con lo que tenéis a la derecha.

Yo lo puedo poner pues este color amarillento a la pelota y sin soluciones cualquier otro por ejemplo podéis solucionar asaco y mirar puedo modificar pues todo el mapa en sí de hecho lo vamos a hacer voy a seleccionar el goal escuela y demás y lo vamos a poner en un tono rojizo 

Ahora podéis seleccionar vuestro player2 le ponéis otro color. Voy a ponerle un tono verdoso lo mejor paraje verde parece que es como otro no puedo colocar creo que voy a dejar blanco me está gustando más blanco lo voy a dejarblanco los dos pero bueno: 

## Colisiones

Ahora mismo estos objetos que tenemos aquí simplemente tienen una posición en nuestro mundo y un componente para visualizarlos. Vamos a agregarles colliders a nuestros objetos. Los colliders son  componentes que se añaden a estos objetos 

Para que tengan colisiones vamos a seleccionarlos todos. Podéis seleccionar el primer elemento y con shift pulsado seleccionamos el último y se seleccionarán todos los que tengáis pues desde el primero hasta el último básicamente 

Si que no queréis que alguno por ejemplo en mi caso no que recoger la línea del centro porque no quiero que tenga esa colisión porque imagino que tenemos la bola aquí y conexiones con el centro y puesto que no tendría sentido básicamente porque a lo mejor si vengo desde aquí y colisionó colisión colisión y comisionó mi player uno va a ganar otro rato porque no puede pasar para allá entonces lo que sí vamos a hacer es nombrarlo para que sepamos qué es el centro que en este caso por estirando cuenta que es el goal 2 llamamos centro y a este es al que no tenemos que añadirle colisión.
Seleccionamos todos los demás objetos, añadir componente y añadimos un bosco leite de 2d que sé que tenemos por aquí así pues ya tendrán colisiones.

## Rigid bodies

Ahora tenemos que tener otra cosa que son rigid bodies para nuestros players y para nuestra pelota que se encargará del tema de física para el movimiento.
Vamos a seleccionar nuestro player y nuestra bola que de hecho la bola vamos a renombrar la vamos a poner la bola seleccionamos todos en el componente rigidbody 2D y ahí le añadimos.

Si dejamos esto así tal cual cuando yo le diera el play vais a ver qué pasa como veis mis elementos se han caído.  Tienen física funcionan pero tienen gravedad y eso pues no lo queremos.

Lo que tenemos que hacer es dentro de nuestro componente rigidbody  donde pone gravity es que a uno vamos a ponerlo a 0 y así ya no se caerán.
Recolocar la línea del centro por debajo de la pelota
Otra cosa que modificando que a lo mejor les ocurre es que la línea del centro se está dibujando por encima de nuestra pelota yeso pues la verdad que no queda muy buena lo mejor sí a lo mejor lo queréis vale pues lo dejáis lo dejáis así si os gusta pues lo dejáis pero si no lo que podéis hacer es se detiene al puesto al bola yen el elemento sprite renderer en el orden y léger le podéis poner un box por ejemplo
Esto sirve para diferenciar la altura a la que se dibujan las diferentes elementos dentro de nuestra pantalla porque ahora mismo son todo imágenes entonces para saber diferenciar cuál está por delante de una de otra utilizamos el orden y léger. En este caso pondré puesto un 2 ya se dibuja por encima así que así no habrá problema.
Movimiento de personajes
Ahora vamos a pasar directamente a lo que sería el tema de los movimientos de nuestros personajes. Vamos a hacerlo con:

- Teclas W y S para el jugador 1 (izquierda)
- Teclas flecha de arriba y hacia abajo para el jugador 2 (derecha)

De este modo, podremos jugar dos jugadores en el mismo teclado.

## Redefinir controles

Tenemos que definir pues esos controles y para ello nos vamos a ir a edit > project settings y donde tenemos input manager tenemos declarado varias cosillas que si no lo vais a expandir el axis y estos son como short cuts o controles que tiene definido djinnit y para diferentes teclas de nuestro teclado en este caso tenemos horizontal que se encarga de saber cuándo estamos pulsando a la izquierda o derecha de las flechas o el add de nuestro teclado que son las típicas teclas que se utilizan para jugar wsb y las flechas de abajo a la derecha entonces pues con esto sabrá cuando llamemos a la horizontal pues si estamos yendo hacia la izquierda o hacia la derecha pasó lo mismo con arriba o abajo pero en este caso tendríamos el ws y la flecha de arriba y hacia abajo entonces tenemos el vertical y tendremos que crear el vertical 2 que es para nuestro jugador 2 y tenemos que diferenciar pues que uno utilice el ws y el otro utilice la flecha hacia arriba y hacia abajo espero que me haya explicado lo mismo escribano con el culo pero bueno podéis seguir tranquilamente con el vídeo y pues si no queda claro pues lo vamos a ir viendo y seguramente que se entienda entonces seguramente a vosotros os haga aquí down y up y w no y yo salgo aquí s&w y esto es porque el vertical ya pilla directamente tanto la parte izquierda de teclado como la de la derecha pero aquí lo tenemos que diferenciar entonces lo vais a hacer esdel vertical vais a borrar el sw que tenemos aquí y lo que vamos a hacer es duplicarlo para tener un vertical 2 para nuestro jugador 2 en cáceres clic derecho duplicate a ride element y se duplicará que vendrá por aquí otra como vertical y entonces le vamos a hacer este más blog vertical 2y entonces ahora aquí lo que faltaría es cambiarle los controles si ni si el playero uno juega con la flecha de arriba y hacia abajo nosotros con el jugador 2 jugaremos con la s w entonces en negativo button tenéis que poner ese y en positivo ton tenía que poner w ycon eso cuando pasemos al código será muchísimo más sencillo porque además sólo tendremos que hacer un script para los dos players 

## Script de programación

Vamos a organizar esto un poquillo y dentro de nuestra carpeta assets vamos á hacer clic derecho y folder que vamos a llamar scripts y así tendremos guardados todos nuestros programas en esta carpeta.

Ahora vamos a pasar a crear nuestro script vamos aquí a entrar a la carpeta que acabamos de crear y vamos a hacer clic derecho create C# script. A este script le vamos a llamar players. Podríamos abrirlo y vamos a utilizar el programa visual studio.
