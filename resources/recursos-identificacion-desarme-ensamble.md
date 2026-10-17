# Recursos para identificar, desarmar y volver a ensamblar
## Guía de investigación para hardware, componentes y sistemas donantes

**Workshop:** Inventiva Bajo Restricción con IA  
**Serie:** Discernimiento humano y creatividad soberana mediada por IA  
**Capítulo:** 2 de 3  
**Uso:** Apéndice práctico para identificación, desarme, documentación y ensamble  
**Actualizado:** octubre de 2026

*Este documento acompaña el workshop **Inventiva Bajo Restricción con IA**. No es un directorio exhaustivo de reparación electrónica. Está organizado como una ruta de investigación: partir de aquello que tienes delante, identificarlo con suficiente precisión, encontrar documentación útil y decidir si una pieza, módulo o aparato completo puede participar en otra arquitectura.*

**La pregunta no es solamente “¿qué es esta pieza?”, sino también “¿qué necesito saber de ella para poder reutilizarla con seguridad?”.**

---

## Cómo usar esta guía

Cuando desarmamos un aparato aparecen muchas clases de incertidumbre al mismo tiempo.

Podemos no saber:

- cómo abrirlo sin romperlo;
- qué componente estamos mirando;
- qué modelo exacto tenemos;
- qué interfaz utiliza;
- qué voltaje necesita;
- qué hace cada pin;
- si existe documentación;
- si puede funcionar fuera de su sistema original;
- qué adaptador o controlador necesita;
- o si conviene más reutilizar el dispositivo completo que extraer una de sus partes.

No todos esos problemas se resuelven en el mismo sitio.

Esta guía organiza recursos según la pregunta que tienes en ese momento.

| Si tienes delante… | Empieza por… | Lo que estás buscando |
|---|---|---|
| **Un aparato cerrado** | iFixit / Repair Wiki | Cómo abrirlo, desmontarlo y reconocer su arquitectura. |
| **Un aparato sin manual técnico** | FCC ID / fabricante | Fotos internas, manuales, diagramas, etiquetas y documentación. |
| **Una pantalla** | Panelook | Modelo, resolución, interfaz, conector, número de pines y dimensiones. |
| **Un componente con número de parte** | Octopart + fabricante | Datasheet, especificaciones y alternativas. |
| **Un SMD con código corto** | WhatSMD | Candidatos posibles que después deben verificarse. |
| **Un conector desconocido** | PinoutGuide | Distribución y función de pines, cableado e interfaz. |
| **Un módulo que quieres conectar a otro** | Datasheet + Adafruit / SparkFun | Alimentación, señal, protocolo, conexión y ejemplos de integración. |
| **Una idea de reutilización poco común** | Hackaday | Casos previos, reverse engineering y caminos técnicos posibles. |
| **Un teléfono o tablet viejo completo** | postmarketOS | Si conviene reutilizar el sistema completo como computador. |
| **Electrónica antigua sin documentación fácil de encontrar** | ElektroTanya | Service manuals y schematics como recurso de segunda línea. |

> **Regla de trabajo:** una coincidencia encontrada en una base de datos o una respuesta de IA es un punto de partida para investigar. No equivale automáticamente a compatibilidad confirmada.

---

# 1 · Abrir y desmontar

## iFixit

**Sitio:** [iFixit en español](https://es.ifixit.com/) · [iFixit](https://www.ifixit.com/)

iFixit es el primer lugar donde conviene mirar cuando necesitas saber **cómo entrar físicamente a un objeto**.

Puede ayudarte a encontrar:

- secuencias de desmontaje;
- ubicación de tornillos y clips;
- tipos de adhesivo;
- piezas reemplazables;
- herramientas apropiadas;
- fotografías de distintas etapas del desarme;
- teardowns de dispositivos completos.

### Úsalo cuando

- todavía no sabes cómo abrir el aparato;
- quieres evitar romper una carcasa, flex cable o conector;
- necesitas reconocer qué piezas aparecen a medida que desmontas;
- quieres comparar tu dispositivo con uno ya documentado.

### Qué registrar

Antes de seguir desarmando, guarda:

- fabricante;
- modelo exacto;
- número de revisión si existe;
- fotografías antes y durante el proceso;
- etiquetas de las piezas que te interesen.

**Nivel de confianza habitual:** alto para el procedimiento específico documentado, pero confirma siempre que la guía corresponda exactamente a tu variante o revisión.

---

## Repair Wiki

**Sitio:** [Repair Wiki](https://repair.wiki/)

Repair Wiki resulta especialmente útil cuando ya pasaste del simple desmontaje hacia **diagnóstico, arquitectura interna o reparación a nivel de placa**.

Sus páginas de dispositivos pueden incluir:

- fotografías de PCB;
- puntos de prueba;
- secuencias de encendido;
- valores de voltaje;
- resistencia o diode-mode readings;
- fallas frecuentes;
- explicaciones de circuitos;
- procedimientos de diagnóstico.

### Úsalo cuando

- iFixit te muestra cómo abrir el aparato, pero no cómo funciona internamente;
- necesitas comparar una placa dañada con valores de referencia;
- quieres entender una sección específica de una PCB;
- estás investigando si un módulo puede operar independientemente.

**Nivel de confianza habitual:** documentación comunitaria técnica. Úsala como evidencia útil, pero contrástala con service manuals, datasheets y mediciones cuando la decisión sea crítica.

---

# 2 · Encontrar documentación que el fabricante no puso frente a ti

## FCC ID

**Buscador amigable:** [FCCID.io](https://fccid.io/)

Muchos dispositivos que contienen transmisores de radio, Wi-Fi, Bluetooth u otras tecnologías reguladas tienen un **FCC ID** impreso en una etiqueta o carcasa.

Los expedientes de autorización pueden contener:

- fotografías internas;
- fotografías externas;
- manuales;
- reportes de prueba;
- diagramas de bloques;
- descripciones operacionales;
- etiquetas;
- información sobre radios y frecuencias.

### Úsalo cuando

- tienes un router, teléfono, teclado inalámbrico, IoT device, radio u otro producto con FCC ID;
- el fabricante no publica fotografías internas;
- quieres reconocer placas, antenas o módulos antes de abrir el aparato;
- necesitas saber qué radio o subsistema contiene.

### Procedimiento rápido

1. Busca la etiqueta con **FCC ID**.
2. Ingresa el código completo.
3. Revisa especialmente **Internal Photos**, **User Manual**, **Operational Description** y **Block Diagram**.
4. Usa esos documentos para formular una hipótesis sobre lo que encontrarás físicamente.

> FCCID.io funciona como índice y acceso conveniente a expedientes de autorización. Para una decisión técnica importante, conserva también la referencia al documento original del expediente cuando esté disponible.

---

# 3 · Identificar pantallas recuperadas

## Panelook

**Sitio:** [Panelook](https://www.panelook.com/)

Una pantalla de laptop o monitor no debería investigarse solamente como:

> “pantalla de un Dell viejo”

Lo importante es encontrar el **model number del panel mismo**, normalmente impreso en una etiqueta en la parte posterior.

Panelook permite consultar datos como:

- fabricante;
- tamaño;
- resolución;
- tecnología del panel;
- backlight;
- interfaz;
- cantidad de pines del conector;
- dimensiones;
- frecuencia;
- estado de producción.

### Flujo recomendado

1. Desmonta el display siguiendo una guía apropiada.
2. Fotografía la etiqueta trasera.
3. Copia exactamente el model number.
4. Búscalo en Panelook.
5. Identifica especialmente:
   - **Interface**
   - **CNT Pins**
   - resolución
   - backlight
   - dimensiones
6. Con el modelo exacto, investiga una **controller board / driver board** compatible.

### Por qué importa

Dos laptops visualmente parecidos pueden contener paneles completamente distintos.

Buscar por el modelo del computador puede darte una familia de posibilidades.  
Buscar por el **modelo del panel** te acerca a la pieza que realmente tienes.

**Nivel de confianza habitual:** bueno para identificar especificaciones del panel; confirma controller boards y pinouts mediante documentación específica antes de energizar.

---

# 4 · Identificar componentes electrónicos

## Octopart

**Sitio:** [Octopart](https://octopart.com/)

Octopart funciona especialmente bien cuando tienes un componente con un **part number legible**.

Puedes buscar por:

- número de parte;
- fabricante;
- palabra clave;
- especificación técnica.

Y encontrar:

- datasheets;
- fabricante;
- descripción;
- categoría;
- disponibilidad;
- piezas equivalentes o relacionadas;
- distribuidores.

### Úsalo cuando

ves algo como:

`STM32F103C8T6`  
`TPS5430`  
`LM2596S`

y necesitas pasar de:

> “hay un chip aquí”

a:

> “sé qué componente es, qué alimentación utiliza, qué pines tiene y qué función puede cumplir”.

### Orden de confianza

Cuando encuentres una coincidencia:

**Octopart → datasheet del fabricante → documentación del módulo o aparato → medición física**

Octopart te ayuda a llegar a la documentación primaria. No reemplaza el datasheet.

---

## WhatSMD

**Sitio:** [WhatSMD](https://whatsmd.com/en/marking)

Los componentes SMD pequeños muchas veces no imprimen un part number completo.

Pueden mostrar códigos como:

`6H`  
`1AM`  
`K1R`

WhatSMD permite buscar esos **marking codes** y obtener componentes candidatos.

### Importante

Un marking code **no identifica necesariamente una sola pieza**.

El mismo código puede aparecer en:

- distintos fabricantes;
- diferentes packages;
- transistores;
- diodos;
- MOSFETs;
- otros componentes.

Por eso este recurso sirve para producir:

> **una hipótesis de identificación**

no:

> **una identificación confirmada**.

### Para reducir candidatos

Combina:

- código visible;
- package;
- número de pines;
- contexto del circuito;
- fabricante probable;
- mediciones;
- datasheet.

Esta distinción encaja directamente con los estados de certeza del workshop:

**hipótesis → documentación → compatibilidad probable → compatibilidad confirmada**

---

# 5 · Identificar conectores e interfaces

## PinoutGuide / Pinouts.ru

**Sitio:** [PinoutGuide](https://www.pinoutguide.com/)

Contiene pinouts y esquemas de conectores modernos y antiguos, incluyendo:

- buses de computadores;
- interfaces de almacenamiento;
- alimentación;
- audio y video;
- conectores de dispositivos;
- cables;
- interfaces seriales;
- conectores propietarios documentados por la comunidad.

### Úsalo cuando

tienes:

- un conector;
- un cable;
- una cantidad de pines;
- una interfaz antigua;
- o dos módulos que físicamente parecen conectables, pero no sabes qué señal transporta cada contacto.

### Antes de conectar

Confirma:

- orientación del conector;
- numeración de pines;
- ground;
- voltajes;
- señal;
- dirección;
- estándar;
- revisión.

> Un conector que físicamente calza no implica que eléctricamente sea compatible.

**Nivel de confianza habitual:** recurso comunitario muy útil. Para alimentación y conexiones críticas, contrasta con datasheet, service manual o documentación del fabricante.

---

# 6 · Aprender a conectar módulos

## Adafruit Learning System

**Sitio:** [Adafruit Learning System](https://learn.adafruit.com/)

## SparkFun Learn / Documentation

**Sitios:** [SparkFun Learn](https://learn.sparkfun.com/) · [SparkFun Documentation](https://www.sparkfun.com/documentation)

Estos recursos son especialmente útiles después de identificar una pieza, cuando aparece la siguiente pregunta:

> **¿Cómo hago que esto funcione dentro de mi nuevo sistema?**

Pueden ayudar con:

- principios básicos de electrónica;
- alimentación;
- buses e interfaces;
- sensores;
- displays;
- microcontroladores;
- serial communication;
- I²C;
- SPI;
- soldering;
- multímetros;
- hookup guides;
- esquemas y ejemplos.

### Úsalos como puente

`componente identificado`
↓
`entiendo alimentación e interfaz`
↓
`puedo probarlo aisladamente`
↓
`puedo integrarlo en otra arquitectura`

No es necesario utilizar componentes de Adafruit o SparkFun para que sus guías sean útiles. Muchas explicaciones sirven para comprender estándares y técnicas generales.

---

# 7 · Encontrar precedentes de reutilización y reverse engineering

## Hackaday

**Sitio:** [Hackaday](https://hackaday.com/)

Hackaday es particularmente útil para responder:

> **¿Alguien ya intentó algo parecido?**

Puede mostrar:

- reutilización de displays;
- reverse engineering;
- hardware hacking;
- controller boards;
- adaptadores;
- reaprovechamiento de aparatos;
- proyectos construidos desde piezas recuperadas.

Un ejemplo especialmente pertinente para este workshop es:

[Displays We Love Hacking: LVDS And EDP](https://hackaday.com/2024/05/08/displays-we-love-hacking-lvds-and-edp/)

### Cómo usarlo bien

Hackaday sirve como:

- descubridor de caminos;
- catálogo de precedentes;
- fuente de vocabulario técnico;
- puerta hacia proyectos y repositorios.

No debería ser tu única confirmación de:

- voltaje;
- pinout;
- compatibilidad;
- seguridad;
- especificaciones.

Usa el proyecto para descubrir **qué investigar después**.

---

# 8 · Antes de destriparlo: ¿conviene reutilizar el aparato completo?

## postmarketOS

**Sitios:** [postmarketOS](https://postmarketos.org/) · [Device Wiki](https://wiki.postmarketos.org/wiki/Category:Devices)

A veces la mejor exaptación modular consiste en **no extraer el módulo**.

Un teléfono viejo ya reúne:

- procesador;
- RAM;
- almacenamiento;
- pantalla;
- touchscreen;
- Wi-Fi;
- Bluetooth;
- cámaras;
- batería;
- sensores;
- carcasa;
- sistema de alimentación.

En vez de intentar recuperar cada pieza por separado, puede resultar más eficiente convertir el aparato completo en:

- pequeño servidor;
- interfaz;
- controlador;
- terminal;
- nodo de red;
- computador embebido.

### Antes de desarmar un teléfono

Pregunta:

> **¿Puedo reutilizar el sistema entero y acceder a sus capacidades mediante software?**

La Device Wiki de postmarketOS permite investigar niveles de soporte por modelo.

Esta es una forma especialmente clara de **exaptación modular a escala de sistema**.

---

# 9 · Cuando necesitas un service manual antiguo

## ElektroTanya

**Sitio:** [ElektroTanya](https://elektrotanya.com/)

Puede ser útil como recurso de segunda línea para:

- service manuals;
- schematics;
- documentación de aparatos antiguos;
- electrónica de consumo que ya no cuenta con soporte fácil de encontrar.

### Úsalo después de

1. buscar documentación oficial;
2. revisar iFixit / Repair Wiki;
3. buscar por modelo exacto;
4. comprobar FCC ID cuando corresponda.

No todos los documentos comunitarios tienen el mismo origen o nivel de verificación, así que conserva la procedencia cuando una decisión dependa de ellos.

---

# 10 · Recursos de The Multiverse School que ya trabajan esta lógica

Este workshop no parte desde cero. Hay material dentro de The Multiverse School que ya documenta operaciones concretas de scavenging, reutilización y construcción desde recursos disponibles.

## Scavenging Components

[Curriculum/Computer Fluency/Scavenging Components.md](https://github.com/lizTheDeveloper/multiverse_school_curriculum/blob/main/Curriculum/Computer%20Fluency/Scavenging%20Components.md)

Especialmente útil para:

- decidir qué componentes vale la pena rescatar;
- comparar dificultad real;
- reutilizar displays;
- teclados;
- teléfonos completos;
- fuentes, ventiladores, speakers y otros módulos.

Su flujo para recuperar pantallas es particularmente compatible con este workshop:

**desmontar → leer model number → Panelook → identificar interfaz → buscar controller board**

---

## Build a Cyberdeck

[Curriculum/Computer Fluency/Build a Cyberdeck - Syllabus.md](https://github.com/lizTheDeveloper/multiverse_school_curriculum/blob/main/Curriculum/Computer%20Fluency/Build%20a%20Cyberdeck%20-%20Syllabus.md)

Útil para observar cómo distintas piezas pueden volver a convertirse en un computador funcional.

Incluye caminos que van desde comprar componentes hasta reutilizar hardware existente, incluido el uso de teléfonos viejos como sistemas completos.

---

## Solarpunk Automation

[Curriculum/Solarpunk Automation](https://github.com/lizTheDeveloper/multiverse_school_curriculum/tree/main/Curriculum/Solarpunk%20Automation)

Particularmente pertinente para:

- old phones como infraestructura;
- sistemas pequeños;
- alimentación;
- hardware recuperado;
- diseño desde recursos disponibles;
- resiliencia técnica.

### Battery Salvage Guide — Safety First

[Battery Salvage Guide - Safety First](https://github.com/lizTheDeveloper/multiverse_school_curriculum/blob/main/Curriculum/Solarpunk%20Automation/Guides/Battery%20Salvage%20Guide%20-%20Safety%20First.md)

**Este recurso se incluye por seguridad, no como invitación general a abrir baterías durante el workshop.**

---

## Consumer Device Rescue and Defense

[Consumer Device Rescue and Defense](https://github.com/lizTheDeveloper/multiverse_school_curriculum/blob/main/Curriculum/Home%20Cyber%20Defense/Clinics/3%20-%20Consumer%20Device%20Rescue%20and%20Defense.md)

Puede aportar criterios útiles para evaluar el estado de dispositivos antiguos antes de decidir si:

- seguir utilizándolos;
- migrarlos;
- reparar;
- retirar;
- reutilizar parcialmente.

---

# 11 · Una ruta de investigación recomendada

Cuando encuentres una pieza o módulo desconocido, intenta avanzar en este orden.

## Paso 1 · Documentar antes de separar

Fotografía:

- aparato completo;
- ubicación de la pieza;
- conectores;
- etiquetas;
- orientación;
- cableado.

## Paso 2 · Identificar

Busca primero:

- fabricante;
- modelo;
- part number;
- marking code;
- FCC ID;
- etiqueta de panel.

## Paso 3 · Encontrar documentación

Prioriza:

1. fabricante;
2. datasheet;
3. service manual;
4. FCC filing;
5. iFixit / Repair Wiki;
6. bases técnicas especializadas;
7. proyectos comunitarios.

## Paso 4 · Entender interfaces

Registra:

- alimentación;
- ground;
- voltaje;
- corriente;
- protocolo;
- pinout;
- driver/controlador;
- requisitos mecánicos.

## Paso 5 · Buscar el puente

Si tienes:

`módulo A`
+
`módulo B`

pero no pueden comunicarse directamente, investiga:

`A ↔ adaptador / controller / bridge / converter ↔ B`

El componente clave del proyecto puede ser precisamente esa interfaz.

## Paso 6 · Separar lo que sabes de lo que supones

Etiqueta cada hallazgo:

- **Hipótesis**
- **Documentación**
- **Compatibilidad probable**
- **Compatibilidad confirmada**
- **Incógnita**
- **Riesgo**

## Paso 7 · Probar pequeño

Antes de integrar todo el sistema:

- prueba el módulo aisladamente;
- confirma alimentación;
- verifica señales;
- prueba una sola conexión;
- documenta qué ocurrió.

---

# 12 · IA como compañera de investigación

Una IA con visión puede ayudar a:

- leer etiquetas;
- transcribir model numbers;
- describir una placa;
- reconocer familias de conectores;
- generar términos de búsqueda;
- explicar un datasheet;
- comparar dos interfaces;
- formular preguntas para encontrar documentación.

Pero una fotografía borrosa y una respuesta convincente pueden producir una identificación falsa con enorme facilidad.

Por eso conviene pedir a la IA cosas como:

> **“No identifiques esta pieza con certeza si la evidencia visual no alcanza. Dame candidatos, qué detalles los distinguen y qué fotografía o medición necesito para confirmar.”**

O:

> **“Separa en tu respuesta lo documentado, lo inferido y lo que todavía no sabemos.”**

La IA puede acelerar el camino hacia evidencia técnica.

**No reemplaza la evidencia técnica.**

---

# Seguridad

No energices un componente recuperado hasta haber identificado, como mínimo:

- alimentación;
- polaridad;
- ground;
- voltaje esperado.

Evita intervenir sin conocimiento especializado:

- baterías hinchadas o dañadas;
- fuentes conectadas a red;
- CRT;
- capacitores de alta tensión;
- microondas;
- fuentes desconocidas;
- sistemas donde una falla pueda producir lesión, incendio o daño estructural.

Cuando aparezca una batería de litio, **detente antes de asumir que “rescatar” significa abrir el pack**.

La recuperación de hardware también incluye saber cuándo no vale la pena intervenirlo.

---

# Selección mínima: cinco pestañas para empezar

Si no quieres abrir once recursos a la vez, comienza por éstos:

1. **iFixit** — abrir y desmontar.
2. **Panelook** — identificar displays.
3. **Octopart + datasheet del fabricante** — identificar componentes.
4. **PinoutGuide** — entender conectores.
5. **Hackaday** — descubrir precedentes y caminos de reutilización.

Y conserva dos rutas especiales:

- **FCC ID** cuando el dispositivo tenga radio y falte documentación.
- **postmarketOS** antes de destripar un teléfono que todavía puede ser un computador completo.

---

## Idea central

Un recurso técnico sirve cuando transforma:

> **“tengo una pieza rara”**

en una cadena de preguntas más precisa:

> **¿qué es?**  
> **¿qué hace?**  
> **¿qué necesita para funcionar?**  
> **¿cómo se comunica?**  
> **¿qué evidencia tengo?**  
> **¿con qué otra cosa podría conectarla?**

Ese cambio permite pasar del objeto encontrado a un módulo utilizable dentro de otra arquitectura.

---

*Contenido y adaptación © Sandra Acevedo · Multiverse School.*
