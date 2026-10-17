# Glosario aplicado de razonamiento funcional
## 25 productos descompuestos por partes, flujos y funciones

**Workshop:** Inventiva Bajo Restricción con IA  
**Serie:** Discernimiento humano y creatividad soberana mediada por IA  
**Capítulo:** 2 de 3  
**Uso:** Recurso de apoyo para Functional Reasoning y Functional Decomposition  
**Actualizado:** octubre de 2026

*Este documento acompaña el workshop **Inventiva Bajo Restricción con IA**. Su objetivo no es entregar una lista de componentes para memorizar, sino ofrecer suficientes ejemplos concretos para entrenar una forma de mirar productos cotidianos como sistemas compuestos por funciones, flujos, subsistemas e interfaces.*

> **La pregunta central no es “¿qué piezas tiene este objeto?”, sino “¿qué tiene que ocurrir dentro de este sistema para que consiga hacer lo que hace, y qué parte realiza cada una de esas operaciones?”.**

---

## Para qué sirve este glosario

El razonamiento funcional puede explicarse en pocas frases y aun así resultar difícil de aplicar por primera vez.

Sabemos que una cafetera “hace café”, un ventilador “mueve aire” y un taladro “hace agujeros”. Esas descripciones nombran el propósito general del producto, pero todavía no muestran la arquitectura funcional que permite realizarlo.

El cambio que buscamos practicar es éste:

**producto**
↓
**función global**
↓
**subfunciones**
↓
**flujos de energía, materia, información y movimiento**
↓
**partes o subsistemas que realizan cada operación**

Un ventilador, por ejemplo, deja de ser solamente “un ventilador” cuando podemos reconocer que:

- recibe energía eléctrica;
- permite al usuario controlar esa energía;
- la convierte en movimiento rotatorio;
- transmite ese movimiento;
- transfiere momento al aire;
- dirige el flujo resultante;
- sostiene los elementos móviles;
- y protege al usuario de ellos.

Una vez que esas funciones están visibles, es posible buscar **otras piezas, módulos o aparatos capaces de realizar una o varias de ellas**.

Ésa es la operación que después permite sustitución, adaptación, reparación, búsqueda de sistemas donantes y exaptación modular.

---

# 1 · Qué es el razonamiento funcional

El **razonamiento funcional** consiste en observar un sistema desde aquello que **hace**, independientemente de la forma específica que adopta para hacerlo.

En diseño e ingeniería suele aparecer relacionado con prácticas como:

- functional analysis;
- functional decomposition;
- function structures;
- systems architecture;
- block diagrams;
- fault isolation;
- reverse engineering.

El vocabulario cambia entre disciplinas, pero la capacidad básica es semejante:

> **seguir qué entra a un sistema, qué transformaciones ocurren, qué sale, qué controla esas transformaciones y qué subsistemas permiten que ocurran.**

---

## Cuatro flujos para seguir

Una manera accesible de comenzar consiste en buscar cuatro tipos de flujo.

| Flujo | Pregunta |
|---|---|
| **Energía** | ¿De dónde entra la energía, cómo se transforma y dónde termina? |
| **Materia** | ¿Qué sustancia u objeto físico entra, qué le ocurre y qué sale? |
| **Información** | ¿Qué detecta el sistema, qué instrucciones recibe y qué comunica? |
| **Movimiento / fuerza** | ¿Qué se mueve, qué fuerza se transmite y qué efecto mecánico produce? |

No todos los productos contienen los cuatro con la misma importancia.

Un computador trabaja principalmente con **energía + información + calor**.  
Una aspiradora trabaja con **energía + movimiento + aire + partículas**.  
Una cafetera trabaja con **energía + agua + calor + control**.  
Un taladro trabaja con **energía + movimiento + torque + control**.

---

# 2 · Cómo leer cada ejemplo

Cada producto de este glosario se presenta en dos niveles.

### Función global

Describe aquello que el sistema completo consigue realizar.

### Parte / subsistema → función local

Relaciona componentes físicos reconocibles con la operación que realizan dentro del sistema.

Esta segunda capa es deliberadamente pedagógica.

En una descomposición funcional formal es posible construir primero una arquitectura de funciones sin asignarlas todavía a partes físicas. Aquí hacemos después el mapeo hacia componentes porque el workshop trabaja con **objetos reales que queremos poder abrir, reconocer y reutilizar**.

---

## Plantilla reutilizable

Para cualquier producto nuevo puedes utilizar esta estructura:

**Producto:**  
**Función global:**  

**Entradas:**  
- energía:
- materia:
- información:

**Transformaciones:**  
-  
-  
-  

**Salidas:**  
-  
-  

**Interfaces:**  
- usuario:
- energía:
- señales:
- mecánicas:

| Parte / subsistema | Función que realiza | Flujo principal |
|---|---|---|
| | | |

---

# 3 · Computación y electrónica

## 3.1 · Computador portátil

**Función global:** recibir, procesar, almacenar y comunicar información en un sistema portátil con interfaz integrada.

| Parte / subsistema | Función |
|---|---|
| batería | almacenar energía eléctrica |
| circuito de carga | controlar entrada de energía hacia la batería |
| reguladores / PMIC | transformar y distribuir distintos niveles de voltaje |
| CPU / SoC | ejecutar operaciones sobre información |
| RAM | mantener información temporalmente disponible |
| SSD | almacenar información persistentemente |
| pantalla | convertir señales electrónicas en información visual |
| teclado | convertir acciones mecánicas del usuario en señales discretas |
| touchpad | convertir movimiento superficial en coordenadas |
| Wi-Fi / Bluetooth | convertir información digital en señales de radio y viceversa |
| micrófono | convertir vibraciones del aire en señal eléctrica |
| parlantes | convertir señal eléctrica en vibración del aire |
| heatpipe / disipador | transportar y distribuir calor |
| ventilador | mover aire para retirar calor |
| bisagras | permitir movimiento angular manteniendo una unión estructural |
| carcasa | posicionar, soportar y proteger subsistemas |

### Cadena funcional principal

`energía`
→ `regulación`
→ `procesamiento`
→ `almacenamiento / comunicación`
→ `output visual / sonoro`

### Qué puede volverse módulo

Pantalla, SSD, Wi-Fi antennas, speakers, webcam, teclado, ventilador, disipador, cargador, carcasa y, en algunos proyectos, la placa completa.

---

## 3.2 · Smartphone

**Función global:** procesar información, conectarse a redes y ofrecer sensores e interfaces dentro de un sistema móvil integrado.

| Parte / subsistema | Función |
|---|---|
| batería | almacenar energía |
| PMIC | regular y distribuir energía |
| SoC | procesar información y ejecutar instrucciones |
| memoria | almacenar instrucciones y datos |
| display | producir output visual |
| digitalizador táctil | convertir contacto y posición en información |
| cámara | convertir luz en información digital |
| micrófonos | convertir sonido en señal |
| parlantes | convertir señal en sonido |
| modem celular | intercambiar información con redes celulares |
| Wi-Fi / Bluetooth | comunicación inalámbrica de corto y medio alcance |
| GNSS/GPS | estimar posición desde señales externas |
| acelerómetro | detectar aceleración |
| giroscopio | detectar rotación |
| sensor de proximidad | detectar presencia cercana |
| USB | transferir energía y/o información |
| carcasa | contener, posicionar y proteger módulos |

### Observación para exaptación

Un teléfono viejo puede ser más útil **sin desmontarlo** porque ya integra:

`computador + pantalla + touch + batería + radio + cámaras + sensores + almacenamiento`

Antes de extraer una pieza conviene preguntar si el aparato completo puede migrar como módulo hacia otro sistema.

---

## 3.3 · Router Wi-Fi

**Función global:** recibir, dirigir y retransmitir información entre redes cableadas e inalámbricas.

| Parte / subsistema | Función |
|---|---|
| fuente de alimentación | adaptar energía de entrada |
| reguladores | distribuir voltajes internos |
| CPU / SoC | procesar tráfico y ejecutar firmware |
| RAM | mantener datos temporales |
| flash | almacenar sistema y configuración |
| Ethernet PHY / switch | convertir y dirigir señales de red cableada |
| radio Wi-Fi | convertir información digital en señal RF y viceversa |
| antenas | acoplar energía eléctrica de alta frecuencia con ondas electromagnéticas |
| LEDs | comunicar estado |
| botones | recibir input físico |
| carcasa | proteger electrónica y posicionar antenas |

### Abstracción útil

Una antena de router no es funcionalmente “una antena de router”.

Es:

> **un elemento que acopla una señal eléctrica de radiofrecuencia con radiación electromagnética.**

---

## 3.4 · Impresora de inyección de tinta

**Función global:** convertir información digital en marcas físicas posicionadas sobre un medio.

| Parte / subsistema | Función |
|---|---|
| USB / Wi-Fi | recibir información |
| controlador | interpretar documento y coordinar movimientos |
| fuente | adaptar y distribuir energía |
| motor de carro | producir movimiento |
| correa | transmitir movimiento lineal al carro |
| riel | restringir el desplazamiento a una trayectoria |
| encoder strip | informar posición del carro |
| cabezal | depositar pequeñas cantidades de material |
| cartuchos | almacenar material de impresión |
| motor de papel | producir movimiento de alimentación |
| rodillos | transportar y posicionar papel |
| sensores | detectar presencia y posición |
| carcasa | alinear y proteger mecanismos |

### Cadena funcional principal

`datos`
→ `interpretación`
→ `posicionamiento`
→ `deposición de material`
→ `imagen física`

### Potencial como sistema donante

Motores, engranajes, rieles, sensores ópticos, encoders, switches, fuentes, resortes, rodillos y estructura.

---

## 3.5 · Monitor LCD

**Función global:** convertir una señal de video en una imagen visible.

| Parte / subsistema | Función |
|---|---|
| fuente | convertir alimentación de entrada en voltajes internos |
| placa principal | recibir e interpretar la señal de video |
| scaler | adaptar resolución y temporización |
| timing controller | coordinar actualización del panel |
| panel LCD | modular el paso de luz por píxel |
| backlight | producir iluminación |
| difusores | distribuir luz uniformemente |
| polarizadores | controlar transmisión de luz |
| botones | recibir input |
| stand | sostener y posicionar |
| carcasa | proteger y alinear subsistemas |

### Pregunta funcional

Si la placa principal muere pero el panel funciona:

> **¿Necesito reparar el monitor completo o solamente encontrar otra forma de recibir una señal y controlar ese panel?**

Ahí aparece el controller board como **módulo puente**.

---

# 4 · Electrodomésticos

## 4.1 · Ventilador

**Función global:** producir y dirigir un flujo de aire mediante movimiento mecánico.

| Parte / subsistema | Función |
|---|---|
| cable / fuente | transportar energía |
| interruptor | permitir o impedir suministro de energía |
| selector de velocidad | modificar condición de operación |
| motor | convertir electricidad en movimiento rotatorio |
| eje | transmitir torque |
| aspas | transferir momento al aire |
| rejilla | permitir paso de aire restringiendo contacto con partes móviles |
| mecanismo de oscilación | convertir rotación en desplazamiento angular alternativo |
| soporte | mantener el conjunto a una altura y orientación |
| base | distribuir carga y resistir vuelco |

### Cadena funcional principal

`electricidad`
→ `rotación`
→ `movimiento de aspas`
→ `transferencia de momento al aire`
→ `flujo de aire`

### Preguntas de entrenamiento

- ¿Qué parte convierte energía?
- ¿Qué parte transmite movimiento?
- ¿Qué parte interactúa directamente con el aire?
- ¿Qué parte existe únicamente para seguridad?
- ¿Qué funciones seguirían disponibles si las aspas se rompen?

---

## 4.2 · Aspiradora

**Función global:** remover, transportar, separar y almacenar partículas utilizando flujo de aire.

| Parte / subsistema | Función |
|---|---|
| cable / batería | suministrar energía |
| controlador | permitir y regular operación |
| motor | convertir electricidad en rotación |
| turbina / impeller | producir diferencial de presión |
| ductos | dirigir flujo de aire |
| boquilla | concentrar flujo sobre una superficie |
| cepillo | separar mecánicamente partículas adheridas |
| filtro | permitir paso de aire reteniendo partículas |
| depósito / bolsa | almacenar residuos |
| sellos | reducir pérdidas de presión |
| ruedas | reducir fricción durante desplazamiento |
| carcasa | posicionar y proteger subsistemas |

### Cadena funcional principal

`electricidad`
→ `rotación`
→ `diferencia de presión`
→ `flujo de aire`
→ `transporte de partículas`
→ `separación`
→ `almacenamiento`

---

## 4.3 · Lavadora

**Función global:** modificar una carga textil mediante agua, productos químicos, movimiento y control secuencial.

| Parte / subsistema | Función |
|---|---|
| válvula de entrada | controlar flujo de agua |
| tambor | contener carga permitiendo movimiento |
| motor | producir rotación |
| transmisión / direct drive | adaptar velocidad y torque |
| bomba | transportar agua |
| resistencia | convertir electricidad en calor |
| sensor de nivel | detectar cantidad de agua |
| sensor de temperatura | detectar estado térmico |
| controlador | secuenciar operaciones |
| puerta y sello | permitir acceso conteniendo líquido |
| bomba de drenaje | evacuar líquido |
| amortiguadores | reducir vibración transmitida a la estructura |
| carcasa | soportar y proteger el sistema |

### Flujos principales

**materia:** ropa + agua + detergente  
**energía:** electricidad → movimiento + calor  
**información:** sensores → controlador → actuadores

---

## 4.4 · Refrigerador

**Función global:** transferir calor desde un volumen interior hacia el ambiente.

| Parte / subsistema | Función |
|---|---|
| compresor | aumentar presión del refrigerante |
| condensador | transferir calor al ambiente |
| dispositivo de expansión | reducir presión del refrigerante |
| evaporador | absorber calor del interior |
| refrigerante | transportar energía térmica |
| ventiladores | mover aire para aumentar transferencia de calor |
| sensores / termostato | detectar temperatura |
| controlador | mantener rango térmico |
| aislamiento | reducir transferencia térmica no deseada |
| puerta | permitir acceso |
| sello | limitar intercambio de aire |
| sistema de deshielo | remover acumulación de hielo |

### Corrección conceptual importante

Un refrigerador no “crea frío”.

Funcionalmente:

> **transporta calor desde un lugar donde no lo queremos hacia otro donde podemos disiparlo.**

---

## 4.5 · Cafetera de goteo

**Función global:** almacenar, calentar, transportar y distribuir agua a través de material soluble y filtrante.

| Parte / subsistema | Función |
|---|---|
| depósito | almacenar agua |
| válvula | controlar dirección del flujo |
| calentador | transferir calor al agua |
| tubo | transportar líquido |
| mecanismo termo-hidráulico | impulsar agua caliente hacia arriba |
| dispersor | distribuir agua sobre material |
| filtro / basket | permitir paso de líquido reteniendo sólidos |
| recipiente | contener producto final |
| placa caliente | mantener temperatura |
| interruptor / control | permitir operación |
| carcasa | posicionar y proteger subsistemas |

### Potencial de reutilización

Carcasa, depósito, bandeja, switch, tubo, calentador, sensores térmicos y estructura pueden seguir disponibles aunque la función “hacer café” haya muerto.

---

# 5 · Herramientas eléctricas de cocina

## 5.1 · Licuadora

**Función global:** fragmentar y mezclar material mediante movimiento rotatorio de alta velocidad.

| Parte / subsistema | Función |
|---|---|
| cable / fuente | suministrar energía |
| motor | convertir electricidad en rotación |
| control de velocidad | modificar energía entregada al motor |
| acople | transmitir torque desde motor al conjunto de cuchillas |
| eje | mantener y transmitir rotación |
| cuchillas | concentrar fuerza sobre material |
| jarra | contener materia durante transformación |
| tapa | impedir salida de material |
| sello | impedir fuga de líquido |
| base | sostener y estabilizar el sistema |
| interlock | impedir operación en una configuración insegura |

---

## 5.2 · Hervidor eléctrico

**Función global:** elevar la temperatura de un volumen de agua de forma controlada.

| Parte / subsistema | Función |
|---|---|
| contactos de base | transferir energía permitiendo separación física |
| resistencia | convertir electricidad en calor |
| recipiente | contener líquido |
| sensor / termostato | detectar condición térmica |
| trayectoria de vapor | transportar señal física de ebullición hacia el mecanismo de corte |
| interruptor automático | interrumpir energía al alcanzar una condición |
| asa | permitir manipulación reduciendo transferencia de calor |
| tapa | permitir acceso y limitar salpicadura/pérdida |
| indicador | comunicar estado |

---

## 5.3 · Procesador de alimentos

**Función global:** aplicar distintas transformaciones mecánicas a alimentos dentro de un sistema modular.

| Parte / subsistema | Función |
|---|---|
| motor | producir rotación |
| transmisión | adaptar y transferir torque |
| eje / spindle | entregar rotación a accesorios |
| bowl | contener material |
| cuchilla | cortar / triturar |
| disco rallador | fragmentar mediante bordes distribuidos |
| accesorios | cambiar la transformación disponible |
| tapa | contener material |
| interlock | impedir operación con el bowl abierto |
| controles | seleccionar estado / velocidad |
| carcasa | soportar motor y geometría del sistema |

### Idea importante

El mismo motor + transmisión puede realizar múltiples funciones porque **la transformación final cambia al reemplazar el módulo que interactúa con el alimento**.

---

## 5.4 · Tostador

**Función global:** transferir energía térmica de manera controlada hacia superficies de alimento.

| Parte / subsistema | Función |
|---|---|
| elementos resistivos | convertir electricidad en radiación y calor |
| ranuras / guías | posicionar alimento |
| palanca | recibir input mecánico |
| mecanismo de retención | mantener alimento en posición |
| resorte | almacenar energía mecánica |
| temporizador / controlador | determinar duración |
| sensor / circuito de browning | estimar condición de tostado |
| mecanismo de liberación | liberar la retención |
| crumb tray | recoger material desprendido |
| carcasa | contener y proteger |

### Cadena funcional

`electricidad`
→ `calor`
→ `transferencia térmica`
→ `transformación del alimento`

con una segunda cadena:

`input del usuario`
→ `retención`
→ `temporización`
→ `liberación`

---

## 5.5 · Batidora eléctrica de mano

**Función global:** transferir movimiento rotatorio a herramientas removibles para mezclar o incorporar aire.

| Parte / subsistema | Función |
|---|---|
| motor | producir rotación |
| engranajes | adaptar velocidad y torque |
| ejes de salida | transmitir rotación |
| batidores | transferir movimiento al material |
| selector | regular velocidad |
| botón eject | liberar accesorios |
| carcasa | contener y alinear mecanismos |
| mango | permitir control humano |
| ventilación | retirar calor del motor |

---

# 6 · Herramientas domésticas eléctricas

Estas herramientas son especialmente útiles para el workshop porque contienen conversiones de energía y mecanismos que **no son evidentes desde el gesto humano que las controla**.

Un martillo manual prolonga directamente una acción corporal reconocible.  
Un taladro, una sierra caladora o una lijadora eléctrica esconden cadenas de conversión, transmisión y regulación mucho más ricas para descomponer.

---

## 6.1 · Taladro inalámbrico

**Función global:** producir movimiento rotatorio controlado y transmitir torque a una herramienta intercambiable.

| Parte / subsistema | Función |
|---|---|
| batería | almacenar energía |
| contactos | transferir energía entre módulos separables |
| gatillo / controlador PWM | recibir input y regular potencia |
| selector de reversa | invertir dirección de rotación |
| motor | convertir electricidad en movimiento rotatorio |
| caja de engranajes | modificar relación velocidad/torque |
| embrague | limitar torque transmitido |
| chuck | acoplar herramientas de diferentes diámetros |
| eje / rodamientos | transmitir rotación reduciendo fricción |
| LED | iluminar zona de trabajo |
| carcasa / mango | soportar componentes y transmitir reacción a la mano |

### Cadena funcional principal

`energía almacenada`
→ `control`
→ `rotación rápida`
→ `adaptación velocidad/torque`
→ `acoplamiento`
→ `herramienta`

### Funciones recuperables

Motor, gearbox, chuck, battery pack, trigger, LEDs, bearings y carcasa pueden convertirse en módulos de otros proyectos.

---

## 6.2 · Sierra caladora

**Función global:** convertir movimiento rotatorio en movimiento alternativo para separar material siguiendo una trayectoria guiada.

| Parte / subsistema | Función |
|---|---|
| cable / batería | suministrar energía |
| gatillo / control | regular operación |
| motor | producir rotación |
| mecanismo excéntrico / crank | convertir rotación en movimiento lineal alternativo |
| guía | mantener trayectoria del movimiento |
| blade clamp | sujetar herramienta de corte |
| hoja | concentrar esfuerzo para separar material |
| shoe / base | apoyar herramienta y controlar ángulo |
| mecanismo orbital | añadir componente de movimiento para modificar corte |
| blower / ducto | retirar polvo de la línea de corte |
| carcasa | contener y alinear mecanismos |

### Idea funcional central

La caladora es un ejemplo excelente de **conversión de movimiento**:

`rotación`
→ `movimiento alternativo`

Ese mecanismo puede tener usos fuera del corte.

---

## 6.3 · Lijadora orbital

**Función global:** producir movimiento oscilante controlado sobre una superficie para remover pequeñas cantidades de material.

| Parte / subsistema | Función |
|---|---|
| cable / batería | suministrar energía |
| interruptor / controlador | regular operación |
| motor | producir rotación |
| contrapeso excéntrico | convertir rotación en movimiento orbital |
| pad | distribuir movimiento sobre superficie |
| sistema hook-and-loop | fijar consumible permitiendo reemplazo |
| abrasivo | remover material por fricción |
| ventilador / puertos | transportar polvo |
| depósito / conexión de aspiración | recoger o evacuar partículas |
| carcasa / grip | permitir control y aislar al usuario |

### Flujo principal

`electricidad`
→ `rotación`
→ `movimiento excéntrico`
→ `fricción distribuida`
→ `remoción de material`

---

## 6.4 · Pistola de calor

**Función global:** producir y dirigir un flujo de aire caliente regulable.

| Parte / subsistema | Función |
|---|---|
| cable | suministrar energía |
| switch / selector | controlar estado y potencia |
| motor | producir rotación |
| impeller | mover aire |
| resistencia | convertir electricidad en calor |
| ducto | obligar al aire a pasar por la zona caliente |
| sensor / termostato | limitar temperatura |
| thermal fuse | interrumpir energía ante sobretemperatura |
| boquilla | dirigir y concentrar flujo |
| carcasa / aislación | proteger y permitir manipulación |

### Dos cadenas acopladas

`electricidad → motor → flujo de aire`

y

`electricidad → resistencia → calor`

que se combinan como:

`aire + calor → flujo de aire caliente dirigido`

---

## 6.5 · Herramienta rotatoria tipo Dremel

**Función global:** producir movimiento rotatorio de alta velocidad para herramientas intercambiables.

| Parte / subsistema | Función |
|---|---|
| fuente / batería | suministrar energía |
| control de velocidad | regular energía entregada |
| motor | producir rotación |
| eje | transmitir movimiento |
| rodamientos | permitir rotación reduciendo fricción |
| collet / chuck | sujetar accesorios diferentes |
| ventilador interno | mover aire para disipar calor |
| carcasa | alinear y proteger |
| accesorios | convertir la rotación en corte, pulido, lijado, perforación u otras operaciones |

### Idea importante

La herramienta completa mantiene casi toda su arquitectura.

La **función final** cambia al intercambiar el accesorio.

Esto permite observar claramente la diferencia entre:

> **capacidad del sistema:** producir rotación controlada

y

> **función específica del accesorio:** cortar / pulir / lijar / perforar.

---

# 7 · Automotriz: subsistemas eléctricos y electromecánicos

En automoción resulta útil no intentar descomponer “el automóvil completo” de una vez.

Trabajamos con subsistemas que ya tienen límites funcionales reconocibles.

---

## 7.1 · Motor de arranque

**Función global:** convertir energía eléctrica almacenada en torque suficiente para iniciar la rotación del motor de combustión.

| Parte / subsistema | Función |
|---|---|
| batería | almacenar energía |
| cableado de alta corriente | transportar energía |
| solenoide | convertir señal de control en desplazamiento y cierre de circuito de potencia |
| motor eléctrico | convertir electricidad en rotación |
| pinion | transferir torque |
| mecanismo Bendix | acoplar temporalmente el pinion |
| overrunning clutch | impedir transmisión inversa peligrosa |
| flywheel | recibir torque e iniciar movimiento del motor |
| carcasa | posicionar y soportar mecanismos |

---

## 7.2 · Alternador

**Función global:** convertir movimiento mecánico del motor en energía eléctrica regulada.

| Parte / subsistema | Función |
|---|---|
| polea | recibir torque |
| rotor | producir campo magnético móvil |
| estator | convertir variación de campo magnético en corriente |
| rectificador | convertir AC en DC |
| regulador | mantener voltaje dentro de rango |
| rodamientos | permitir rotación reduciendo fricción |
| ventilación | retirar calor |
| carcasa | soportar y alinear componentes |

### Cadena funcional

`rotación mecánica`
→ `campo magnético variable`
→ `electricidad AC`
→ `rectificación`
→ `electricidad DC regulada`

---

## 7.3 · Limpiaparabrisas eléctrico

**Función global:** convertir rotación continua en movimiento oscilante sincronizado sobre una superficie.

| Parte / subsistema | Función |
|---|---|
| switch | recibir input del usuario |
| relay / controlador | seleccionar modo y temporización |
| motor | convertir electricidad en rotación |
| worm gear | reducir velocidad y aumentar torque |
| crank | convertir rotación en desplazamiento alternativo |
| linkage | distribuir movimiento a varios puntos |
| pivotes | permitir rotación localizada |
| brazos | transmitir movimiento |
| escobillas | desplazar agua y partículas |
| park switch | detectar posición de reposo |

### Ejemplo de conversión

`rotación`
→ `movimiento alternativo`
→ `barrido angular`

---

## 7.4 · Elevalunas eléctrico

**Función global:** convertir energía eléctrica en movimiento lineal controlado de un panel de vidrio.

| Parte / subsistema | Función |
|---|---|
| switch | recibir orden |
| controlador / relay | dirigir energía |
| motor | producir rotación |
| worm gear | reducir velocidad y aumentar torque |
| regulador de cable o tijera | convertir rotación en desplazamiento lineal |
| guías | restringir trayectoria |
| soportes | transmitir fuerza al vidrio |
| sensores / current sensing | detectar obstrucción o fin de recorrido |
| estructura | mantener alineación |

---

## 7.5 · Conjunto de ventilador de radiador

**Función global:** aumentar el flujo de aire a través del intercambiador de calor cuando la circulación natural no es suficiente.

| Parte / subsistema | Función |
|---|---|
| sensor de temperatura | detectar condición térmica |
| ECU / controlador | decidir cuándo activar |
| relay / driver | controlar potencia |
| motor | convertir electricidad en rotación |
| aspas | transferir momento al aire |
| shroud | dirigir flujo a través del radiador |
| montajes | posicionar y aislar vibración |
| conector / cableado | transportar energía y señal |

### Homología interesante

El ventilador doméstico y el ventilador de radiador comparten gran parte de su arquitectura funcional:

`electricidad → rotación → flujo de aire`

pero están integrados en sistemas completamente distintos.

Ésta es exactamente la clase de equivalencia que el razonamiento funcional permite detectar.

---

# 8 · Cómo se entrena esta capacidad

El razonamiento funcional no se entrena memorizando nombres de piezas.

Se entrena repitiendo ciertas operaciones hasta que empiezan a aparecer espontáneamente al observar un objeto.

---

## Ejercicio 1 · Prohibir temporalmente el nombre del producto

En vez de:

> “esto es una aspiradora”

describir:

> “este sistema crea un flujo de aire que transporta partículas, las separa del flujo y las almacena”.

En vez de:

> “esto es una pistola de calor”

describir:

> “este sistema produce aire en movimiento, le transfiere energía térmica y concentra el flujo en una salida”.

La identidad comercial del producto deja de ser la explicación.

---

## Ejercicio 2 · Seguir los flujos

Pregunta:

### ¿Qué entra?

- energía;
- agua;
- aire;
- alimento;
- datos;
- fuerza humana.

### ¿Qué cambia?

- temperatura;
- presión;
- velocidad;
- forma;
- posición;
- estado de información.

### ¿Qué sale?

- movimiento;
- calor;
- aire;
- señal;
- imagen;
- sonido;
- material transformado.

---

## Ejercicio 3 · Preguntar “¿cómo?” hacia abajo

Ejemplo:

> El ventilador mueve aire.

¿Cómo?

> Hace girar aspas.

¿Cómo?

> Un eje transmite movimiento.

¿Cómo?

> Un motor produce rotación.

¿Cómo?

> Convierte energía eléctrica en movimiento.

Cada “¿cómo?” tiende a llevarnos hacia **subfunciones y mecanismos**.

---

## Ejercicio 4 · Preguntar “¿para qué?” hacia arriba

> El motor gira.

¿Para qué?

> Para mover el eje.

¿Para qué?

> Para mover las aspas.

¿Para qué?

> Para transferir momento al aire.

¿Para qué?

> Para producir flujo.

Cada “¿para qué?” reconstruye el camino hacia la **función global**.

---

## Ejercicio 5 · Separar función de solución física

Pregunta:

> **¿Es necesario que esta función la realice esta pieza particular?**

Necesito:

`mover aire`

Posibles medios:

- fan axial;
- blower centrífugo;
- compressor;
- bellows;
- convection;
- piston pump.

La función permanece.

La solución física cambia.

---

## Ejercicio 6 · Buscar homologías entre dominios

Ejemplos:

`controlar agua` → válvula  
`controlar electricidad` → switch  
`controlar luz` → shutter  
`controlar información` → gate / router

Todos pueden abstraerse como:

> **regular un flujo**

Otro ejemplo:

`motor + crank` en una caladora  
y  
`motor + crank` en un limpiaparabrisas

pueden realizar funciones finales completamente diferentes mientras comparten una conversión:

> **rotación → movimiento alternativo**

Cuando una persona empieza a detectar estas homologías, el razonamiento funcional está dejando de ser un ejercicio y empieza a convertirse en una manera de mirar sistemas.

---

# 9 · Para qué se ocupa

## Comprender

Cuando no sabemos cómo funciona una máquina, podemos reconstruir:

`entrada → transformaciones → salida`

sin necesitar reconocer inmediatamente cada componente.

---

## Diagnosticar

Si una función deja de ocurrir, recorremos la cadena.

Ejemplo:

> el ventilador no mueve aire.

¿Las aspas giran?

No.

¿El eje gira?

No.

¿El motor recibe energía?

Sí.

El problema está probablemente dentro de la transición:

`energía eléctrica → movimiento rotatorio`

o en la transmisión inmediata.

---

## Diseñar

Cuando necesitamos una función pero no tenemos la solución convencional:

> **¿qué otra cosa disponible puede realizar una función equivalente?**

---

## Sustituir

Si un componente no existe o no podemos conseguirlo:

> **¿qué requisitos funcionales debe cumplir el reemplazo?**

---

## Buscar sistemas donantes

En vez de buscar solamente:

> “repuesto para aparato X”

podemos preguntar:

> **¿en qué otros productos existe un módulo que ya realice esta función?**

---

## Recombinar

Podemos identificar varios módulos existentes y construir una arquitectura nueva alrededor de ellos.

---

# 10 · Profesiones donde esta capacidad es central

La habilidad puede recibir nombres distintos según la profesión, pero aparece de manera muy consistente.

| Profesión / campo | Cómo utiliza razonamiento funcional |
|---|---|
| **Ingeniería mecánica** | mecanismos, transferencia de fuerza, movimiento, energía y diseño de máquinas |
| **Ingeniería de sistemas** | funciones, subsistemas, interfaces, entradas, salidas y dependencias |
| **Ingeniería eléctrica / electrónica** | bloques funcionales, power paths, signal paths y control |
| **Mecatrónica** | integración de funciones mecánicas, electrónicas y de software |
| **Product Design Engineering** | traducir necesidades en funciones antes de escoger componentes |
| **Diseño industrial** | relacionar función, interacción, forma, material y fabricación |
| **Mantenimiento industrial** | localizar qué función dejó de cumplirse y qué subsistema la realiza |
| **Reliability engineering** | analizar modos de falla y consecuencias funcionales |
| **Técnicos de reparación** | seguir energía, señal, movimiento o flujo hasta localizar una falla |
| **Reparación de electrodomésticos** | diagnóstico por cadenas funcionales y sustitución de módulos |
| **Diagnóstico automotriz** | separar el vehículo en subsistemas y seguir energía, señal, fluidos y movimiento |
| **Reverse engineering** | inferir propósito y relaciones desde estructura y comportamiento |
| **Robótica** | percepción → procesamiento → decisión → actuación |
| **Embedded systems** | relacionar sensores, cómputo, interfaces y actuadores |
| **Manufacturing engineering** | dividir producción en operaciones funcionales |
| **Biomedical engineering** | reproducir funciones biológicas mediante sistemas técnicos |
| **Prótesis y rehabilitación** | identificar una función corporal y construir otra arquitectura que la realice |
| **Hardware hacking / maker practice** | reutilizar partes por capacidad y no sólo por identidad original |

---

# 11 · Cómo reconocer progreso

Una progresión típica puede verse así.

### Nivel 1 · Identidad del producto

> “Es una cafetera.”

### Nivel 2 · Componentes

> “Tiene calentador, tubos y switch.”

### Nivel 3 · Funciones locales

> “El calentador transfiere energía al agua; los tubos transportan líquido; el switch controla energía.”

### Nivel 4 · Arquitectura funcional

> “El sistema almacena líquido, transfiere calor, transporta fluido, distribuye material y controla una secuencia.”

### Nivel 5 · Transferencia

> “Necesito mover una pequeña cantidad de líquido caliente. No necesito una cafetera: necesito contener, calentar, transportar y controlar líquido.”

### Nivel 6 · Búsqueda funcional

> “¿Qué otros aparatos contienen al menos tres de esas capacidades y podrían funcionar como sistema donante?”

Ahí la categoría comercial del producto dejó de delimitar el espacio de soluciones.

---

# 12 · Usar IA para entrenar razonamiento funcional

La IA puede participar desde el principio.

Después de una primera descomposición humana o grupal:

> **“Estoy analizando un ventilador. Mi lista actual de funciones es: recibir energía, convertir electricidad en rotación, transmitir movimiento, mover aire y proteger al usuario. Amplía la descomposición. Separa funciones de energía, movimiento, información y estructura. No propongas todavía otros productos.”**

Después:

> **“Para cada función, indica qué parte o subsistema del ventilador normalmente la realiza. Señala las funciones que dependen de más de una pieza.”**

Y luego:

> **“Busca productos de categorías distintas que contengan al menos tres de estas funciones. No incluyas otros ventiladores ni productos diseñados principalmente para mover aire.”**

La IA pasa así de explicar el objeto a realizar **búsqueda funcional transversal**.

---

# 13 · Relación con Generic Parts Technique

Este documento está dedicado a **functional reasoning / functional decomposition**.

No es todavía Generic Parts Technique.

La diferencia práctica es:

### Functional decomposition

Pregunta:

> **¿Qué hace esta parte dentro del sistema?**

Ejemplo:

`motor → convertir electricidad en rotación`

### Generic Parts Technique

Pregunta:

> **¿Qué es físicamente esta parte si dejo de nombrarla por su función convencional?**

Ejemplo posible:

`motor`

→ conjunto compacto  
→ carcasa metálica cilíndrica  
→ eje rígido que puede girar  
→ cobre enrollado  
→ imanes  
→ elementos que permiten rotación

Una técnica abstrae hacia **función**.

La otra desarma las etiquetas convencionales hacia **propiedades físicas**.

En el workshop pueden trabajar una después de la otra sobre el mismo objeto.

---

## Idea central

El razonamiento funcional empieza a volverse útil cuando dejamos de preguntar únicamente:

> **¿Qué producto necesito?**

y empezamos a preguntar:

> **¿Qué tiene que ocurrir?**  
> **¿Qué funciones necesito?**  
> **¿Qué partes realizan esas funciones?**  
> **¿Qué otros objetos ya contienen esas capacidades?**

Esa última pregunta convierte el análisis en una herramienta directa para construir con lo que ya existe.

---

*Contenido y adaptación © Sandra Acevedo · Multiverse School.*
