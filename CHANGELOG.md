# Historial de cambios

## Versión 13.5: suspensión de los vehículos (5 de octubre de 2026)

- **Las ruedas ya no se hunden en la carrocería**: el muelle de cada rueda se calculaba con la masa de la rueda y no con el peso que sostiene. Así, en reposo, la carrocería bajaba sobre las ruedas: el coche 8,5 px (con ruedas de 13 px de radio), la camioneta 10,6, el autobús 11,8 y el camión hasta 17,6, inclinado y con el parachoques en el suelo.
  - Ahora cada muelle aguanta el peso que le toca según dónde está el centro de masa del vehículo. Además está precargado, así que en reposo cada rueda queda justo en su paso de rueda (0 px en todos los vehículos).
  - La suspensión amortigua como la de un coche de verdad: al caer desde 3 m se comprime y en un segundo vuelve a su sitio, sin quedarse rebotando. Al acelerar se agacha un poco de atrás.
  - Al cambiar la gravedad o hacerlo ingrávido, la suspensión se reajusta.
- Como la carrocería ya no roza el suelo, los vehículos andan bien. El autobús, que antes no avanzaba, recorre 28 m en 3 s; la camioneta, 32 en vez de 11, y el camión, 26 en vez de 19.

## Versión 13.4: texturas nuevas (5 de octubre de 2026)

- **Armas antiguas redibujadas**: las armas de antes de las armas reales (versión 11) tienen texturas nuevas con el mismo estilo que las reales. Tienen luz arriba y sombra abajo, contorno, miras, guardamontes, cargadores, vetas de la madera, empuñaduras rugosas, remaches y bobinas que brillan.
  - **Pistolas**: pistola, pistola de 9 mm, pistola con silenciador, revólver, Magnum, cañón de mano, pistola de chispa, táser, aturdidor, pistola de bengalas y bláster.
  - **Subfusiles, fusiles y escopeta**:
    - Subfusiles: el normal, el de tambor (con su tambor y el compensador), el compacto y el de cañón largo.
    - Fusil de asalto y fusil clásico (con el cargador curvo y el guardamanos de madera).
    - Fusil semiautomático (con el peine de latón) y escopeta de corredera.
  - **Armas pesadas y de precisión**: minigun (con sus seis cañones y el conducto de munición), ametralladora pesada sobre su trípode, rifle de francotirador y rifle antimaterial (con visor, bípode y freno de boca).
  - **Armas de energía**: rifle láser, desintegrador, rifle de rayos, rayo calorífico, rayo congelante, repetidor de haces, fusil bláster y bláster automático, con la energía que brilla.
  - **Lanzadores y cañones**:
    - Arpón, lanzallamas, bazuca, ballesta y lanzamisiles guiados.
    - Cañón de hierro fundido sobre su cureña, con rueda de radios.
    - Cañón acelerador, cañón de iones, cañón de tormenta, tambor de pulsos, lanzador de arcos y lanzafragmentos.
    - Fusiles de clavos y cañón automático de 30 mm.
    - Los cuatro cañones montados: rayos, láser, haz y 120 mm.
- **Armas cuerpo a cuerpo**:
  - Hojas con lomo, filo brillante y acanaladura: cuchillo, machete, espada, katana con su hamon y espada legendaria con la runa que brilla.
  - Mangos con vetas, cintas y remaches, y cabezas de acero en el hacha, el mazo y el martillo.
  - Motosierra con su cadena, cristal tallado y lanza de justa en espiral.
- **Explosivos, proyectiles y accesorios**:
  - Explosivos: granadas con su espoleta y anilla, cóctel molotov, dinamita, C4 con el detonador, barril explosivo con la etiqueta de peligro, bombona de propano, bomba aérea, bomba nuclear y de fusión, mina naval con sus cuernos y recipiente de energía.
  - Proyectiles: cohetes, misiles, proyectiles y clavos.
  - Accesorios de las armas: mira, láser, linterna, silenciador y munición especial.
  - Pistolas médicas: curativa, reconstructor y rigidificador.
- Se usan exactamente igual que antes: los 115 objetos conservan su tamaño, su forma física y los puntos de la boca y la empuñadura.

## Versión 13.3: criaturas que saben andar y cirugía (5 de octubre de 2026)

- **Las criaturas saben usar su cuerpo**: una creación con patas de más (un «caballo» de cuatro patas, una araña de seis, dos torsos con cuatro piernas...) se pone de pie sobre todas y anda moviéndolas al paso, la mitad hacia delante mientras la otra mitad empuja. Antes, un caballo de cuatro patas no sabía andar.
  - Cada criatura calcula su postura con la forma real de su cuerpo: cuántas patas tiene, dónde están cosidas, cuánto miden y hacia dónde apuntan. Así se pone a la altura de sus patas, con el cuerpo tumbado si las patas cuelgan de un torso horizontal. Si pierde una pata se reajusta y, si pierde todas, se cae.
  - Las que sólo tienen brazos andan apoyándose en ellos, y lo que no es pata resbala por el suelo en vez de frenarla.
  - Funciona con su IA (huye de los zombis, persigue, corre...), con «Caminar» y con los poderes (con más pulmones y músculos, más rápido). Las personas normales andan como siempre.
  - Al soltar una pierna junto a una criatura, se cose antes al torso que a otra pierna.
- **Arrancar órganos desde el menú**: con clic derecho sobre una parte del cuerpo con órganos aparece «Arrancar órgano» para cada uno de los suyos («Arrancar órgano: Corazón», «Arrancar órgano: Pulmón (2)»...), igual que «Arrancar» con las partes del cuerpo. Sirve con o sin rayos X, y también para lo que hay debajo aunque delante haya un brazo. Con los rayos X se siguen pudiendo arrancar agarrándolos con el ratón.
- **Cuchilla quirúrgica** (Órganos → Cirugía): atraviesa el cuerpo sin chocar con él y corta por dentro, dejando la incisión por donde pasa. Al agarrarla no cuelga: mantiene el ángulo, que se cambia con A/D.
  - Con la punta sobre un órgano, el órgano se marca y se ve cuál es y cómo está («Pulmón · 100 % · F: sacarlo»).
  - Activándola (F) lo saca entero, sin dañarlo, con una herida pequeña y poco dolor. Arrancarlo lo daña y duele mucho más.
- **Zombi sin cerebro**: ya no muere, queda incapacitado. Sigue vivo, pero tirado: no se mueve, no ataca y no contagia a nadie (sólo da algún espasmo), y su información lo dice. Si se le vuelve a meter un cerebro, se levanta otra vez.
- Arreglado: con la IA activada, una criatura de cuatro patas dejaba de andar al momento.

## Versión 13.2: criaturas y poderes de los órganos (5 de octubre de 2026)

- **Las criaturas viven con cualquier forma**: un cuerpo montado a mano sólo necesita una cabeza, cerebro, corazón, pulmón, riñón e hígado (dentro o unidos con venas). Los torsos, brazos y piernas son opcionales, y la sangre la pone en marcha la descarga.
  - Vale cualquier cabeza: si falta la de su sitio, o no tiene cerebro, cuenta la que esté cosida en otro sitio (por ejemplo en el segundo torso). Lo mismo con el torso.
  - Antes, una criatura de dos torsos y cuatro piernas no vivía: o su cabeza cosida en el segundo torso no contaba, o la descarga que le daba vida le paraba el corazón al seguir electrocutándola. Ahora a un Frankenstein la electricidad nunca le para el corazón ni le daña el cerebro, y vive y se levanta.
  - Si a alguien le cortan la cabeza pero tiene otra cosida con cerebro, sigue vivo con ésa.
- **Poderes de los órganos de más** (con Cuerpos realistas o en un Frankenstein; se ven en su información):
  - **Corazones**: más fuerza (un 15 % por cada uno), aguanta mejor los golpes y las balas, recupera la sangre, las heridas dejan de sangrar antes, aguanta con menos sangre y no sufre paros cardíacos (ni por la electricidad ni por el veneno) mientras le quede un corazón sano.
  - **Cerebros**: esquiva balas, puñetazos, tajos y mordiscos con un «sentido arácnido» (28 % con uno de más, 63 % con tres, hasta un 80 %) y, si esquiva un mordisco, no se contagia. Lanza con la mente lo que tiene cerca contra sus enemigos (telequinesis: más pesado y más a menudo cuantos más cerebros). Reacciona antes, se recupera antes de un golpe en la cabeza y no se asusta.
  - **Pulmones**: corre más, salta más y aguanta mucho más sin respirar.
  - **Músculos**: más fuerza (un 30 % por cada uno), corre y salta más y sus golpes hacen más daño.
  - **Riñones e hígados**: los venenos le hacen menos efecto y los elimina antes; el virus zombi avanza más despacio. Con tres de más, inmunidad total a venenos, drogas y al virus zombi, y si ya estaba contagiado, se cura.
  - **Estómagos**: aguanta el ácido; con tres de más, el ácido no le hace nada. **Intestinos**: se regenera, cierra las heridas, recupera la sangre y cura las partes dañadas.
  - Nuevo **«Saltar»** en el menú de cada persona, para ver lo que salta.
- **Descoser**: en el menú de una parte cosida (de una creación, o una de más en cualquiera) están **«Descoser esta parte»**, que la separa como una parte suelta que ya no cuenta como del cuerpo, y **«Eliminar sólo esta parte»**. La tecla de borrar señalando una parte cosida de una creación borra sólo esa parte, no la creación entera (y se puede deshacer con Z). Al coser, el aviso recuerda cómo separarla.
  - En Entorno → Seres vivos, **«Coser las partes al soltarlas junto a otro cuerpo»** permite que no se cosan solas; entonces se cosen sólo con «Coser al cuerpo más cercano».

## Versión 13.1: rayos X y cirugía sin límites (5 de octubre de 2026)

- **Rayos X** (tecla **X**, o el botón de arriba junto a la visión térmica): las personas y los zombis se ven por dentro, con la carne translúcida, los huesos (más oscuros si están rotos) y los órganos encima de todo, aunque los tape un brazo. Cada órgano tiene su color según su estado: los dañados, más oscuros y con el borde rojo, y los destrozados, grises.
  - Al señalar un órgano se ve cuál es y cómo está («Corazón · 35 %»). Agarrándolo con el ratón y tirando se arranca y se queda en la mano, y en el menú contextual aparecen **«Arrancar»** y **«Dañar»** para el órgano señalado. Sirve en vivos y en muertos.
  - Sin Cuerpos realistas se ven sólo los huesos (avisa de que hay que activarlos para ver los órganos). Si ya usabas la X para otra acción, los rayos X se quedan sin tecla y se les puede poner una en Ajustes.
- **Daño de los órganos según el recorrido**: los disparos y las puñaladas dañan los órganos por los que pasan dentro del cuerpo, no sólo el que está junto a la herida de entrada (antes cinco balazos en el pecho podían no tocar el corazón). El corazón es más delicado: dos balazos que lo atraviesen lo paran, y la causa de la muerte dice «Corazón destrozado» (o «Sin corazón» si no lo tiene).
- **Los órganos sueltos son restos**: los que no están unidos a nada (ni con una vena ni en la mano de alguien) se borran con «Borrar restos», así no quedan cerebros y corazones por el suelo.
- **Órganos sin límite**: de cada órgano se pueden meter todos los que quieras (por ejemplo 10 corazones y 20 pulmones). Cada uno busca un hueco libre: su sitio de siempre si está vacío y, si no, el resto del tronco y luego los torsos cosidos de más. Los cerebros van a la cabeza y los músculos a cualquier parte. Todos cuentan para sus funciones. Con varios cerebros manda el que está mejor: si se destroza, piensa el siguiente.
  - El menú **«Órganos…»** se actualiza en la misma ventana; antes «Meter» y «Sacar» abrían otra encima de la que ya estaba. Tiene **«Meter todos»** para los que haya cerca o unidos con venas, y con más de tres órganos iguales muestra la cuenta («20 dentro: 20 × 100 %») y un **«Sacar el peor»**.
- **Coser partes del cuerpo en cualquier sitio**: una parte (una del menú, una cortada o un Frankenstein a medias) se cose donde toque a otro cuerpo, no sólo en su hueco de siempre. Así puedes poner una pierna en el pecho, un brazo en la cabeza o varios torsos juntos. Mientras la arrastras, el punto de la costura se marca en verde.
  - Si la sueltas junto a su hueco de siempre, va a su hueco y se mueve como siempre. En cualquier otro sitio queda cosida tal como la pusiste, aunque mirase hacia el otro lado, por la parte que toca (una pierna cosida por el pie cuelga del pie). Es una parte de más que el cuerpo sostiene con sus músculos y con sus órganos funcionando.
  - «Coser al cuerpo más cercano», sin un hueco cerca, la lleva hasta el cuerpo más próximo y la cose donde lo toca.
  - Cortar, reventar o arrancar una parte de más (aunque sea una cabeza o un torso) no mata. Una parte de más arrancada se puede coser en el hueco de otro cuerpo y pasa a ser la suya de verdad.
  - Se voltean con R junto al cuerpo, se ven por dentro con los rayos X y se copian y se guardan con el cuerpo (en estructuras y escenas).

## Versión 13: Frankenstein (4 de octubre de 2026)

- **Zombis resistentes** (Entorno → Seres vivos → Zombis: «Resistentes», lo normal ahora, o «Como antes»): un zombi sólo muere si le separas la cabeza del cuerpo, si le cortas al menos la mitad de la cabeza o si se la destrozas (un disparo, una puñalada o golpes que le destrocen el cerebro, una explosión o un peso que se la revienten, o quemarse hasta los huesos).
  - Perder los brazos o las piernas, que lo partan por la cintura, desangrarse, el corazón, el veneno, ahogarse, el frío o la electricidad no lo paran: sigue persiguiéndote. Sin piernas se arrastra con los brazos y sin brazos ni piernas se retuerce hacia ti; no siente dolor, así que sigue andando aunque arda, y congelado sólo se queda quieto hasta que se descongela.
  - Un golpe muy fuerte en la cabeza lo tumba la mitad de tiempo que antes. La IA apunta a la cabeza, espera a tenerla en el punto de mira cuando está lejos y remata con un tiro en la cabeza a los zombis caídos.
- **Cuerpos realistas** (Entorno → Seres vivos): las personas y los zombis tienen dentro cerebro, corazón, dos pulmones, hígado, estómago, dos riñones e intestinos, cada uno en su sitio.
  - Se dañan si les da de lleno un disparo, una puñalada, un tajo o una explosión (un tiro lejos del corazón ya no lo para por azar) y hacen su función: sin cerebro se muere; sin corazón la sangre deja de circular; con un pulmón se respira peor y sin ninguno se asfixia; sin hígado o sin riñones se acumulan las toxinas y, al rato, falla el cuerpo; el estómago y los intestinos sangran por dentro si les dan. En las heridas y en los cortes se ve el órgano que hay debajo.
  - Con los cortes, las explosiones y los aplastamientos los órganos se salen del cuerpo y quedan sueltos, con física propia (cada uno se va con su lado del corte, y si el corte pasa por él puede partirse o caer).
  - **Trasplantes**: un órgano suelto (o uno nuevo del menú) unido al cuerpo con un **conductor de líquido** (una vena artificial) vuelve a hacer su función y cuelga de la vena; desde su menú se puede **meter dentro**. Con un corazón nuevo y el desfibrilador, alguien que murió sin corazón vuelve a vivir (el desfibrilador dice qué le falta si no puede). En el menú de cada persona, **«Órganos…»** enseña cómo está cada uno y permite sacarlos o meter los que tenga cerca. Un cerebro de zombi convierte en zombi a quien se lo ponen.
- **Categoría Órganos** (justo después de Materiales médicos y Químicos), con apartados: **Órganos** (cerebro, corazón, pulmón, hígado, estómago, riñón e intestinos), **Músculos** (cada músculo que unas o metas en un cuerpo le da más fuerza) y **Partes del cuerpo** (cabeza, torso, brazo, antebrazo, pierna y pie, vacías, sin órganos).
- **Frankenstein**: una parte del cuerpo se cose a otro cuerpo soltándola junto a su sitio (el cuello, el hombro, la cadera...; el hueco se marca en verde mientras la acercas) o con «Coser al cuerpo más cercano» en su menú, con puntadas en la costura y su propia piel. Con un torso, una cabeza, cerebro, corazón, al menos un pulmón y sangre, una descarga eléctrica (el desfibrilador, «Electrocutar», «Dar vida», un rayo o un cable con corriente) le da vida: ya es un ser vivo, que se levanta y tiene IA. Lo cortado a cualquiera también se puede volver a coser en su sitio, y un brazo o una pierna nuevos se pueden coser a alguien que los ha perdido.
- **Armas grandes con las dos manos**: las escopetas, subfusiles, fusiles, francotiradores, ametralladoras y lanzadores se sujetan con la mano del gatillo en la empuñadura (el codo atrás) y la otra en el guardamanos, unida al arma, y las pesadas cargan sobre el cuerpo en vez de tumbarlo. Al disparar el arma se mueve unas cinco veces menos.
- **Dos pistolas a la vez**: con la IA, quien tiene una pistola y encuentra otra (si no hay cerca nadie más que necesite un arma) la coge con la otra mano. Si vienen enemigos por los dos lados, dispara a la vez hacia delante y hacia atrás (la pistola de atrás bien puesta, no del revés); si vienen por un lado, dispara con las dos alternando, el doble de rápido.
- **Copiar y guardar con todo**: la silueta al pegar y la miniatura de una estructura guardada se ven a su tamaño real (Redimensionar), y se copian los ajustes de cada objeto (el color de la carcasa o del globo, textos, notas, retrasos, intervalos, teclas, potencias, sentidos, modos, líquidos...) y su daño. Las personas se copian con las partes que les faltan o tienen sueltas, las cosidas de otros cuerpos con su piel, las puntadas y sus órganos; las partes sueltas del menú y los Frankenstein, tal cual.
- Al reanimar a alguien, el pulso vuelve a contarse (antes podía quedarse en «Sin pulso»).

## Versión 12 (4 de octubre de 2026)

- **Corte libre del cuerpo**: las personas (y los zombis y androides) se pueden cortar por cualquier sitio, siguiendo la trayectoria de lo que las corta. Un tajo de katana de arriba abajo las parte en dos mitades; uno horizontal, por la cintura o por el cuello. Antes del corte el cuerpo se ve igual que siempre.
  - Los píxeles de cada parte se reparten a un lado y otro de la línea de corte y lo que se separa se convierte en un trozo con su propia forma física, que cae, rueda, sangra y se puede volver a cortar. En el borde del corte se ven la carne y el hueso.
  - Lo que colgaba del lado cortado se va con el trozo (si cortas el brazo por la mitad, el antebrazo cae con él), lo que estaba clavado en ese lado también, y una mano cortada suelta lo que sostenía.
  - Si el tajo es lo bastante fuerte, la hoja no se frena: atraviesa una parte tras otra. Cuanto más grande es la parte (el torso, la cadera), más fuerte tiene que ser el golpe; el hacha y las espadas cortan mucho mejor que un cuchillo.
  - Cortan las katanas, espadas, machetes, cuchillos, hachas (que antes no llegaban a cortar), el cristal y la espada legendaria; la motosierra y la espada de energía cortan poco a poco hasta atravesar; el rotor del helicóptero, el láser y las armas de haz cortan a lo largo de su recorrido, y la IA también puede partir a sus enemigos con sus tajos.
  - Partir la cabeza mata; partir el torso o la cadera, también (salvo a los zombis, que se siguen arrastrando sin piernas).
- **Romperse en trozos como los ladrillos**: las explosiones fuertes, los aplastamientos y los disparos de gran calibre ya no hacen desaparecer las partes del cuerpo en una nube de sangre: las rompen en dos, tres o cuatro trozos que salen despedidos. Si se vuelven a golpear, revientan del todo.
- Para que la partida siga fluida hay un máximo de 300 trozos sueltos a la vez; los cortes respetan los ajustes de desmembramiento e inmortalidad.

## Versión 11 (4 de octubre de 2026)

- **Armas de fuego por apartados**: el catálogo de armas de fuego se divide en **Pistolas**, **Escopetas**, **Subfusiles**, **Fusiles de asalto / rifles**, **Rifles de precisión / snipers** y **Armas explosivas y lanzadores** (y, al final, los accesorios), con su título como en la maquinaria.
- **Armas pesadas sólo con explosivos**: bombas, granadas, minas, dinamita, C4, molotov, bombonas y barriles explosivos, fuegos artificiales, EMP, singularidad... Los lanzacohetes, lanzagranadas, bazuca, lanzamisiles, lanzallamas, pistola de bengalas, ballesta, arpón, fusiles de clavos, lanzafragmentos y todos los cañones pasan a armas de fuego (armas explosivas y lanzadores).
- **56 armas reales nuevas**, cada una con su aspecto, calibre, cadencia, retroceso y precisión:
  - **Pistolas**: Desert Eagle y Desert Eagle dorada, Glock 17 y Glock 17 con mira Red Dot, SIG Sauer P225, P226 y P226 con silenciador y mira, Beretta M9, M1911, FN Five-seveN y H&K USP.
  - **Escopetas**: Franchi SPAS-12, AA-12 (automática, con tambor), Remington 870 (de corredera: se bombea tras cada disparo) y Benelli M4.
  - **Subfusiles**: H&K MP5A2 y MP5SD (silenciado), H&K MP7, H&K UMP45, FN P90, IMI Uzi y Kriss Vector.
  - **Fusiles**: AR-15 (semiautomático), FN SCAR-H, SCAR-L y SCAR-H de Fuerzas Especiales (silenciador, mira holográfica y empuñadura), FAMAS, M4A1 (base, Holosun, ACOG, CQBR y Over Tactical, con silenciador, mira holográfica con lupa, láser, linterna y empuñadura), M16A1 y M16A2 (ráfagas de tres balas), H&K HK416 y HK416 con EOTECH, H&K G3, G36C y G36K, IMI Galil, M4-WAC-47, Steyr AUG A3, C7A2 y C7A2 con mira C79, FN FAL y FAL Paratrooper 50.63, FN F2000, IWI Tavor TAR-21 y X95, SA80, KN-60 y QBZ-95 y QBZ-191.
  - **Francotiradores**: SVD Dragunov, CheyTac Intervention y Mk 14 EBR.
  - Las armas que ya había y coincidían con la lista pasan a ser la real: la ametralladora es la **M249**, el fusil de cerrojo el **Kar98k**, el lanzacohetes el **RPG-7** (se ve el cohete puesto y desaparece al dispararlo hasta que se recarga) y el lanzagranadas el **Milkor MGL** (tambor de 6 granadas que se recarga al vaciarse). Lo guardado con ellas sigue cargando.
  - Las semiautomáticas respetan su cadencia, las de cerrojo y corredera suenan al recargar cada disparo, y las que traen mira, silenciador, láser o linterna de serie no admiten otro accesorio igual. Las miras de serie mejoran la precisión según su tipo (punto rojo, holográfica, ACOG, visores...).
  - La IA sabe usarlas todas (las escopetas de cerca, los francotiradores de lejos y los lanzadores sin acercarse demasiado).
- **Vehículos nuevos**:
  - **Bote**: lancha con motor fueraborda que flota de verdad (cabecea con el peso y levanta la proa al acelerar), lleva a dos personas sentadas y sólo avanza con la hélice en el agua. Si se rompe el casco, se inunda y se hunde poco a poco.
  - **Helicóptero**: F arranca el motor; el rotor tarda en coger vueltas, despega solo y se queda suspendido. Desde el menú se sube, se baja, se avanza, se retrocede o se aterriza (con señales: rojo sube y azul baja). Compensa el peso de lo que lleva, el rotor corta lo que toca y se rompe contra algo duro, y si se apaga en el aire baja girando hasta el suelo. Lleva a dos personas.
  - En los dos, el menú **«Subir a bordo a la persona más cercana»** la sienta en un asiento libre (con lo que lleve en las manos) y **«Bajar a todos»** los deja fuera, de pie junto al vehículo.
- **Cables de activación invisibles**: los cables de propagación (verde, rojo y azul, normales y destructibles) no se ven salvo cuando tienes equipada cualquiera de sus herramientas, y entonces se ven todos los colores a la vez. Mientras no se ven tampoco se pueden señalar ni borrar sin querer; las señales pasan por ellos igual.
- **Correcciones**: el agua que salpica ya no enfría los objetos por debajo de su temperatura (un bote al caer al mar llegaba a −140 °C y congelaba a quien se sentaba en él). La IA vuelve a distinguir bien las armas de balas de los lanzadores.

## Versión 10 (4 de octubre de 2026)

- **Categorías nuevas del catálogo**: Seres vivos, Armas cuerpo a cuerpo, Armas de fuego, Armas pesadas, Vehículos, Maquinaria, Objetos y Decoración, y Materiales médicos y Químicos (más los artefactos guardados).
  - Las armas de energía pasan a armas de fuego (pistolas, fusiles, táser, aturdidor...), a armas cuerpo a cuerpo (espada de energía) o a armas pesadas (los cañones y la singularidad). Los lanzadores pasan a armas pesadas y los accesorios de armas, a armas de fuego.
  - Los matraces, la botella, el gotero, la pistola curativa, el reconstructor y el rigidificador pasan a materiales médicos y químicos. El globo, el extintor, el punto de anclaje, el trampolín, el bidón de líquido y el cuenco de madera pasan a objetos y decoración.
- **Maquinaria según la lista**: 90 máquinas en 9 apartados que se ven en el catálogo (activación y gestión de señales; fuentes de alimentación y potencia; sensores y detectores; propulsión, motores y movimiento; iluminación y óptica; mecánica de fluidos y química; medicina avanzada; maquinaria física avanzada, energía y destrucción; automatización, acoplamientos y comunicación).
  - **Nuevas**: puertas lógicas **AND, OR, XOR y NOT** (sus entradas son los cables de propagación que llegan a ellas y su salida, los que salen; mientras la salida está activa también dan electricidad), **núcleo de distorsión** (120 de energía, deforma el espacio a su alrededor y, si se daña o se calienta demasiado, colapsa en una singularidad y estalla), **generador EMP** (apaga durante 6 s la maquinaria eléctrica cercana y aturde a los androides), **motor eléctrico** (gira más rápido y con más fuerza cuanta más electricidad le llega), **hélice grande**, **engranajes** (los que se tocan giran a la vez, en sentido contrario y según su tamaño), **espejo láser** (desvía el láser sin estropearse) y **martillo eléctrico** (prensa que deja caer de golpe su martillo al recibir una señal; sustituye al martillo percutor de mano).
  - **Cambian**: la **palanca** (el antiguo interruptor eléctrico) envía una señal en cada cambio de posición y, abajo, corta la corriente. El **interruptor** (antes conmutador de activación) se queda encendido o apagado. El **aleatorizador** manda cada señal por una sola de sus salidas, elegida al azar.
  - El **fusible** es eléctrico: se funde si la corriente supera su límite y corta el circuito. El **deslizador** es un potenciómetro con un mando que se arrastra y gradúa la corriente. El **transformador eléctrico** multiplica o divide la corriente que pasa por él, y la **resistencia** deja pasar la parte que elijas.
  - El **acumulador** se carga con la corriente que le llega y la suelta en grandes descargas. La **bombilla clásica** y la **jukebox** estallan si les llega demasiada corriente.
  - El **láser** calienta y prende lo que toca, corta la carne poco a poco y acaba rompiendo los espejos normales.
  - Otros ajustes: la **caja de retraso** llega a 60 s, el **termómetro** mide lo que tiene unido y las **pantallas** pueden mostrar en tiempo real la lectura de lo conectado. La **radio**, además de transmitir señales, pone música y suena con un tono. El **electrodo activador** suelta una chispa que prende y da calambre, el **ventilador** aviva el fuego, el **imán eléctrico** atrae el metal de todo el mapa y el **desacoplador** también se suelta con electricidad. La **luz de cátodo** es decorativa y de varios colores, y el **tubo fluorescente** parpadea cuando está dañado.
  - **Nombres de la lista**: activador por llave, caja de retraso, convertidor de señal, medidor de potencia, motor de barco, ruedas, impulsor, cama de impulsores, cabrestante, linterna de mano, foco de inundación, foco directo, luz de cátodo, bombilla clásica, luces LED, duplicador de líquido, salida de fluido, válvula, presurizador, bypass cardiopulmonar, bobina de Tesla, pistola de físicas, caja de amortiguación, giróscopo estabilizador, elemento de enfriamiento, imán eléctrico, acoplador, puntero y jukebox.
  - **Se quitan** (no están en la lista): aislante, compuerta y compuerta temporizada, convertidores de color, detector de rayo, receptor y sensor láser, placa de presión, termómetro infrarrojo, espejo conmutable, indicador de aguja, sierra circular, torretas (normal, láser y de techo), trampa para osos, cadena (objeto), propulsores iónico, de levitación y pequeño, giroestabilizador industrial, ala, ventilador gigante, rueda de madera, rueda grande, barra luminosa, bengala, antorcha, desagüe y válvula de presión.
  - En las escenas guardadas, los que tenían algo parecido pasan a serlo; por ejemplo, el indicador de aguja pasa a medidor de potencia y la rueda de madera, a ruedas. La bengala sigue existiendo como proyectil de la pistola de bengalas.

## Versión 9 (4 de octubre de 2026)

- **Uniones rehechas**: las herramientas de unión son ahora exactamente estas (por grupos de teclas):
  - **2 · Cables de propagación**: verde, rojo y azul, que no se rompen con tirones, y sus versiones **destructibles**, que se rompen si se estiran, con golpes o caídas de lo que unen, si las cruza algo rápido, con balas o con explosiones (se dibujan a trazos). Ahora la señal va **en un solo sentido**: del primer objeto que unes al segundo (una flecha en el cable lo indica).
  - **3 · Cables rígidos**: **Cable rígido** (barra metálica que mantiene la distancia y deja girar los extremos; antes «Cable rígido articulado»; ya no se rompe), **Soporte de madera** (antes «Puntal»: se parte con mucha fuerza, balas o explosiones y arde) y **Tubo de calor** (ya no se rompe).
  - **4 · Cables**: **Cable** (el de cobre: conduce la electricidad y se rompe si se dañan sus extremos: un golpe fuerte o una explosión en un extremo, o si se estira muchísimo), **Conductor de líquido** (ya no se rompe al estirarlo) y **Conductor de líquido destructible** (nuevo: se rompe fácilmente y derrama lo que lleva).
  - **5 · Cables fijos**: **Cable fijo** (el cable rígido sin giro ni movimiento de la versión 8; prácticamente indestructible), **Atadura de acero** (como una soldadura; ya no se rompe) y **Atadura de madera** (se rompe con mucho peso, balas o explosiones y arde).
  - **6 · Resortes y pines**: Resorte, Resorte fuerte (aguanta mucho más), **Vendaje**, **Pin** (la antigua bisagra; no se rompe) y **Pin de madera** (nuevo: se parte con mucha fuerza o explosiones y arde).
  - **7 · Conexiones flexibles y mecánicas**: **Cuerda** (se rompe con un tirón muy fuerte o con demasiado peso colgado, más de tonelada y media), **Cadena** (aguanta cualquier tirón o peso), Correa mecánica y **Enlace de fase** (antes «Enlace sin colisión»).
  - Se quitan **Soldar**, **Cable de acero**, **Elástico**, **Bisagra motorizada** y **Enlace de propagación**. Las escenas y construcciones guardadas que los usen siguen cargando: pasan a ser una atadura de acero, una cadena, un resorte, un pin y un cable de propagación verde.
  - La madera (soportes, ataduras y pines) **arde**: si uno de sus extremos se quema o se calienta mucho, la unión se pone al rojo y al rato se parte.
  - Lo que se une con ataduras, cable fijo o pines no choca entre sí (así no se empujan aunque se solapen) y, al quitar la unión, vuelven a chocar en cuanto se separan.
  - Los tirones secos ya no pasan desapercibidos: la fuerza de las uniones que se pueden romper se comprueba en cada paso de la física.
- **Arrancar partes del cuerpo tirando**: si tiras muy fuerte de alguien, se le arranca lo que tiras. Con el ratón, un tirón brusco y largo, o tirar de alguien que está sujeto, le arranca los brazos o la cabeza (las piernas cuestan más); también lo hacen las cuerdas, cadenas o vehículos que tiran de golpe. Sólo cuenta tirar: los golpes y las caídas no arrancan nada por esto. No pasa a los inmortales ni con el desmembramiento desactivado en Ajustes.
- **Zombis muertos**: ya no siguen moviéndose como si se arrastraran.
- **Arrastrarse con los brazos**: al arrastrarse, las personas y los zombis estiran un brazo, lo apoyan y tiran del cuerpo, alternando los dos, en lugar de deslizarse sin moverlos. Si están boca arriba, primero se dan la vuelta.
- **Copias exactas**: copiar y pegar, duplicar, guardar escenas y deshacer un borrado conservan la escala, las colisiones activadas o desactivadas, el sonido silenciado, el congelado, la ingravidez y la fuerza de las máquinas; en las personas, también que sean inmortales, su IA y su pose.

## Versión 8.1 (3 de octubre de 2026)

- **Desmayarse es mucho más difícil**: personas, zombis y androides sólo pierden el conocimiento con un golpe muy fuerte en la cabeza (un batazo o un mazazo, un choque de la cabeza a mucha velocidad, una explosión fuerte o un disparo en la cabeza), y cuanto más fuerte, más tiempo. Los puñetazos, las patadas y los golpes flojos ya no desmayan, y el dolor aturde (se mueven peor) pero no hace perder el conocimiento. Siguen desmayando la pérdida de mucha sangre, el daño cerebral, el ahogo, el frío extremo, los sedantes y las armas aturdidoras.
- Las peleas a puñetazos terminan cuando uno de los dos está demasiado aturdido para seguir.

## Versión 8 (3 de octubre de 2026)

- **Cuerpo a cuerpo más fuerte, con estocadas y golpes desde arriba según el arma**:
  - Los cuchillos, las lanzas, los pinchos y la motosierra atacan de **estocada**: el codo atrás y luego el brazo estirado hacia el objetivo, con el cuerpo acompañando. Los bates, martillos, mazos, palancas, sartenes, hachas y machetes **golpean desde arriba**: el arma por encima de la cabeza y abajo con fuerza. Las espadas (también la katana, la legendaria y la de energía) hacen las dos cosas.
  - Cada persona se pone a la distancia justa para su arma (más lejos con una lanza que con un cuchillo) y espera en guardia con el arma lista. Si un zombi se le echa encima con un arma larga, retrocede.
  - El daño depende del arma (su peso y si corta, pincha o golpea) y de dónde da: una estocada o un golpe fuerte en la cabeza mata en uno o dos golpes, los tajos pueden decapitar y los golpes fuertes derriban. Un mazo mata a un zombi de un solo golpe en la cabeza.
  - Las armas pesadas se blanden sin que la persona se caiga, y el golpe no se queda en los brazos del zombi: llega a la cabeza o al cuerpo.
  - A un zombi caído (pero vivo) que tiene al lado lo **remata**: pasa por encima de él, se agacha y le golpea en la cabeza. Si el arma es demasiado corta para llegar, le da un pisotón.
  - Las armas largas se llevan levantadas; si una se queda clavada en el suelo o apuntando hacia atrás, la vuelven a coger bien.
  - Los puñetazos y las patadas también pegan más fuerte. La motosierra se enciende sola al pelear y se apaga al acabar.
- **Disparos que no hieren a terceros**: cuando una persona dispara a un zombi, sus balas atraviesan sin herir a las demás personas que haya en medio o detrás. Si le dispara a alguien con quien se está peleando, a esa persona sí le da. Con lo que no son balas (lanzallamas, lanzacohetes...) sigue sin disparar si hay alguien en medio.
- **Zombis variados**: como las personas, cada zombi tiene su propio pelo y su ropa (sucia y desgastada), con distintos tonos de piel verde y de ojos.
- **Vista detalle**: cuando algo muere, todas las barras de vida de su cuerpo se vacían (antes los brazos, por ejemplo, podían seguir en verde).
- **Cable rígido** (herramientas, grupo 3): une dos cosas como si fueran una sola pieza, sin que puedan moverse ni girar entre sí, aguanten lo que aguanten. Lo que se une pasa a formar parte del mismo cuerpo, con su peso, su inercia y sus choques, así que tampoco cede con mucho peso (una carga pesada en el brazo de un servomotor, por ejemplo). Se pueden encadenar varios para construir estructuras. El antiguo «Cable rígido» (que mantiene la distancia pero deja girar los extremos) ahora se llama **Cable rígido articulado**.
- **Fuerza de las máquinas**: los servomotores, rotores, ruedas, pistones, deslizadores, propulsores, hélices, motores, ventiladores, electroimanes, giroscopios, vehículos con motor... tienen una opción **Fuerza** en el menú contextual (de 10 % a 2000 %) que multiplica la fuerza de sus motores y todo lo que empujan o atraen. Con más fuerza mueven y levantan más peso. Funciona con varias seleccionadas a la vez y se conserva al copiar, pegar y guardar.
- **Borrar restos** también limpia: la sangre (y las demás manchas) desaparece de los objetos, que quedan como nuevos, y de encima de las personas (las heridas siguen).
- Chocarse sin querer ya no hace que dos personas se peleen (sólo cuenta si la lanzas o la arrastras tú contra la otra, si va a por ella o si le tira algo), y al golpear con un arma blanca sólo se le da a quien se quiere dar.

## Versión 7 (3 de octubre de 2026)

- **IA de las personas rehecha**:
  - Andan y corren de verdad (con animación de piernas y brazos). Corren cuando están en peligro o persiguen a alguien.
  - Deciden con calma: ya no dudan entre huir y disparar. Mantienen cada decisión un tiempo y sólo cambian si hace falta.
  - Sólo temen a lo que es hostil: zombis vivos y conscientes, quien les ha atacado, explosivos encendidos y fuego. A los zombis muertos o caídos ni les temen ni les disparan.
  - Buscan armas solas cuando están en peligro: miran en 10 m, eligen la más fácil de alcanzar siguiendo el suelo (escalones que se pueden saltar, sin paredes, lava ni caídas) y no van si hay un zombi o un peligro en el camino o si el enemigo llegaría antes. Si está en el suelo se agachan, si está a media altura la cogen de pie y si está alta saltan.
  - Disparan apuntando bien aunque el arma pese (corrigen con la dirección real del cañón y el brazo hace más fuerza), mantienen la distancia, disparan ráfagas con las automáticas y no disparan si hay alguien inocente en medio.
  - Pelean cuerpo a cuerpo con armas blancas, lanzan cócteles molotov, se apartan de los explosivos encendidos y del fuego, saltan obstáculos bajos, no se tiran por bordes ni a la lava y, si están acorralados, plantan cara.
  - Con las piernas dañadas se arrastran con los brazos (con la cabeza por delante).
- **Zombis**: sólo contagian al morder o arañar, y sólo si están de pie (o arrastrándose) y conscientes; un zombi muerto o inconsciente ya no contagia. El 15 % corre y el 15 % salta obstáculos (alguno hace las dos cosas), y todos se arrastran si tienen las piernas dañadas.
- **Colisiones entre seres** (en Entorno), por separado para humanos, zombis y androides: sin colisiones entre ellos, sin colisiones con los muertos o con colisiones. Por defecto los zombis no chocan entre sí y los vivos pasan por encima de los muertos, así que las hordas avanzan.
- **Menú contextual para varias cosas**: con una selección, cada opción (congelar, colisiones, ingravidez, curar, hacer inmortal, poses, IA, encender...) se aplica a todas las que la admiten; las demás se quedan igual. También salen las opciones que sólo tienen algunas de las seleccionadas.
- **El fuego consume**: lo inflamable sigue ardiendo hasta deshacerse en ceniza (una caja tarda unos 20 s) y las personas que se queman hasta el final quedan como esqueletos carbonizados. Lo quemado se acumula aunque el fuego se apague y se vuelva a prender.

## Versión 6 (3 de octubre de 2026)

- **Interfaz como la del original**: los objetos a la izquierda (categorías arriba, buscador «Filtrar», casillas con miniaturas y, abajo, Ajustes, Entorno, Borrar todo, Borrar restos y Borrar seres vivos); las herramientas y los poderes en una barra a la derecha (clic derecho en un botón para elegir entre las variantes de su grupo); arriba a la derecha, la herramienta actual, el objeto elegido, la pausa, el reloj con la velocidad del tiempo (100 %, 25 % en cámara lenta, 0 % en pausa), la vista detalle y la visión térmica; y los avisos abajo a la derecha, en mayúsculas. La primera vez aparecen unas pantallas con los controles básicos (se pueden borrar).
- **Menú contextual como el del original**: negro, sin título y en el mismo orden (Eliminar, Copiar, Pegar, Guardar · Seguir, Activar, Prender fuego, Congelar, Desactivar colisiones, Hacer ingrávido, Redimensionar, Editar capa · Fijar temperatura, Fijar ángulo, Inspeccionar, Romper hueso y las poses), seguido de las opciones propias de cada objeto o persona. El menú del clic derecho del navegador ya no aparece mientras juegas.
- **Congelar por partes**: congelar afecta sólo a la parte que señalas (puedes congelar el brazo de una persona y el resto se sigue moviendo). También sirve con objetos.
- **Poses de las personas** (menú contextual): Tropezar, Caminar, Encogerse, Sentarse y Pose rígida.
- **IA de las personas** (se activa o desactiva en el menú contextual de cada una, y para todas en Ajustes): huyen de los zombis, o los atacan si tienen un arma (y cogen una si la tienen cerca), y se defienden de quien les ataque. Si haces que una persona golpee a otra, se pelean a puñetazos (y patadas si una cae al suelo) hasta que una queda inconsciente o muere.
- **Agarrar con la mano**: mientras arrastras a alguien por el brazo, F hace que su mano agarre lo que tenga cerca (un arma, otra persona, el suelo, un coche...). F otra vez lo suelta.
- **Voltear con R** lo que arrastras o señalas. Una persona sigue sosteniendo sus armas y objetos pequeños (giran con ella) y lo que tenga clavado; si agarra algo pesado, como un coche, sólo se gira ella y sigue agarrando el mismo punto con el brazo al revés.
- **Agarre que no depende del peso**: la fuerza con la que arrastras se calcula con todo lo que va unido a lo que agarras, así que todo se mueve con la misma soltura (un arma clavada en alguien, una mano, un coche...). El **arrastre preciso** (la mano azul) lleva lo que agarras justo al cursor, como Mover, pero con física y girando libremente; al girarlo con A/D se queda en ese ángulo.
- **Personas más ligeras** (unos 48 kg en vez de 70), con la misma fuerza relativa. Los vehículos ligeros (monopatín, carrito, bicicleta) llevan ejes rígidos: ya no se hunden con alguien encima.
- **Vista detalle (S)** como en el original: una barrita de vida en cada parte del cuerpo y el alcance de la explosión de cada explosivo en un círculo rojo. **Visión térmica (T)**: además, muestra la temperatura de lo que señalas.
- **Tiempo**: lo que mueves con el tiempo detenido conserva su impulso y, al reanudarlo, sigue su trayectoria desde el nuevo sitio. Lo que aparece en pausa se ve al momento.
- **Entorno** en su propia ventana: gravedad, día y noche, temperatura, lluvia, nieve, niebla, tormenta y velocidad de la cámara lenta.
- Inspeccionar muestra la salud, el hueso y la temperatura de cada parte del cuerpo; Editar capa pone algo delante o detrás de lo demás.

## Versión 5 (3 de octubre de 2026)

- **Controles rehechos uno a uno como en el original**:
  - Hacer aparecer un objeto ya no se hace con un clic. Eliges el objeto en el catálogo y mantienes Q o E: verás su silueta en el cursor, y al soltar aparece mirando a la izquierda o a la derecha. Pegar (V) funciona igual. Esc o clic derecho mientras mantienes la tecla cancelan.
  - Lo que agarras cuelga y gira libremente. Si lo giras con A/D, aunque sea un poco, mantiene ese ángulo mientras no lo sueltes: los choques con cosas blandas o ligeras (una persona, por ejemplo) no lo tuercen, y sólo lo rígido (el suelo, las paredes, los objetos congelados o algo mucho más pesado) puede girarlo; al separarse, vuelve a su ángulo.
  - Arrastrar un objeto seleccionado mueve toda la selección. Alt ajusta a la cuadrícula también con el tiempo en marcha.
  - Lo congelado sólo se mueve con el tiempo detenido.
  - Los números eligen grupos de herramientas, y pulsar el mismo número otra vez pasa a la siguiente herramienta del grupo. Mantener M clava las bisagras en el centro de masa.
  - Retroceso borra y Z deshace, incluidos los borrados.
  - La rueda hace zoom y, si la aprietas y arrastras, mueve la cámara, en cualquier momento, también mientras agarras algo. Puedes soltar lo que agarras sin dejar de mover la cámara.
  - Se quitaron las teclas que no son del original (R, L, H, Inicio, Supr, Ctrl+Z/C/V/D y congelar con clic derecho). Esas acciones siguen en el menú contextual o se pueden asignar en Ajustes.
  - Las teclas se detectan por su posición, así que Mayús, Alt o la distribución del teclado no las cambian. Las teclas guardadas de versiones anteriores vuelven a las del original.
- **Jeringas**: las de suero son infinitas (inyectan sin vaciarse). Si les disparas o les alcanza una explosión, revientan y su contenido afecta a quien esté cerca.
- **Objetos clavados**: una jeringa, un cuchillo o una espada clavados se pueden sacar arrastrándolos. Además, al hacer clic tiene prioridad el objeto más pequeño (como en el original), así que agarras lo clavado y no a la persona.
- En táctil: con un objeto elegido, toca un hueco o usa los botones Q/E.

## Versión 4 (2 de octubre de 2026)

- **Controles como en el original**: Z deshace, C copia y V pega (también con Ctrl), Mayús+clic selecciona varios objetos, Mayús gira más rápido, Alt ajusta a la cuadrícula y al ángulo, y F1 abre la ayuda. Con el juego en pausa, lo que arrastras se coloca directamente, sin física.
- **Casi 100 objetos nuevos (330 en total)**:
  - Armas de fuego: fusil de asalto clásico, pistola de 9 mm, fusil semiautomático, subfusil de cañón largo, ametralladora pesada y cañón automático de 30 mm.
  - Armas de energía: repetidor de haces, fusil bláster, bláster automático, cañón de tormenta, aturdidor, tambor de pulsos, lanzador de arcos, reconstructor, rigidificador y cañones de rayos, láser y de haz.
  - Lanzadores y explosivos: bazuca, lanzafragmentos, fusil de clavos automático, cañón de 120 mm, explosivo rosa, granada de púas y recipiente de energía.
  - Armas blancas: martillo, martillo percutor, barra de hierro, palo, lanza de justa, pincho de hierro, cristal, espada legendaria y bastón de tentáculos.
  - Electrónica: conmutador y fusible de activación, compuertas, convertidores de canal, radio, detector, electrodo, transformador eléctrico, indicador de energía, pantallas de texto y holográfica, termómetro infrarrojo, espejo conmutable y extractor de energía de la materia.
  - Maquinaria: caja amortiguadora, decimador, giroestabilizador industrial, apuntador, proyector de partículas, pistola de gravedad, pistón industrial, deslizador, torno, minipropulsor, plataforma de propulsores, ala, ruedas sin motor, máquina de circulación extracorpórea, acoplador adhesivo y ventilador gigante flotante.
  - Química: identificador de líquidos, centrifugadora, duplicador de líquidos, válvula, válvula de presión, presurizador, tanque de sangre y suero rosa.
  - Iluminación: reflector, lámpara catódica y antorcha.
  - Objetos: cubos, pirámide, muros de mampostería y de sillería (se desmoronan en piedras), roca pequeña, pilar, viga corta, carcasa redimensionable que se puede pintar, escritorio, asiento de autobús, ancla y abrazadera.
  - Vehículos: camión, coche flotante, vagón contenedor y tanque antiguo. Todos se pueden poner en marcha atrás, reparar, romper y frenar; las ruedas se pinchan y el depósito puede explotar.
- **Mapas nuevos**: Abismo (el antiguo Vacío), Híbrido, Gigante, Reactor A5 (reactor nuclear con barras de control, regulador automático, parada de emergencia y fusión del núcleo), Inclinado, Pequeño, Nevado, Subestructura (tres plantas con ascensor y parada de emergencia), Diminuto, Vacío y Valle. Los mapas tienen fondo, texturas, focos en los techos y su propia luz. «Limpiar escena» devuelve el mapa a su estado inicial.
- **Editor de mapas**: dibuja bloques, rampas, agua y lava con distintas texturas y guarda tus mapas para cargarlos desde la lista.
- **Uniones nuevas**: atadura de acero, atadura de madera (se quema), enlace sin colisión, conducto de líquido (se rompe si se estira demasiado), correa mecánica, enlace de propagación y arrastre suave.
- **Cables rojo y azul con funciones propias**: invierten motores y ruedas, cambian de sentido el torno, ponen el freno de mano a los vehículos, cambian la polaridad del electroimán o la altura de levitación.
- **Menú contextual**: redimensionar con un deslizador, fijar ángulo, fijar temperatura, hacer indestructible, evitar la electrocución, silenciar, curar un hueso roto, color del puntero láser y modo energía de las ruedas (consumen o generan electricidad).
- **Personas**: pulmones perforados, hemorragia interna, desmayo por fuerza G y los efectos del suero rosa.
- **Ajustes**: visión térmica, tamaño del ajuste a la cuadrícula y al ángulo, y límite de propagación de señales.
- **Poderes**: un clic con el rayo lo hace caer del cielo y la piroquinesis lanza más fuego cuanto más rápido mueves el ratón.
- Detalles del original: el extintor revienta y el lanzallamas explota si les disparas, las armas pueden dispararse solas si caen con fuerza, y el Metrónomo, el Tocadiscos y el Transformador de activación se llaman como en el juego.
- Correcciones: el propulsor de levitación ya no rebota y las escenas guardadas en mapas con máquinas propias ya no las duplican al cargarlas.

## Versión 3 · The Playground (1 de octubre de 2026)

- El juego pasa a llamarse **The Playground** y el archivo ahora es `theplayground.html`.
- Controles por defecto iguales a los del juego original: A/D girar, Q/E colocar mirando a la izquierda o a la derecha, F activar, G cámara lenta, Retroceso/Supr borrar, C/Z copiar y pegar, Tab mostrar u ocultar la interfaz, Ctrl alternar herramientas y poderes, S vista detalle.
- **Electricidad**: cable de cobre, baterías, acumulador, generadores, resistencia, aislante, interruptor, medidor y transformador de señal. Máquinas y luces se encienden solas cuando les llega corriente y las personas conectadas se electrocutan.
- **Temperatura**: conducción por contacto, fuego, metal al rojo, escarcha, quemaduras e hipotermia. Calefactor, refrigerante, termómetro, rayo calorífico, rayo congelante y temperatura ambiente.
- **Líquidos**: 22 líquidos con efectos en el cuerpo. Los matraces vierten al inclinarlos y recogen lo que les cae dentro, hay mezclas, y las jeringas inyectan al clavarse o extraen (F cambia el modo). También gotero, grifo, desagüe, botella, bidón y cuenco.
- **Agua y lava**: flotación según el material, salpicaduras, burbujas y ahogamiento. Mapas nuevos: Mar, Piscina, Foso de lava, Torre y Bloques.
- **Entorno**: lluvia (apaga los fuegos a cielo abierto), nieve que se acumula, niebla y tormenta eléctrica.
- **Vista detalle (S)**: pulso, sangre en litros, temperatura, oxígeno, dolor, sustancias en sangre, masa, energía y contenido de los recipientes.
- **Lógica y detectores**: tecla disparadora, contador, aleatorizador, retardador, sirena, radio, monitor cardíaco, puntero láser con espejos y detectores de movimiento, vida, metal, fuego, impactos y láser.
- **Más de 100 objetos nuevos (232 en total)**: armas nuevas, accesorios que se montan al soltarlos sobre un arma (mira telescópica, mira láser, linterna, silenciador, munición explosiva e incendiaria), explosivos (granada adhesiva y de mango, fuegos artificiales, EMP, mina naval, bomba de fusión), maquinaria (giroscopio, servomotor, plataforma de lanzamiento, campo de inmovilidad, desacoplador, hélice, motores y propulsores), tanque, bicicleta, torretas láser y de techo, y objetos de decorado.
- **Poderes (Ctrl)**: empujar, atraer, levantar, rayo, piroquinesis, criokinesis, explosión y curar.
- **Uniones nuevas**: cable fijo, resorte fuerte, venda (corta las hemorragias), puntal de madera, tubo de calor, cable de acero, cadena y cables de activación de colores. Opciones para quitar colisiones y gravedad a un objeto.
- **Artefactos guardados**: guarda una construcción en el catálogo y vuelve a colocarla con todas sus uniones. Copiar y pegar también conserva las uniones y los cables.
- Correcciones: las jeringas ahora inyectan de verdad; el resaltado y la tecla F vuelven a responder después de cerrar un menú; el cambio de color de la barra luminosa funciona.

## Versión 2 (1 de octubre de 2026)

- Todas las teclas se pueden reasignar en **Ajustes → Teclas**.
- La tecla S muestra u oculta la ventana de datos (vivo, inconsciente, sangre...).
- Agarre más fuerte: lo que arrastras sigue al cursor con algo de inercia, también si lo agarras por una mano o un pie.
- A quemarropa, la escopeta, el revólver y los rifles de gran calibre revientan solo la parte golpeada.
- Bomba nuclear con bola de fuego y hongo de humo; descargas de la bobina Tesla más visibles y marcas de quemado en el suelo.
- Objetos nuevos: lanzallamas y extintor.
- Los objetos clavados ya no salen despedidos al chocar con otras partes del mismo cuerpo, y «Limpiar escena» borra también las manchas del suelo.

## Versión 1 (1 de octubre de 2026)

- Primera versión del sandbox en un solo archivo (`peopleplayground.html`).
- Personas con salud por extremidad: huesos, sangrado, desmembramiento, dolor y consciencia. Se levantan solas y empuñan armas.
- 118 objetos en 11 categorías: entidades, armas blancas y de fuego, explosivos, lanzadores, energía, jeringas, maquinaria, vehículos, iluminación y objetos.
- Herramientas: arrastrar, mover, soldar, bisagra, motor, resorte, cuerda, barra, elástico, cable de activación, congelar, borrar, fuego, explosión, rayo y curar.
- 6 mapas, modo noche, cámara lenta, guardar y cargar escenas, y controles táctiles.
