# GaboxTV codigo fuente
Hola, soy Gabox y dare mas a detalle este proyecto y recomendaciones para actualizar la pagina con nuevos reproductores

# ¿Como fue hecho?
Fue hecho con BING AI, le pedi una pagina y le fui agregando cosas que tenia en mente,lo arregle para que quede asi. Le puse pocos canales pero les pueden poner los que quieran.

# ¿Como añedirle mas canales?
Para añedirle mas canales deben ir a [Futbol Libre](https://futbollibretv.tv/) y elegir el canal.
Despues de eso deben apretar F12 y abrir en Body; luego a container y buscan el cuadro y abren el codigo hasta que llegen al link, deberian estar aca:
![image](https://github.com/GaboxTheBest/gaboxtv/assets/92964881/5b3f18ec-d364-4ef4-b485-8797f68d02f8)

Despues de eso usaran esta plantilla y la pondran en otro contenedor
```
<div class="contenedor">
  <div class="cabecera">
    <h1>Canal</h1>
  </div>
  <div class="separador"></div>
  <div class="video">
    <!-- Aquí va el enlace de la transmisión en vivo -->
    <iframe class="embed-responsive-item" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen="" src="Link de la transmicion" scrolling="no"></iframe>

  </div>
  <div class="separador"></div>
  <div class="pie">
    <p>© 2024 Nombre. Futbol libre pero sin virus.</p>
  </div>
</div>
```
En donde dice link de la transmicion copien el link del codigo de futbol libre en donde dice scr="link".

# Ahi lo tendrian hecho :)
