# The Playground

Sandbox de física con ragdolls inspirado en People Playground, en un único archivo: `theplayground.html`.

## Cómo jugar

Descarga `theplayground.html` y ábrelo con Chrome, Edge o Firefox. Funciona sin conexión y también en el móvil.

## Controles por defecto

Son los del juego original y se pueden cambiar en **Ajustes → Teclas**.

| Acción | Control |
| --- | --- |
| Elegir un objeto | Clic en el catálogo |
| Hacerlo aparecer mirando a la izquierda / derecha | Mantén Q / E para ver su silueta en el cursor y suelta para colocarlo |
| Agarrar y arrastrar | Clic izquierdo (lo que agarras cuelga y gira libremente) |
| Girar lo que arrastras | A / D (Mayús: más rápido). Al girarlo mantiene ese ángulo hasta que lo sueltes, aunque choque con algo blando; sólo lo rígido (suelo, paredes, objetos congelados o mucho más pesados) puede torcerlo |
| Ajustar a la cuadrícula y al ángulo | Alt |
| Seleccionar varios | Arrastrar en un hueco, o Mayús + clic. Arrastrar uno mueve toda la selección |
| Activar (disparar, encender, detonar) | F (mantener para uso continuo) |
| Menú contextual (congelar, redimensionar, borrar uniones...) | Clic derecho |
| Borrar lo seleccionado o lo que señalas | Retroceso |
| Deshacer (también los borrados) | Z |
| Copiar / pegar con sus uniones | C / mantén V para ver la silueta y suelta para pegar |
| Detener el tiempo / cámara lenta | Espacio / G |
| Vista detalle (salud de las extremidades, pulso, sangre, temperatura...) | S |
| Mostrar u ocultar el catálogo y las herramientas | Tab |
| Herramientas / poderes | Ctrl |
| Herramientas | 1-9 (el mismo número otra vez pasa a la siguiente de su grupo) |
| Bisagra en el centro de masa | Mantén M al clavarla |
| Zoom / mover la cámara | Rueda / apretar la rueda y arrastrar (también mientras agarras algo) o flechas |
| Ayuda con todos los controles | F1 |

Con el tiempo detenido, lo que arrastras se coloca directamente sin física y los objetos congelados se pueden mover (con el tiempo en marcha no se mueven). Congelar, voltear, duplicar, seguir con la cámara y la visión térmica están en el menú contextual o en Ajustes, sin tecla por defecto, como en el original. En pantallas táctiles, con un objeto elegido, toca un hueco o usa los botones Q/E.

## Qué incluye

- Personas con salud por extremidad: dolor, sangre, huesos rotos, desmembramiento, consciencia, pulso, temperatura corporal y respiración (se ahogan bajo el agua).
- 330 objetos: armas blancas y de fuego, accesorios para armas, explosivos, lanzadores, armas de energía, electrónica, biológico, química y líquidos, maquinaria, vehículos, iluminación y objetos.
- Electricidad con cable de cobre y señales con cables de activación verde, rojo y azul (botones, interruptores, detectores, contadores, compuertas, radios...).
- Temperatura: fuego, metal al rojo, congelación, calefactores y refrigerantes.
- Líquidos: matraces que vierten y recogen, jeringas que inyectan y extraen, mezclas, y conductos con presurizadores y válvulas.
- Agua y lava con flotación. 21 mapas: los del original (Abismo, Híbrido, Gigante, Reactor A5, Inclinado, Pequeño, Nevado, Subestructura con ascensor, Diminuto, Vacío y Valle, más Mar y Foso de lava) y otros extra (Explanada, Piscina, Foso de pinchos, Plataformas, Arena cerrada, Torre, Bloques y Escaleras).
- Editor de mapas: dibuja bloques, rampas, agua y lava, y guarda tus propios mapas.
- Entorno: temperatura ambiente, lluvia, nieve, niebla y tormenta eléctrica.
- Herramientas de unión (soldar, bisagras, resortes, cuerdas, cadenas, vendas, ataduras de acero y madera, correas, conductos...) y poderes (empujar, atraer, levantar, rayo, fuego, frío...).
- Menú contextual con redimensionar, fijar ángulo y temperatura, hacer indestructible, silenciar y más. Visión térmica.
- Guardar escenas y guardar construcciones como artefactos en el catálogo.

## Notas

- El historial de versiones está en [CHANGELOG.md](CHANGELOG.md).
- La física usa [planck.js](https://github.com/piqnt/planck.js) (licencia MIT), incluido dentro del HTML.
- Todo el arte pixel y los sonidos se generan por código; no hay recursos externos.
