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
| Agarrar y arrastrar | Clic izquierdo (lo que agarras cuelga y gira libremente; la fuerza no depende del peso) |
| Girar lo que arrastras | A / D (Mayús: más rápido). Al girarlo mantiene ese ángulo hasta que lo sueltes, aunque choque con algo blando; sólo lo rígido (suelo, paredes, objetos congelados o mucho más pesados) puede torcerlo |
| Ajustar a la cuadrícula y al ángulo | Alt |
| Seleccionar varios | Arrastrar en un hueco, o Mayús + clic. Arrastrar uno mueve toda la selección |
| Voltear lo que arrastras o señalas | R (una persona sigue sosteniendo lo que lleva en las manos) |
| Activar (disparar, encender, detonar) | F (mantener para uso continuo) |
| Agarrar con la mano de una persona | F mientras la arrastras por el brazo (F otra vez: soltar) |
| Menú contextual (borrar, copiar, congelar una parte, poses, IA...); con varias cosas seleccionadas se aplica a todas las compatibles | Clic derecho |
| Borrar lo seleccionado o lo que señalas | Retroceso |
| Deshacer (también los borrados) | Z |
| Copiar / pegar con sus uniones | C / mantén V para ver la silueta y suelta para pegar |
| Detener el tiempo / cámara lenta | Espacio / G |
| Vista detalle (vida de cada parte, alcance de los explosivos, pulso, sangre...) | S |
| Visión térmica (temperatura de lo que señalas) | T |
| Mostrar u ocultar el catálogo y las herramientas | Tab |
| Herramientas / poderes | Ctrl |
| Herramientas | 1-9 (el mismo número otra vez pasa a la siguiente de su grupo) |
| Bisagra en el centro de masa | Mantén M al clavarla |
| Zoom / mover la cámara | Rueda / apretar la rueda y arrastrar (también mientras agarras algo) o flechas |
| Ayuda con todos los controles | F1 |

La interfaz es como la del original: los objetos a la izquierda (con buscador y, abajo, Ajustes, Entorno y los botones para borrar todo, los restos o los seres vivos), las herramientas y los poderes a la derecha, y arriba a la derecha la herramienta, el objeto elegido, la velocidad del tiempo, la vista detalle y la visión térmica. Hay tres formas de agarrar: **Arrastrar** (mano blanca), **Arrastre preciso** (mano azul: lo agarrado va justo al cursor y gira libremente) y **Mover** (flechas: sin física).

Con el tiempo detenido, lo que arrastras se coloca directamente sin física y conserva su impulso al reanudar; los objetos congelados sólo se mueven en pausa. Congelar (sólo la parte que señalas), duplicar y seguir con la cámara están en el menú contextual, sin tecla por defecto, como en el original. En pantallas táctiles, con un objeto elegido, toca un hueco o usa los botones Q/E.

## Qué incluye

- Personas con salud por extremidad: dolor, sangre, huesos rotos, desmembramiento, consciencia, pulso, temperatura corporal y respiración (se ahogan bajo el agua). Poses (tropezar, caminar, encogerse, sentarse, pose rígida) e IA que se puede activar en cada una: corren, buscan armas a las que se puede llegar, disparan (sin herir a los inocentes que haya en medio), pelean cuerpo a cuerpo con estocadas o golpes desde arriba según el arma, rematan a los zombis caídos, se apartan de explosivos y fuego, saltan obstáculos y se arrastran si tienen las piernas dañadas. Zombis variados (cada uno con su pelo y su ropa) que contagian al morder o arañar (algunos corren y otros saltan).
- 330 objetos: armas blancas y de fuego, accesorios para armas, explosivos, lanzadores, armas de energía, electrónica, biológico, química y líquidos, maquinaria, vehículos, iluminación y objetos.
- Electricidad con cable de cobre y señales con cables de activación verde, rojo y azul (botones, interruptores, detectores, contadores, compuertas, radios...).
- Temperatura: fuego, metal al rojo, congelación, calefactores y refrigerantes.
- Líquidos: matraces que vierten y recogen, jeringas que inyectan y extraen, mezclas, y conductos con presurizadores y válvulas.
- Agua y lava con flotación. 21 mapas: los del original (Abismo, Híbrido, Gigante, Reactor A5, Inclinado, Pequeño, Nevado, Subestructura con ascensor, Diminuto, Vacío y Valle, más Mar y Foso de lava) y otros extra (Explanada, Piscina, Foso de pinchos, Plataformas, Arena cerrada, Torre, Bloques y Escaleras).
- Editor de mapas: dibuja bloques, rampas, agua y lava, y guarda tus propios mapas.
- Entorno: temperatura ambiente, lluvia, nieve, niebla, tormenta eléctrica y colisiones entre seres (humanos, zombis y androides).
- El fuego consume lo que arde: los objetos acaban en ceniza y las personas, como esqueletos carbonizados.
- Herramientas de unión (soldar, cable rígido que une dos cosas como una sola pieza, cable rígido articulado, bisagras, resortes, cuerdas, cadenas, vendas, ataduras de acero y madera, correas, conductos...) y poderes (empujar, atraer, levantar, rayo, fuego, frío...).
- Máquinas con fuerza ajustable (servomotores, rotores, pistones, propulsores, vehículos...) desde el menú contextual.
- Menú contextual como el del original (congelar por partes, inspeccionar, editar capa, poses, IA...), además de redimensionar, fijar ángulo y temperatura, hacer indestructible, silenciar y más.
- Guardar escenas y guardar construcciones como artefactos en el catálogo.

## Notas

- El historial de versiones está en [CHANGELOG.md](CHANGELOG.md).
- La física usa [planck.js](https://github.com/piqnt/planck.js) (licencia MIT), incluido dentro del HTML.
- Todo el arte pixel y los sonidos se generan por código; no hay recursos externos.
