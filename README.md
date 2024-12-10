#Juego de Parejas en React
Este es un juego de cartas tipo "Memoria" o "Parejas" implementado con React. El objetivo del juego es emparejar cartas con imágenes similares, girándolas una a una hasta encontrar los pares correctos. El jugador gana cuando todos los pares son encontrados y las cartas se emparejan correctamente.

Características:
Cartas con imágenes: El juego utiliza un conjunto de imágenes que se duplican y barajan para formar un mazo de cartas ocultas.
Interactividad: El jugador puede hacer clic en las cartas para girarlas y ver las imágenes. Si se encuentran dos cartas con la misma imagen, se mantienen giradas.
Voz: El juego utiliza la API de SpeechSynthesis para anunciar en voz alta las acciones del jugador, como seleccionar una carta o encontrar un par.
Reinicio automático: Al finalizar el juego con éxito (cuando todas las cartas se emparejan), se muestra un mensaje de victoria y el juego se reinicia automáticamente.
Tecnologías:
React: Biblioteca para la construcción de interfaces de usuario.
CSS: Estilos personalizados para la presentación del juego, incluyendo transiciones y efectos de animación.
SpeechSynthesisUtterance: API de voz del navegador para anunciar las cartas y las acciones del jugador.
