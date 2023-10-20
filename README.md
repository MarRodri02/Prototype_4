# Prototype_4
## Lección 4.1: Mira por dónde vas
### Descripción general: 
Primero lo primero, crearemos un nuevo prototipo y descargaremos los archivos iniciales. Notarás una hermosa isla, cielo y efecto de partículas... ¡todos los cuales podemos personalizar! Después permitirás que el jugador rote la cámara alrededor de la isla en un radio perfecto, lo cual nos permitirá tener una gloriosa vista de la Escena. El jugador se representará con una esfera envuelta en una textura detallada de tu elección. Por último, agregarás fuerza al jugador para permitir que se mueva hacia adelante o hacia atrás en dirección de la cámara.
### Resultado del proyecto:
La cámara girará de forma estable alrededor de un punto focal en el centro de la isla dada una entrada horizontal del jugador. El jugador controlará una esfera con textura y la moverá hacia adelante o hacia atrás en dirección el punto focal mencionado anteriormente.

## Lección 4.2: ¿Cómo seguir al jugador?
### Descripción general: 
El jugador puede dar vueltas hasta cansarse... pero no tiene un propósito. En esta lección, le damos ese propósito al crear un enemigo que desafíe al jugador. Primero le daremos al enemigo una textura de tu elección, después le daremos la habilidad de empujar al jugador... con la posibilidad de tirarlo por un precipicio. Por último, dejaremos que el enemigo persiga al jugador por la isla y se genere en posiciones al azar.
### Resultado del proyecto:
Un enemigo esférico y con textura se generará en la isla al inicio, en una ubicación aleatoria determinada por una función personalizada. Perseguirá al personaje por la isla y lo empujará por el precipicio si se acerca mucho. 

## Lección 4.3: Potenciador y cuenta regresiva
### Descripción general: 
El enemigo persigue al jugador por la isla, pero el jugador necesita una mejor forma de defenderse... especialmente si agregamos más enemigos. En esta lección crearemos un potenciador que otorgue al jugador un incremento momentáneo de fuerza, con el cual podrá alejar a los enemigos con los que entra en contacto. El potenciador se generará en una posición aleatoria en la isla y hará resaltar al jugador con un indicador cuando lo recoja. El indicador del potenciador y el potenciador mismo se representarán con recursos de juego del estilo que tú elijas.
### Resultado del proyecto:
Un potenciador se generará en una posición aleatoria en el mapa, donde esperará al jugador. Cuando el jugador colisione con este potenciador, el potenciador desaparecerá y el indicador hará resaltar al jugador. El potenciador durará 5 segundos después de recogerlo y dará al jugador superfuerza para alejar a los enemigos.

## Lección 4.4: «Bucles For» para oleadas
### Descripción general: 
Tenemos todos los elementos de un excelente juego: un jugador que rueda por todos lados y gira la cámara, un potenciador que otorga superfuerza y un enemigo que persigue al jugador hasta las últimas consecuencias. En esta lección daremos los toques finales al reunir todos estos elementos.
Primero mejoraremos el Spawn Manager del enemigo para permitir que genere varios enemigos e incremente la cantidad cada vez que derrotemos a una oleada. Por último, generaremos el potenciador con cada oleada para permitir que el jugador tenga oportunidad de defenderse contra el creciente grupo de enemigos.
### Resultado del proyecto:
El Spawn Manager operará en oleadas y generará varios enemigos y un nuevo potenciador con cada iteración. Cada vez que la cantidad de enemigos llegue a cero, se generará una nueva oleada y aumentará la cantidad de enemigos.

Tablero [Trello](https://trello.com/invite/b/0lQT9RcI/ATTIf418c09484e2e493e5cf59f7b6b4885aC1F6D11B/videojuego)

