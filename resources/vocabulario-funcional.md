# Vocabulario funcional · Inventiva bajo restricción con IA

**Serie:** Discernimiento humano y creatividad soberana mediada por IA  
**Capítulo:** 2 de 3  
**Workshop:** Inventiva bajo restricción con IA  
**Uso:** referencia rápida para participantes y facilitación  
**Actualizado:** 17 de octubre de 2026

Este vocabulario acompaña el workshop **Inventiva bajo restricción**. No es un glosario de electrónica ni una lista de términos para memorizar. Su función es ofrecer palabras útiles para describir lo que estamos haciendo cuando dejamos de mirar un producto como una unidad cerrada y empezamos a verlo como un sistema de **funciones, propiedades, capacidades, partes, módulos e interfaces** que pueden participar en otras configuraciones.

La transformación central del workshop puede resumirse así:

> **producto → funciones → entradas / transformaciones / salidas → interfaces → propiedades → capacidades → partes / módulos → sistemas donantes → bridges → recombinación → nueva configuración**

Y también desde el lado del objeto:

> **objeto conocido → partes → propiedades → capacidades → otros usos posibles**

---

# 1 · Unidades básicas para mirar un sistema

## Producto

Objeto o sistema presentado comercialmente como una unidad con una identidad y un uso esperado.

Ejemplos:

- cafetera;
- teléfono;
- impresora;
- computador;
- ventilador.

En este workshop, **producto no equivale a función**. Una cafetera es una configuración particular que resuelve varias funciones; esas mismas funciones pueden aparecer en otros sistemas.

---

## Función

Aquello que **debe ocurrir** dentro de un sistema para que éste logre un resultado.

Una función se formula mejor como una acción:

- contener;
- calentar;
- transmitir;
- sostener;
- detectar;
- mover;
- regular;
- almacenar;
- mostrar.

Ejemplo:

Una cafetera no sólo “hace café”. Entre otras cosas:

- contiene agua;
- calienta;
- mueve líquido;
- controla flujo;
- recibe input;
- suministra energía;
- sostiene un recipiente.

---

## Función global

Resultado principal conseguido por el sistema completo.

Ejemplo:

**Taladro:** producir movimiento rotatorio controlado y transmitir torque a una herramienta.

La función global todavía puede descomponerse en subfunciones.

---

## Subfunción

Operación más pequeña que participa en una función mayor.

Ejemplo:

Para que un ventilador mueva aire pueden existir subfunciones como:

- recibir energía;
- regular energía;
- convertir electricidad en rotación;
- transmitir rotación;
- transferir movimiento al aire;
- sostener las partes móviles.

---

## Propiedad

Característica material, geométrica, estructural o física que una parte **tiene**, independientemente de su uso convencional.

Ejemplos:

- rígido;
- flexible;
- transparente;
- hueco;
- pesado;
- elástico;
- conductor;
- aislante;
- cóncavo;
- convexo;
- perforado;
- resistente al calor.

Una propiedad no describe todavía para qué sirve la parte.

---

## Capacidad

Algo que una parte, módulo u objeto **puede hacer o permitir** gracias a sus propiedades y estructura.

Ejemplos:

- un material transparente **puede dejar pasar luz**;
- una pieza elástica **puede almacenar energía mecánica y retornar**;
- un objeto pesado **puede actuar como contrapeso**;
- un volumen hueco **puede contener, guiar o aislar**;
- un eje **puede transmitir rotación**.

Una distinción útil:

> **propiedad = lo que algo es o tiene**  
> **capacidad = lo que eso le permite hacer**  
> **función = el papel que necesitamos que cumpla dentro de un sistema**

---

## Parte

Porción física distinguible de un objeto.

“Parte” es deliberadamente amplio. Puede ser una pieza mecánica, una sección de carcasa, una tapa, un cable, una rueda, una bandeja o una placa.

---

## Componente

Parte con una identidad técnica más específica dentro de un sistema.

Ejemplos:

- motor;
- resistor;
- sensor;
- batería;
- interruptor;
- conector.

En el workshop no es necesario conocer primero el nombre técnico. Podemos comenzar por una descripción funcional o física y traducirla después con ayuda de documentación o IA.

---

## Módulo

Conjunto de componentes que realiza una función suficientemente coherente como para ser tratado como una unidad dentro de otro sistema.

Ejemplos:

- cámara;
- display;
- fuente de alimentación;
- módulo Wi-Fi;
- lector de tarjetas;
- controlador de motor.

Un módulo puede ser más útil **entero** que desarmado.

---

## Sistema

Conjunto de partes relacionadas que intercambian energía, materia, información o movimiento para producir un comportamiento.

Un producto puede ser visto como sistema, pero un sistema no tiene que coincidir con un producto comercial.

---

## Subsistema

Parte del sistema que posee una organización interna propia y cumple una función dentro de un sistema mayor.

Ejemplo:

En un computador portátil, el sistema de enfriamiento puede incluir ventilador, heatpipe, disipador, entradas y salidas de aire.

---

## Arquitectura

Forma en que funciones, partes, módulos, interfaces y dependencias se organizan y relacionan.

Dos sistemas pueden cumplir funciones parecidas usando arquitecturas muy diferentes.

---

# 2 · Flujos, relaciones e interfaces

## Entrada / Input

Energía, materia, información, fuerza o acción que entra a un sistema o función.

Ejemplos:

- electricidad;
- agua;
- señal digital;
- presión;
- movimiento del usuario.

---

## Transformación

Cambio que ocurre sobre una entrada.

Ejemplos:

- electricidad → rotación;
- electricidad → calor;
- luz → señal digital;
- señal digital → sonido;
- movimiento mecánico → presión.

---

## Salida / Output

Resultado que sale de una función o sistema.

Ejemplos:

- movimiento;
- calor;
- imagen;
- sonido;
- información;
- aire desplazado.

---

## Flujo

Aquello que podemos seguir mientras atraviesa un sistema.

Cuatro flujos especialmente útiles en el workshop:

- **energía**;
- **materia**;
- **información**;
- **movimiento / fuerza**.

Ejemplo:

`energía eléctrica → motor → rotación → aspas → flujo de aire`

---

## Interfaz / Interface

Punto o mecanismo donde dos partes, módulos, sistemas o una persona **se encuentran e intercambian algo**.

Puede ser:

- mecánica;
- eléctrica;
- electrónica;
- lógica;
- de software;
- de usuario.

Ejemplos:

- un conector USB;
- un eje;
- un tornillo;
- un protocolo;
- una API;
- una superficie de montaje;
- botones y pantalla.

Una gran parte de la reutilización técnica fracasa o funciona en la interfaz.

---

## Dependencia

Condición, componente, servicio o recurso sin el cual una función no puede realizarse como está previsto.

Ejemplos:

- un módulo que necesita cierto voltaje;
- un display que requiere un controlador específico;
- software que depende de una cuenta o servicio externo.

---

## Compatibilidad

Grado en que dos componentes, módulos o sistemas pueden trabajar juntos bajo condiciones reales.

No debe inferirse sólo porque dos partes “parecen encajar”.

Puede depender de:

- voltaje;
- corriente;
- polaridad;
- protocolo;
- conector;
- dimensiones;
- software;
- drivers;
- montaje;
- control.

En el workshop distinguimos entre:

- **confirmado**;
- **probable**;
- **hipótesis**;
- **incógnita**.

---

## Bridge / puente

Elemento intermedio que permite conectar dos sistemas que no encajan directamente.

Puede ser:

- adaptador;
- conversor;
- controlador;
- soporte mecánico;
- cableado;
- pieza fabricada;
- cambio de voltaje;
- software;
- traducción de protocolo.

Ejemplo:

Si un teléfono no puede sacar video directamente de la forma esperada, el objeto buscado puede no ser “otra pantalla”, sino un **bridge** que externalice la interfaz visual.

---

# 3 · Operaciones de reconfiguración

Estas palabras no son sinónimos. Nombran operaciones diferentes que pueden aparecer después de identificar funciones y capacidades.

## Reparación

Restaurar una función o comportamiento perdido.

La reparación intenta recuperar algo que el sistema hacía antes.

---

## Sustitución

Reemplazar una parte o solución por otra capaz de cumplir la función necesaria.

Pregunta útil:

> **¿Qué otra cosa puede cumplir X?**

La sustitución puede ser directa o requerir adaptación.

---

## Bypass / puenteo

Evitar una parte, ruta o restricción del sistema creando otra manera de conseguir el resultado.

No necesariamente repara la parte original.

Ejemplo conceptual:

si una interfaz integrada falla, puede buscarse una forma externa de realizar esa misma función.

---

## Adaptación

Modificar una parte, interfaz o condición para que algo pueda participar en un contexto diferente.

La adaptación puede ser:

- física;
- eléctrica;
- lógica;
- dimensional;
- de montaje;
- de software.

---

## Recombinación

Construir una configuración nueva combinando funciones, partes o módulos que antes pertenecían a sistemas distintos.

La recombinación no exige que las partes mantengan su identidad original.

---

## Canibalización

Extraer partes o módulos de un sistema para utilizarlos en otro.

El objeto original funciona como fuente de recursos.

En inglés puede aparecer como **cannibalization** o dentro de prácticas de hardware scavenging.

---

## Scavenging

Búsqueda, recuperación e identificación de componentes, módulos o materiales reutilizables provenientes de equipos existentes, descartados o fuera de uso.

No equivale automáticamente a reparación, reciclaje ni canibalización, aunque puede relacionarse con ellas.

---

## Reutilización / reuse

Volver a usar una parte u objeto.

Puede conservar su función original o adquirir otra.

---

## Recontextualización

Mover una parte, módulo o tecnología a un contexto diferente, donde sus propiedades o capacidades cobran otro valor.

---

## Refuncionalización

Asignar una función nueva a una parte u objeto que antes cumplía otra.

---

## Exaptación

Uso de una característica, tecnología, parte o módulo para una función distinta de aquella para la que surgió o fue incorporada originalmente.

En este workshop hablamos especialmente de **exaptación tecnológica** o **modular exaptation** cuando una tecnología ya existente migra hacia otra arquitectura.

No es sinónimo de reutilización en general.

---

## Sistema donante / donor system

Término operativo del workshop para un objeto o sistema que puede aportar una o más capacidades necesarias a otra configuración.

Ejemplos:

- una impresora como donante de motores, ejes y mecanismos de arrastre;
- un laptop viejo como donante de pantalla, ventilador, SSD o cámara;
- un teléfono viejo como módulo completo de sensores, pantalla, batería y conectividad.

Pregunta útil:

> **¿En qué otros aparatos existe esta función o un módulo que la realice?**

---

## Objeto como inventario de capacidades

Cambio de representación central del workshop.

En lugar de:

> “tengo una impresora rota”

pasamos a:

> “tengo motores, movimiento lineal, rodillos, sensores, estructura, fuentes de energía, interfaces y materiales disponibles”.

El producto deja de ser sólo una identidad y se vuelve un conjunto de posibilidades investigables.

---

# 4 · Conceptos para cambiar la representación

## Razonamiento funcional / Functional reasoning

Forma de analizar un sistema desde **lo que hace**, en vez de comenzar por su forma o identidad comercial.

Pregunta base:

> **¿Qué tiene que ocurrir dentro de este sistema para que consiga hacer lo que hace?**

---

## Descomposición funcional / Functional decomposition

Separar una función global en funciones o transformaciones más pequeñas.

Ejemplo:

`ventilador`

puede convertirse en:

`recibir energía → controlar energía → producir rotación → transmitir rotación → mover aire`

La descomposición funcional abstrae **desde el producto hacia lo que hace**.

---

## Functional fixedness / fijación funcional

Tendencia a ver un objeto principalmente a través de su uso habitual o conocido, dificultando percibir otros usos de sus partes y propiedades.

Ejemplo:

ver una rueda únicamente como “rueda” puede ocultar que también es:

- circular;
- rígida;
- perforada;
- giratoria;
- capaz de transmitir movimiento;
- capaz de actuar como disco, guía, soporte o separador.

---

## Generic Parts Technique / GPT

Técnica asociada al trabajo de Tony McCaffrey para reducir fijación funcional describiendo partes de un objeto de forma más genérica y evitando nombres que ya contienen una función asumida.

Preguntas útiles:

> **¿Puedo dividir esta cosa todavía más?**

> **¿El nombre que estoy usando ya presupone una función?**

Ejemplo:

en vez de “bisagra”:

> pieza rígida + articulación + eje + posibilidad de movimiento angular.

En vez de “bandeja”:

> superficie plana + borde + rigidez + capacidad de contener o sostener.

### Importante

En este documento, **GPT puede significar Generic Parts Technique**. No confundir con “Generative Pre-trained Transformer”, el significado habitual de GPT en modelos como ChatGPT.

La Generic Parts Technique abstrae **desde la identidad funcional de una parte hacia sus propiedades físicas y estructurales**.

---

## Goal-derived categorization

Agrupar objetos por la **meta o función que pueden ayudar a cumplir**, en vez de por su categoría comercial.

Ejemplo:

si la meta es “mantener tensión”, podrían aparecer juntos:

- elásticos;
- resortes;
- contrapesos;
- mecanismos de retorno;
- piezas flexibles.

Aunque comercialmente pertenezcan a categorías distintas.

---

## Chunk decomposition

Romper una unidad percibida en partes o “chunks” más pequeños para hacer visibles elementos que antes se trataban como una sola cosa.

Ejemplo:

“enchufe” puede dejar de ser una sola unidad y convertirse en:

- pines metálicos;
- carcasa;
- aislante;
- conductores;
- tornillos;
- geometrías de montaje.

---

## Constraint relaxation

Detectar y soltar una restricción que asumimos como necesaria aunque el problema no la imponga realmente.

Ejemplo:

> “necesito una webcam”

puede contener una restricción inventada: que la solución deba ser un producto vendido como webcam.

Al relajarla:

> necesito capturar imagen + convertirla en señal + entregarla al computador + sostener/orientar el sensor.

---

## Analogical transfer

Trasladar una relación, mecanismo o solución desde un dominio hacia otro.

Pregunta útil:

> **¿Dónde más existe una estructura o función parecida, aunque el objeto pertenezca a otra categoría?**

---

## Modular exaptation

Migración de un módulo ya existente hacia una arquitectura nueva donde cumple una función distinta o participa de otra manera.

Ejemplo:

usar un teléfono antiguo entero como:

`computador + pantalla + touch + batería + cámaras + sensores + radio`

en lugar de desmontarlo para rescatar piezas individuales.

---

# 5 · Restricción, inventiva y casos reales

## Restricción

Condición que limita algunas rutas y modifica el espacio de diseño.

Puede ser:

- disponibilidad;
- costo;
- tiempo;
- acceso;
- compatibilidad;
- herramientas;
- conocimiento;
- infraestructura;
- dependencia tecnológica.

En este workshop, restricción **no significa pobreza como espectáculo**. Es una condición situada que obliga a mirar de otro modo los recursos disponibles.

---

## Inventiva bajo restricción

Práctica de producir una solución nueva o suficiente cuando la reposición directa, la herramienta habitual o el camino convencional no están disponibles o no resultan adecuados.

La secuencia de trabajo puede verse así:

> **necesidad → funciones → recursos → capacidades → gaps → operaciones → investigación → configuración**

---

## Bricolage

Construcción o resolución mediante materiales, herramientas y recursos disponibles, muchas veces combinados fuera de sus usos previstos.

No es sinónimo automático de GPT, exaptación, reparación o desobediencia tecnológica.

---

## Desobediencia tecnológica

Concepto desarrollado por Ernesto Oroza a partir de su investigación sobre prácticas materiales y tecnológicas en Cuba, especialmente objetos abiertos, reparados, modificados y reconfigurados bajo condiciones de fuerte restricción.

En este workshop lo usamos como **caso histórico y material para pensar la relación con los objetos**, no como sinónimo de Generic Parts Technique.

La conexión que proponemos es operacional:

- GPT ayuda a suspender la identidad funcional de una parte;
- los objetos documentados por Oroza muestran partes y sistemas reutilizados atendiendo a propiedades, formas, materiales y capacidades que exceden su función prescrita.

No se afirma una genealogía entre ambos marcos.

---

# 6 · Investigación y verificación

## Hipótesis técnica

Explicación o posibilidad todavía no confirmada por evidencia suficiente.

Ejemplo:

> “este conector podría ser LVDS”.

La siguiente pregunta debe ser:

> **¿qué evidencia permitiría confirmarlo?**

---

## Documentación

Información técnica trazable que ayuda a verificar identidad, interfaces o comportamiento.

Ejemplos:

- datasheet;
- service manual;
- pinout;
- esquema;
- documentación del fabricante;
- teardown;
- fotografías internas confiables.

---

## Equivalencia funcional

Dos partes o sistemas pueden realizar una función semejante aunque tengan forma, origen o categoría diferentes.

Equivalencia funcional **no implica compatibilidad directa**.

---

## Gap

Lo que todavía falta entre las capacidades disponibles y las funciones necesarias.

Puede ser:

- una función inexistente;
- una interface;
- energía;
- control;
- montaje;
- software;
- información;
- compatibilidad.

Los gaps ayudan a decidir qué investigar o adquirir mínimamente.

---

## Incógnita

Dato relevante que todavía no conocemos.

Ejemplos:

- voltaje;
- pinout;
- protocolo;
- dimensiones;
- consumo;
- driver requerido.

Nombrar una incógnita es mejor que convertirla en una suposición invisible.

---

## Evidencia

Información observable o documentada que permite aumentar o reducir confianza en una hipótesis.

En el workshop, una respuesta de IA puede ayudar a localizar evidencia, pero **no sustituye la evidencia**.

---

# 7 · Clean Room como puente conceptual

## Clean-room reimplementation

Método de reimplementación en el que se separa el análisis del sistema original de la construcción de una nueva implementación.

En la representación usada para el workshop:

`sistema original`
↓
`observar / probar / describir`
↓
`especificación funcional`
↓
`barrera de información`
↓
`reimplementar desde la especificación`
↓
`nuevo sistema`

La idea que nos interesa aquí es:

> **separar comportamiento de implementación.**

No se presenta como garantía jurídica automática.

---

# 8 · Frases de trabajo

Estas frases condensan el vocabulario del workshop y pueden usarse como prompts mentales durante las actividades:

> **Producto no es función.**

> **El objeto tampoco es su nombre.**

> **¿Qué tiene que ocurrir para que esto funcione?**

> **¿Qué entra, qué cambia y qué sale?**

> **¿Puedo dividir esta parte todavía más?**

> **¿El nombre que estoy usando ya presupone una función?**

> **¿Qué propiedades tiene?**

> **¿Qué capacidades aparecen gracias a esas propiedades?**

> **¿Dónde más existe esta función?**

> **¿Qué sistema podría ser donante?**

> **¿Qué bridge falta entre estas dos cosas?**

> **¿Qué sabemos, qué estamos infiriendo y qué todavía no sabemos?**

> **Imaginar una configuración no demuestra compatibilidad.**

> **No imitamos necesariamente el objeto: reconstruimos la función.**

---

# 9 · Mapa mínimo

Para recordar las distinciones principales:

| Término | Pregunta |
|---|---|
| **producto** | ¿cómo se llama la configuración conocida? |
| **función** | ¿qué tiene que ocurrir? |
| **propiedad** | ¿qué es / qué característica tiene? |
| **capacidad** | ¿qué le permite hacer esa propiedad o estructura? |
| **parte** | ¿qué porción física puedo distinguir? |
| **módulo** | ¿qué conjunto puede migrar como unidad? |
| **input** | ¿qué entra? |
| **transformación** | ¿qué cambia? |
| **output** | ¿qué sale? |
| **interface** | ¿dónde se encuentran dos sistemas? |
| **donor system** | ¿qué otro sistema ya contiene la capacidad? |
| **bridge** | ¿qué falta para conectarlos? |
| **compatibilidad** | ¿pueden realmente funcionar juntos? |
| **gap** | ¿qué sigue faltando? |
| **evidencia** | ¿qué permite afirmarlo? |

---

## Nota de uso

Este vocabulario está diseñado para acompañar la práctica. No todos los términos necesitan aparecer en la facilitación oral. Una persona puede comenzar perfectamente diciendo:

> “necesito algo que gire”

y sólo después descubrir que está buscando:

> rotación → transmisión de torque → motor / eje / mecanismo donante → interfaz → compatibilidad.

El vocabulario sirve para **hacer visible una arquitectura que antes estaba escondida dentro del nombre del producto**.
