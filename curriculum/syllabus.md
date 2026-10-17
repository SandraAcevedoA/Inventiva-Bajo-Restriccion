# Inventiva Bajo Restricción con IA

**Serie:** Discernimiento humano y creatividad soberana mediada por IA  
**Capítulo:** 2 de 3  
**Duración:** 3 horas  
**Formato:** Workshop remoto, aplicado y participativo  
**Idioma:** Español  
**Nivel:** Todos los niveles  
**Requisitos previos:** Ninguno

## Descripción

Cuando un aparato deja de cumplir su función original tendemos a verlo como una unidad fallida: una cafetera rota, un teléfono con la pantalla dañada, un computador demasiado viejo.

Este workshop propone cambiar la unidad de análisis.

En lugar de preguntar solamente cómo reparar o reemplazar un producto, trabajaremos con herramientas provenientes del diseño de ingeniería y la psicología cognitiva para identificar **funciones, propiedades físicas, capacidades, interfaces y módulos que siguen disponibles dentro de objetos existentes**.

La inteligencia artificial acompañará ese proceso ayudando a descomponer sistemas, identificar componentes y funciones, buscar equivalencias, encontrar módulos donantes, investigar interfaces y compatibilidades, explorar usos alternativos y desarrollar nuevas configuraciones.

El recorrido conceptual será:

**functional reasoning → functional decomposition → functional fixedness → Generic Parts Technique → modular exaptation**

pero el workshop no está organizado como una secuencia de clases teóricas. Los conceptos aparecen cuando permiten hacer la siguiente operación sobre objetos y problemas reales.

---

# Pregunta central

> **¿Qué podemos construir con las capacidades que ya existen dentro de los objetos y tecnologías que tenemos disponibles?**

Pregunta práctica complementaria:

> **Cuando un producto deja de servir como producto, ¿qué sigue siendo útil dentro de él?**

---

# Objetivos de aprendizaje

Al finalizar el workshop, las personas participantes podrán:

- distinguir entre **producto y función**;
- realizar una descomposición funcional básica de un objeto o sistema;
- identificar **entradas, transformaciones, salidas, interfaces y dependencias** relevantes;
- reconocer la fijación funcional;
- utilizar una versión práctica de la **Generic Parts Technique**;
- describir componentes por sus propiedades materiales, geométricas y estructurales;
- identificar módulos reutilizables dentro de hardware u objetos en desuso;
- reconocer posibilidades de **reparación, sustitución, bypass, adaptación, recombinación y exaptación**;
- utilizar IA para investigar componentes, documentación, equivalencias funcionales, interfaces y compatibilidad;
- distinguir entre hipótesis técnicas, documentación, compatibilidad confirmada, compatibilidad probable, incógnita y riesgo;
- desarrollar una configuración nueva utilizando funciones, partes o módulos ya disponibles.

---

# Para quién es este workshop

Personas interesadas en:

- repair y reutilización tecnológica;
- e-waste y hardware scavenging;
- cyberdecks y small computing;
- DIY y fabricación;
- electrónica y sistemas personalizados;
- upcycling funcional;
- tecnología apropiada;
- diseño desde recursos realmente disponibles;
- formas prácticas de incorporar IA en procesos materiales y técnicos.

No se requiere experiencia previa en electrónica, programación, ingeniería o reparación.

---

# Qué vas a necesitar

- computador con acceso a internet;
- un modelo generalista de IA;
- idealmente acceso a un modelo capaz de trabajar con imágenes;
- objetos reales, fotografías o dispositivos en desuso sobre los que trabajar;
- un lugar donde registrar funciones, partes, hipótesis, recursos y decisiones.

No es necesario construir físicamente el prototipo durante la sesión.

---

# BLOQUE 0 · El objeto que murió
**15 min**

## Entrada

Abrir con un objeto real.

Ejemplos posibles:

- cafetera rota;
- HP All-in-One obsoleto;
- Pixel 6 con pantalla dañada;
- algún proyecto rata;
- otro electrodoméstico o dispositivo común.

No comenzar con una definición académica.

Comenzar con una pregunta:

> **Este objeto ya no sirve como producto. ¿Qué queda?**

Mostrar que el fallo de una función o del sistema completo no implica que hayan desaparecido:

- materiales;
- partes;
- capacidades;
- interfaces;
- módulos;
- estructuras;
- mecanismos.

## Mini ejemplo

Cafetera rota:

`cafetera`
↓
carcasa  
cavidad  
tapa articulada  
bandeja  
depósito  
switch  
cable  
elementos de calentamiento  
mecanismos internos

La actividad central del workshop empieza a insinuarse desde aquí.

---

# BLOQUE 1 · De producto a funciones
**25 min**

## Functional Reasoning

Introducción breve.

Un producto llega a nosotros empaquetado como una identidad:

> cafetera  
> teléfono  
> impresora  
> computador

El razonamiento funcional cambia la pregunta:

> **¿Qué hace este sistema?**

y después:

> **¿Qué tiene que hacer cada parte para que el sistema funcione?**

---

## Functional Decomposition

Ejemplo con un aparato cotidiano.

No:

> cafetera = hacer café

Sí:

- contener líquido;
- mover líquido;
- calentar;
- controlar flujo;
- recibir input;
- soportar recipiente;
- alojar componentes;
- suministrar energía;
- proteger elementos internos.

Añadir cuando sea útil:

- **entrada**
- **transformación**
- **salida**
- **interfaz**
- **dependencia**

Ejemplo:

`entrada: energía eléctrica + agua`
↓
`transformación: calentar + transportar`
↓
`salida: agua caliente controlada`

Esto vuelve mucho más fácil investigar equivalencias.

---

## Uso de IA

Los participantes pueden entregarle a la IA su primera descomposición y pedirle que:

- encuentre funciones omitidas;
- agrupe funciones;
- proponga una formulación más abstracta;
- identifique entradas y salidas;
- encuentre interfaces;
- busque otros objetos que reúnan varias de esas funciones.

Pregunta especialmente importante:

> **¿En qué otros aparatos existe esta función o un módulo que la realice?**

---

## Caso real: Pixel 6

Problema aparente:

> pantalla dañada.

Problema funcional:

> necesitamos externalizar la interfaz visual.

Investigación:

> ¿qué tecnologías permiten hacerlo?

↓

DisplayLink / adapters / docks / bridges.

Después:

> **¿Qué aparatos antiguos contienen esa tecnología y podrían encontrarse usados?**

Aquí aparece una idea que debe mantenerse durante todo el workshop:

**el objeto que buscamos puede ser un módulo puente o una interfaz, no necesariamente el componente final.**

---

### [IFRAME · GRAFO DE CONCEPTOS]

**Insertar aquí iframe correspondiente al grafo conceptual.**

Nodos sugeridos visibles:

- functional reasoning
- functional decomposition
- function vs product
- interface
- capability
- component
- architecture

`<!-- IFRAME: GRAFO CONCEPTOS -->`

---

# BLOQUE 2 · Primera ventana histórica
**10 min**

No convertirlo en "la sección de historia".

Introducir un ejemplo breve que muestre cómo las personas han tenido que resolver problemas desde funciones y recursos disponibles en contextos de:

- escasez;
- falta de repuestos;
- acceso limitado;
- aislamiento tecnológico;
- infraestructuras incompletas.

La función de esta intervención es:

> mostrar que estas operaciones no nacieron con ChatGPT ni con la cultura maker contemporánea.

Mostrar uno o dos casos y volver al objeto.

---

### [IFRAME · GRAFO DE FENÓMENOS DE INVENTIVA]

**Insertar aquí iframe correspondiente al grafo de fenómenos de inventiva bajo restricción.**

Posibles entradas:

- bricolage
- jugaad
- gambiarra
- rikimbili
- scavenging
- reparación improvisada
- sustitución
- adaptación

`<!-- IFRAME: GRAFO FENOMENOS INVENTIVA -->`

---

# BLOQUE 3 · Lo que el nombre esconde
**20 min**

## Functional Fixedness

Introducción mínima.

Cuando conocemos demasiado bien un objeto, su función habitual puede volverse una etiqueta cognitiva.

Ejemplo:

problema de los tres switches y tres ampolletas.

La solución aparece al considerar una propiedad que el framing inicial ocultaba:

> la ampolleta no sólo produce luz; también produce calor y tarda en enfriarse.

No necesitamos otra lógica.

Necesitamos otra propiedad.

---

## Generic Parts Technique

Tony McCaffrey.

El procedimiento busca eliminar progresivamente nombres que codifican el uso convencional del componente.

Ejemplo:

**switch**

Evitar:

> dispositivo que abre o cierra un circuito.

Evitar incluso:

> dos contactos conductores cuya continuidad puede alterarse.

Llevarlo hacia algo como:

- dos pequeñas piezas metálicas planas;
- una pieza metálica flexible;
- piezas plásticas rígidas;
- pequeñas superficies que pueden tocarse;
- una estructura que puede mantener más de una posición;
- un pequeño mecanismo de movimiento.

Material.

Forma.

Tamaño.

Flexibilidad.

Movimiento.

Relación espacial.

---

## Demo con objeto real

La bandeja de una cafetera:

> bandeja para taza

↓

> pieza removible  
> plástico rígido  
> superficie aproximadamente plana  
> borde elevado  
> capaz de soportar peso  
> capaz de recoger material o líquido

En ese momento ya no estamos viendo únicamente "una pieza de cafetera".

---

## Uso de IA

La IA puede:

- ayudar a identificar partes;
- describir materiales;
- identificar geometrías;
- señalar palabras que siguen escondiendo función;
- enumerar propiedades físicas;
- reconocer movimientos, articulaciones, cavidades o superficies;
- proponer usos alternativos desde esas propiedades.

---

### [IFRAME · GRAFO DE CONCEPTOS]

**Insertar aquí nuevamente iframe al grafo conceptual, enfocado en:**

- functional fixedness
- Generic Parts Technique
- design fixation, sólo si resulta necesario
- properties
- material
- form
- structure

`<!-- IFRAME: GRAFO CONCEPTOS / FUNCTIONAL FIXEDNESS + GPT -->`

---

### [IFRAME · GRAFO DE TÉCNICAS]

**Insertar aquí iframe correspondiente al grafo de técnicas.**

Técnicas relacionadas:

- functional decomposition
- Generic Parts Technique
- constraint relaxation
- substitution
- functional abstraction

`<!-- IFRAME: GRAFO TECNICAS -->`

---

# PAUSA
**15 min**

---

# BLOQUE 4 · Del aparato al banco de módulos
**25 min**

## Modular Exaptation

Éste es el aterrizaje principal.

Un dispositivo puede dejar de servir como sistema completo y seguir siendo:

> una biblioteca de módulos.

Ejemplos:

**laptop**

→ display  
→ webcam  
→ speakers  
→ battery  
→ keyboard  
→ antennas  
→ storage

**impresora**

→ motors  
→ rails  
→ gears  
→ sensors  
→ power supply  
→ enclosure

**All-in-One**

→ display  
→ speakers  
→ enclosure  
→ stand  
→ buttons  
→ cabling

---

## Qué significa migrar un módulo

Un módulo puede:

### Mantener su función

Una pantalla sigue siendo pantalla dentro de otro sistema.

### Cambiar su función

Un mecanismo, superficie o componente puede cumplir otra tarea distinta.

---

## Caso principal

HP All-in-One obsoleto.

El computador integrado ya no resulta útil.

Pero:

`pantalla`
+
`parlantes`
+
`carcasa`
+
`soporte`
+
`interfaces posibles`

pueden convertirse en arquitectura para otro computador.

Por ejemplo:

`Pixel 6`
+
`módulo puente`
+
`display recuperado`

---

## Caja de operaciones

No convertir estas palabras en seis unidades teóricas.

Utilizarlas como **verbos de trabajo**:

- reparar;
- sustituir;
- hacer bypass;
- adaptar;
- recombinar;
- exaptar.

Pregunta:

> **¿Qué operación necesita esta parte para poder entrar en otro sistema?**

---

## Interfaces y módulos puente

Muchas veces:

`módulo A`

y

`módulo B`

ya existen.

El problema es:

`A ↔ ? ↔ B`

La pieza que falta puede ser:

- adaptador;
- convertidor;
- controlador;
- bridge;
- interface board;
- cableado;
- driver;
- protocolo.

Esto también forma parte del scavenging.

---

## Uso de IA

Aquí la AI puede ayudar a responder:

- ¿qué módulos contiene este aparato?
- ¿cuáles pueden funcionar independientemente?
- ¿qué interfaces utilizan?
- ¿qué alimentación necesitan?
- ¿qué bridge podría conectarlos?
- ¿qué otros aparatos contienen módulos compatibles?
- ¿qué dispositivo usado puede ser un sistema donante?
- ¿qué adaptadores existen?
- ¿qué información necesita verificarse en documentación?

---

## Estados de certeza

Toda investigación técnica debe distinguir:

**Hipótesis**

La IA o nosotros creemos que algo probablemente funciona así.

**Documentación**

Existe una fuente técnica que lo describe.

**Compatibilidad confirmada**

Interfaces, voltajes, protocolos y requisitos están verificados.

**Compatibilidad probable**

Hay evidencia razonable, pero faltan pruebas.

**Incógnita**

No sabemos todavía.

**Riesgo**

Existe posibilidad de daño físico, eléctrico o material.

La IA no convierte una hipótesis en documentación.

---

### [IFRAME · GRAFO DE CONCEPTOS]

**Insertar aquí iframe al grafo conceptual.**

Foco sugerido:

- exaptation
- modular exaptation
- recombination
- substitution
- bypass
- interfaces
- modules

`<!-- IFRAME: GRAFO CONCEPTOS / MODULAR EXAPTATION -->`

---

### [IFRAME · GRAFO DE TÉCNICAS]

**Insertar aquí iframe al grafo de técnicas.**

Foco:

- modular reuse
- donor systems
- substitution
- bypass
- recombination
- scavenging
- adaptation

`<!-- IFRAME: GRAFO TECNICAS / MODULAR EXAPTATION -->`

---

# BLOQUE 5 · ACTIVIDAD CENTRAL
# Este objeto murió. Construye otra cosa.
**50 min**

Una sola actividad integra el workshop completo.

---

## Etapa 1 · Elegir un objeto

Puede ser:

- roto;
- viejo;
- obsoleto;
- incompleto;
- abandonado;
- parcialmente funcional;
- un aparato propio;
- uno de los objetos demostrados;
- una fotografía entregada durante el workshop.

---

## Etapa 2 · Descomponer funciones

Crear aproximadamente 5–10 funciones.

Cuando sea relevante incluir:

- entradas;
- transformaciones;
- salidas;
- interfaces;
- dependencias.

IA:

- amplía;
- reorganiza;
- busca funciones omitidas;
- encuentra formulaciones funcionales más abstractas.

---

## Etapa 3 · Descomponer partes

Elegir varias piezas.

Aplicar Generic Parts Technique.

Describir:

- material;
- forma;
- tamaño;
- estructura;
- flexibilidad;
- superficie;
- movimiento;
- cavidades;
- articulaciones;
- conexiones;
- relaciones espaciales.

---

## Etapa 4 · Identificar módulos

Preguntar:

> ¿Qué partes funcionan como módulos suficientemente independientes como para migrar?

Investigar:

- alimentación;
- interfaces;
- controladores;
- protocolos;
- dimensiones;
- drivers;
- conectores;
- condiciones mínimas.

---

## Etapa 5 · Elegir tres

Seleccionar al menos:

**tres funciones, partes o módulos** que sigan siendo útiles.

---

## Etapa 6 · Mirar alrededor

No limitarse al objeto.

Registrar también recursos ya disponibles:

- otros aparatos viejos;
- herramientas;
- piezas;
- cables;
- materiales;
- objetos prestables;
- consumibles;
- otros módulos;
- hardware guardado.

Pregunta:

> **¿Qué ya existe alrededor mío que podría completar este sistema?**

---

## Etapa 7 · Necesidad × capacidad × gap

Usar una tabla mínima:

| Necesito | Ya tengo algo que puede hacerlo | Me falta |
|---|---|---|
| función A | módulo X | interface |
| función B | pieza Y | alimentación |
| función C | nada todavía | sistema donante |

Esto reemplaza la antigua actividad completa de "mapa de correspondencias".

Se convierte en herramienta interna del ejercicio.

---

## Etapa 8 · Investigar gaps con IA

La IA puede:

- localizar sistemas donantes;
- buscar módulos equivalentes;
- encontrar interfaces;
- identificar adaptadores;
- sugerir documentación;
- buscar datasheets;
- comparar voltajes;
- encontrar ejemplos existentes;
- señalar incompatibilidades;
- describir pruebas necesarias.

Registrar para cada hallazgo:

`hipótesis / documentación / probable / confirmado / incógnita / riesgo`

---

## Etapa 9 · Recombinar

Construir conceptualmente un objeto o sistema nuevo utilizando al menos tres elementos recuperados.

La IA puede ayudar a:

- explorar combinaciones;
- investigar precedentes;
- ordenar arquitectura;
- identificar componentes faltantes;
- encontrar sistemas puente;
- comprobar plausibilidad;
- detectar dificultades.

---

## Etapa 10 · ¿Qué falta para hacerlo real?

La propuesta termina documentando:

- objeto de origen;
- funciones recuperadas;
- partes seleccionadas;
- módulos seleccionados;
- recursos adicionales disponibles;
- sistema nuevo;
- interfaces necesarias;
- componentes faltantes;
- preguntas abiertas;
- riesgos;
- primera prueba física razonable.

---

## Restricción económica situada

No existe una cifra universal.

La pregunta es:

> **¿Qué ya tengo y qué cantidad mínima tendría sentido agregar antes de que simplemente reemplazar el producto completo resulte más lógico?**

La solución debe depender principalmente de recursos existentes.

Un pequeño gasto puede ser razonable si sirve para:

- consumibles;
- conectores;
- cables;
- adaptadores;
- fijaciones;
- interfaces simples.

No queremos convertir la actividad en:

> comprar todas las piezas necesarias para fabricar otra cosa desde cero.

---

### [IFRAME · GRAFO DE TÉCNICAS]

**Insertar aquí iframe principal del grafo de técnicas.**

Éste es el momento más importante para que el participante pueda consultar:

- functional decomposition
- Generic Parts Technique
- substitution
- bypass
- adaptation
- recombination
- modular exaptation
- scavenging
- constraint relaxation

`<!-- IFRAME: GRAFO TECNICAS / ACTIVIDAD CENTRAL -->`

---

# BLOQUE 6 · Volver al mundo
**10 min**

Abrir nuevamente los casos históricos.

Ahora los participantes ya han experimentado las operaciones materiales.

Conectar con:

- escasez;
- embargo;
- aislamiento;
- guerra;
- crisis;
- falta de infraestructura;
- pobreza;
- economías informales;
- repair cultures;
- acceso desigual a tecnología;
- discontinuación de productos;
- tecnologías cerradas.

Idea central:

> estas formas de inventiva no aparecen porque alguien decida crear una estética "maker".

Aparecen repetidamente cuando las condiciones materiales obligan a trabajar con:

> lo disponible, lo incompleto, lo reparado, lo recombinado.

También desaparecen o se vuelven menos visibles cuando:

- abundan repuestos;
- los productos son baratos;
- la sustitución es sencilla;
- la industria vuelve a cerrar los sistemas;
- resulta más fácil comprar que comprender.

---

### [IFRAME · GRAFO DE FENÓMENOS DE INVENTIVA]

**Insertar aquí nuevamente iframe del grafo de fenómenos de inventiva bajo restricción.**

Usarlo para conectar distintas geografías, épocas y condiciones.

`<!-- IFRAME: GRAFO FENOMENOS / CIERRE HISTORICO -->`

---

# BLOQUE 7 · Desobediencia tecnológica
**10 min**

Cerrar el recorrido histórico con un caso latinoamericano sistemáticamente documentado.

## Ernesto Oroza y la desobediencia tecnológica cubana

No presentarla como:

- curiosidad;
- romanticización de precariedad;
- estética retro;
- peculiaridad cultural.

Presentarla como un corpus ampliamente documentado de:

- reparación;
- apertura de productos cerrados;
- sustitución;
- adaptación;
- recombinación;
- reconfiguración;
- modificación de función;
- construcción de aparatos híbridos.

Ejemplos posibles:

- Rikimbili;
- antenas improvisadas;
- ventiladores reparados;
- electrodomésticos híbridos;
- objetos industriales transformados;
- piezas migradas entre sistemas.

La pregunta de cierre no necesita convertirse en ejercicio.

Basta con dejar visible que:

> **la configuración prescrita por el fabricante puede dejar de ser la configuración final del objeto.**

---

### [IFRAME FINAL · GRAFO DESOBEDIENCIA TECNOLÓGICA]

**Insertar aquí el iframe completo del grafo de Desobediencia Tecnológica.**

Este es el grafo final y principal del cierre.

Debe poder explorarse libremente después de la sesión.

`<!-- IFRAME: GRAFO DESOBEDIENCIA TECNOLOGICA -->`

---

# BLOQUE 8 · Recursos
**10 min**

Los recursos no se enseñan uno por uno.

Se entregan para continuar trabajando.

---

## Recurso A · Desarmar, identificar, reparar

Incluir:

- iFixit;
- service manuals;
- teardown databases;
- manufacturer documentation;
- datasheets;
- FCC documentation cuando corresponda;
- recursos del workshop de Cyberdeck;
- Scavenging Components;
- Consumer Device Rescue and Defense;
- Solarpunk Automation;
- sitios de identificación de componentes;
- fuentes de pinouts;
- recursos de hardware reutilizable.

---

## Recurso B · AI durante el proceso

Organizado por etapas:

### Entender el objeto

- identificar funciones;
- descomponer sistema;
- identificar entradas y salidas;
- identificar interfaces.

### Romper functional fixedness

- describir sin nombres funcionales;
- identificar materiales;
- describir geometrías;
- enumerar propiedades físicas.

### Identificar módulos

- reconocer componentes;
- encontrar specs;
- localizar documentación;
- identificar alimentación e interfaces.

### Encontrar sistemas donantes

- "¿Dónde más existe esta función?"
- "¿Qué aparatos contienen este módulo?"
- "¿Qué dispositivos usados podrían ser donantes?"

### Buscar interfaces

- adaptadores;
- bridge boards;
- controladores;
- converters;
- drivers.

### Evaluar compatibilidad

- voltaje;
- corriente;
- protocolos;
- conectores;
- dimensiones;
- software;
- controladores.

### Diseñar arquitectura

- mapear módulos;
- determinar gaps;
- diseñar relaciones;
- identificar componentes faltantes.

### Resolver problemas locales

No preguntar únicamente:

> "¿Qué puedo hacer con este Pixel?"

También:

> "Necesito un dispositivo que ejecute procesos programados."

> "Necesito conectividad local."

> "Necesito controlar relays."

> "Necesito registrar sensores."

> "Necesito una interfaz visual."

Después:

> ¿cuáles de esas capacidades ya existen en el Pixel?

---

## Recurso C · Hoja de actividad

**Este objeto murió. Construye otra cosa.**

Campos:

Objeto original

Funciones

Inputs / outputs / interfaces

Partes

Propiedades

Módulos

Recursos adicionales disponibles

Necesidad

Capacidad disponible

Gap

Sistema donante posible

Hipótesis

Documentación

Compatibilidad

Riesgo

Tres elementos seleccionados

Nueva configuración

Qué falta para hacerlo real

---

## Recurso D · Bibliografía

### Functional fixedness

Karl Duncker

### Generic Parts Technique

Tony McCaffrey

### Functional decomposition

Literatura de diseño de ingeniería

### Exaptation

Gould & Vrba

### Modular exaptation

Andriani & Carignani

### Desobediencia tecnológica

Ernesto Oroza

### Fenómenos históricos

Corpus Quartz desarrollado para Inventiva Bajo Restricción.

---

# Seguridad

No intervenir durante el workshop:

- equipos energizados;
- baterías hinchadas o dañadas;
- alimentación de red;
- sistemas con voltajes desconocidos;
- componentes estructurales donde un fallo pueda producir daño físico.

Una respuesta de IA no constituye por sí sola evidencia suficiente para realizar una intervención eléctrica o física.

Cuando exista riesgo, verificar mediante:

- documentación;
- datasheets;
- manuales;
- fuentes técnicas;
- mediciones apropiadas;
- personas con experiencia.

---

# Qué este workshop NO es

No es:

- curso de reparación electrónica;
- clase de ingeniería eléctrica;
- certificación técnica;
- competencia de upcycling;
- taller de manualidades recicladas;
- curso de prompting;
- curso sobre Make;
- argumento de que reutilizar siempre es mejor que comprar;
- argumento de que cualquier basura puede transformarse en cualquier cosa;
- romantización de la escasez.

La posibilidad real de concluir:

> "esto no vale la pena reutilizarlo"

también forma parte del criterio técnico.

---

# Evidencia de aprendizaje

Al finalizar, cada participante debería conservar:

1. una descomposición funcional;
2. una descripción de partes basada en propiedades;
3. un inventario básico de módulos;
4. una tabla de `necesidad × capacidad × gap`;
5. una pequeña investigación asistida por IA;
6. una propuesta que reutilice al menos tres funciones, partes o módulos;
7. una lista de interfaces, incógnitas y pruebas necesarias.

No son siete actividades.

Son capas de **una sola actividad central**.

---

# Recorrido de la sesión

| Tiempo | Bloque |
|---:|---|
| 15 min | El objeto que murió |
| 25 min | Functional reasoning + decomposition + IA |
| 7 min | Ventana histórica I |
| 20 min | Functional fixedness + Generic Parts |
| 15 min | Pausa |
| 25 min | Modular exaptation |
| 50 min | Actividad central |
| 7 min | Fenómenos históricos |
| 8 min | Desobediencia tecnológica |
| 8 min | Recursos |
| **180 min** | **Total** |

---

# Movimiento conceptual

**producto**
↓
**funciones**
↓
**inputs / outputs / interfaces**
↓
**propiedades**
↓
**partes**
↓
**módulos**
↓
**sistemas donantes**
↓
**interfaces / bridges**
↓
**recombinación**
↓
**nuevo sistema**

Y la IA acompaña:

**identificar**
↓
**descomponer**
↓
**describir**
↓
**buscar equivalencias**
↓
**encontrar módulos**
↓
**investigar interfaces**
↓
**verificar compatibilidad**
↓
**resolver gaps**
↓
**desarrollar arquitectura**

Los espacios de Quartz quedan separados así:

**Conceptos** → cuando se introduce teoría.  
**Fenómenos de inventiva** → cuando se introduce contexto histórico.  
**Técnicas** → junto a ejercicios y actividad.  
**Desobediencia tecnológica** → al final como corpus latinoamericano documentado.

---

*Contenido y diseño pedagógico © Sandra Acevedo · Multiverse School.*
