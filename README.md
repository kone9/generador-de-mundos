# generador-de-mundos diseñado con Godot Engine y Gdscript

un generador de mundos que funciona en el editor, es decir, genera mundos que puedes editar antes de correr la escena, sirve tanto para juegos side-scrolling como top-down. Es un script para nodos tilemaps, que obviamente va a tener que ser editado para obtener los resultados esperados.
Esto surgió ante la necesidad de generar un mapa para un juego rpg, ya que los que yo mismo creaba no se veían muy naturales, Opensimplexnoise me resolvía esto, pero no podía editar el mapa, ya que se generaba en tiempo de ejecución, así que use el modo tool de godot para generar el mundo en el editor y así poder editarlo a mi antojo. espero que les sirva y si hay algo que no se entienda del codigo (que de seguro la hay), no duden en consultar.

Space o Enter para generar un mundo siempre y cuando este habilitado.
sí "semilla aleatoria" esta activada cada vez que presiones Space va a generar un nuevo mundo, por el contrario, si está desactivada, va a generar el mundo basandose en la semilla seteada en el inspector.
link: https://github.com/XardacoX/generador-de-mundos
