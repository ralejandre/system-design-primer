*[English](README.md) ∙ [日本語](README-ja.md) ∙ [简体中文](README-zh-Hans.md) ∙ [繁體中文](README-zh-TW.md) | [العَرَبِيَّة‎](https://github.com/donnemartin/system-design-primer/issues/170) ∙ [বাংলা](https://github.com/donnemartin/system-design-primer/issues/220) ∙ [Português do Brasil](https://github.com/donnemartin/system-design-primer/issues/40) ∙ [Deutsch](https://github.com/donnemartin/system-design-primer/issues/186) ∙ [ελληνικά](https://github.com/donnemartin/system-design-primer/issues/130) ∙ [עברית](https://github.com/donnemartin/system-design-primer/issues/272) ∙ [Italiano](https://github.com/donnemartin/system-design-primer/issues/104) ∙ [한국어](https://github.com/donnemartin/system-design-primer/issues/102) ∙ [فارسی](https://github.com/donnemartin/system-design-primer/issues/110) ∙ [Polski](https://github.com/donnemartin/system-design-primer/issues/68) ∙ [русский язык](https://github.com/donnemartin/system-design-primer/issues/87) ∙ [Español](https://github.com/donnemartin/system-design-primer/issues/136) ∙ [ภาษาไทย](https://github.com/donnemartin/system-design-primer/issues/187) ∙ [Türkçe](https://github.com/donnemartin/system-design-primer/issues/39) ∙ [tiếng Việt](https://github.com/donnemartin/system-design-primer/issues/127) ∙ [Français](https://github.com/donnemartin/system-design-primer/issues/250) | [Add Translation](https://github.com/donnemartin/system-design-primer/issues/28)*

**Ayuda [traduciendo](TRANSLATIONS.md) ésta guía!**

# El manual de diseño de sistemas

<p align="center">
  <img src="images/jj3A5N8.png">
  <br/>
</p>

## Motivación

> Aprende a diseñar sistemas a gran-escala.
>
> Preparacion para una entrevista de diseño de sistemas.

### Aprende a diseñar sistemas a gran-escala

Aprender a diseñar sistemas escalables te ayudara a ser un mejor engeniero.

Diseño de sistemas es un tema amplio. Existe **una gran contidad de recursos esparcidos en el internet** sobre los principios de diseño de sistemas.

Este repositorio es una **collection organizada** de recursos que te ayudaran a aprender como construir sistemas a escala.

### Aprende de la comunidad de codigo abierto.

Este es un projecto de codigo abierto, continuamente actualizado.

[Contribuciones](#contributing) siempre son bienvenidas!

### Preparate para la entrevista de diseño de sistemas

Ademas de las entrevistas de codigo, diseño de sistemas es un **componente requerido** en el **proceso de entrevista técnica** en muchas compañias tecnologicas.

**Practica preguntas de diseño de sistemas comunes en entrevistas** y **compara** tus resultados con las **soluciones muestra**: discussion, codigo y diagramas.

Temas adicionales para la preparacion de una entrevista:

* [Guid de estudio](#study-guide)
* [Cómo abordar una pregunta de entrevista de diseño de sistema](#how-to-approach-a-system-design-interview-question)
* [Preguntas de la entrevista de diseño del sistema, **con soluciones**](#system-design-interview-questions-with-solutions)
* [Preguntas de la entrevista de diseño de sistemas con programacion orientado a objetos, **con soluciones**](#object-oriented-design-interview-questions-with-solutions)
* [Preguntas adicionales de la entrevista sobre el diseño del sistema](#additional-system-design-interview-questions)

## Tarjetas Didácticas Anki

<p align="center">
  <img src="images/zdCAkB3.png">
  <br/>
</p>

Las [Barajas de Tarjetas Didácticas Anki](https://apps.ankiweb.net/)
usan la repeticion espaciada para ayudarte a retener conceptos clave de diseño de sistemas.

* [Baraja de diseño de sistemas](https://github.com/donnemartin/system-design-primer/tree/master/resources/flash_cards/System%20Design.apkg)
* [Baraja de ejercicios de diseño de sistemas](https://github.com/donnemartin/system-design-primer/tree/master/resources/flash_cards/System%20Design%20Exercises.apkg)
* [Baraja de ejercicios de diseño de sistemas con Programacion orientada a objectos](https://github.com/donnemartin/system-design-primer/tree/master/resources/flash_cards/OO%20Design.apkg)

Ideal para usar mientras viajas.

### Recursos de programacion: Desafios de programacion interactivos


Buscas recursos que te ayuden a prepararte para la [**Entrevista tecnica**](https://github.com/donnemartin/interactive-coding-challenges)?

<p align="center">
  <img src="images/b4YtAEN.png">
  <br/>
</p>

Echa un vistazo al repositorio hermano [**Desafíos de programacion interactiva**] (https://github.com/donnemartin/interactive-coding-challenges), que contiene una baraja adicional de Anki:

* [Baraja de programacion](https://github.com/donnemartin/interactive-coding-challenges/tree/master/anki_cards/Coding.apkg)

## Contribuyendo

> Aprende de la comunidad.

No dude en enviar un pull request para ayudar:

* Corregir errores
* Mejorar secciones
* Agregar nuevas secciones
* [Traducir](https://github.com/donnemartin/system-design-primer/issues/28)

Contenido que necesita de mejoria esta ubicado [bajo desarrollo](#under-development).

Revisa la guia de contribucion [Pautas de contribución](CONTRIBUTING.md).

## Temario de diseño de sistemas

> Resumen de varios temas de diseño de sistemas, incluyendo los pros y contras.
**Todo es un compromiso**
>
> Cada sección contiene enlaces a recursos más detallados.

<p align="center">
  <img src="images/jrUBAF7.png">
  <br/>
</p>

* [Temario de diseño de sistemas: empiezan aqui](#system-design-topics-start-here)
* [Paso 1: Revisa la escalabilidad video conferencia](#step-1-review-the-scalability-video-lecture)
    * [Step 2: Revisa la escalabilidad articulo](#step-2-review-the-scalability-article)
    * [Siguientes pasos](#next-steps)
* [Desempeño vs escalabilidad](#performance-vs-scalability)
* [Latencia vs rendimiento](#latency-vs-throughput)
* [Disponibilidad vs consistencia](#availability-vs-consistency)
    * [Teorema CAP](#cap-theorem)
        * [CP - consistencya y tolerancia al particionado](#cp---consistency-and-partition-tolerance)
        * [AP - Disponibilidad y tolerancia al particionado](#ap---availability-and-partition-tolerance)
* [Patrones de consistencia](#consistency-patterns)
    * [Consistencia debild](#weak-consistency)
    * [Consistencia eventual](#eventual-consistency)
    * [Consistencia fuerte](#strong-consistency)
* [Patrones de disponibilidad](#availability-patterns)
    * [Conmutacion por error](#fail-over)
    * [Replicación](#replication)
    * [Disponibilidad en numeros](#availability-in-numbers)
* [Sistema de nombres de dominio](#domain-name-system)
* [Red de entrega de contenidos](#content-delivery-network)
    * [CDNs de empuje](#push-cdns)
    * [CDNs de jale](#pull-cdns)
* [Equilibrador de carga](#load-balancer)
    * [Activo-pasivo](#active-passive)
    * [Activo-activo](#active-active)
    * [Nivel 4 equilibrador de carga](#layer-4-load-balancing)
    * [Nivel 7 equilibrador de carga](#layer-7-load-balancing)
    * [Escalado horizontal](#horizontal-scaling)
* [Proxy inverso (servidor web)](#reverse-proxy-web-server)
    * [Equilibrador de carga vs Proxy inverso](#load-balancer-vs-reverse-proxy)
* [Nivel de Applicacion](#application-layer)
    * [Microservicios](#microservices)
    * [Descubrimiento de servicios](#service-discovery)
* [Base de Datos](#database)
    * [Sistema de gestión de bases de datos relacionales (RDBMS)](#relational-database-management-system-rdbms)
        * [Amo-esclavo replicación](#master-slave-replication)
        * [Amo-amo replicación](#master-master-replication)
        * [Federación](#federation)
        * [Fragmentación](#sharding)
        * [Desnormalización](#denormalization)
        * [Ajuste de SQL](#sql-tuning)
    * [NoSQL](#nosql)
        * [Almacén de clave-valor](#key-value-store)
        * [Almacén de documentos](#document-store)
        * [Tienda de columna ancha](#wide-column-store)
        * [Base de datos de gráfos](#graph-database)
    * [SQL o NoSQL](#sql-or-nosql)
* [Cache](#cache)
    * [Almacenamiento en caché del cliente](#client-caching)
    * [Almacenamiento en caché del CDN](#cdn-caching)
    * [Almacenamiento en caché del servidor web](#web-server-caching)
    * [Almacenamiento en caché del la base de datos](#database-caching)
    * [Almacenamiento en caché de la aplicación](#application-caching)
    * [Almacenamiento en caché a nivel de consulta de la base de datos](#caching-at-the-database-query-level)
    * [Almacenamiento en caché a nivel de objeto](#caching-at-the-object-level)
    * [Cuando actualizar la caché](#when-to-update-the-cache)
        * [Caché en segundo plano](#cache-aside)
        * [Escribir a través](#write-through)
        * [Escribir hacia atras](#write-behind-write-back)
        * [Actualizar con anticipación](#refresh-ahead)
* [Asincronismo](#asynchronism)
    * [Colas de mensajes](#message-queues)
    * [Colas de tareas](#task-queues)
    * [Contrapresión](#back-pressure)
* [Comunicación](#communication)
    * [Protocolo de Control de Transmisión (TPC)](#transmission-control-protocol-tcp)
    * [Protocolo de Datagrama de Usuario (UDP)](#user-datagram-protocol-udp)
    * [Llamada a procedimiento remoto (RPC)](#remote-procedure-call-rpc)
    * [Transferencia de estado representacional (REST)](#representational-state-transfer-rest)
* [Seguridad](#security)
* [Apendice](#appendix)
    * [Tabla de potencias de dos](#powers-of-two-table)
    * [Números de latencia que todo programador debe conocer](#latency-numbers-every-programmer-should-know)
    * [Preguntas adicionales de la entrevista sobre el diseño del sistema](#additional-system-design-interview-questions)
    * [Arquitecturas del mundo real](#real-world-architectures)
    * [Arquitecturas de empresas](#company-architectures)
    * [Blogs de ingeniería de empresas](#company-engineering-blogs)
* [Bajo desarrollo](#under-development)
* [Créditos](#credits)
* [Informacion de contacto](#contact-info)
* [licencia](#license)

## Guia de estudio

> Temas sugeridos para revisar según el cronograma de su entrevista (corto, medio, largo) plazo.

![Imgur](images/OfVllex.png)

**Q: Para entrevistados, necesito saber todos estos temas?**

**A: No, no necesitas saber todo aqui para prepararte para le entrevista**.

Lo que se te pregunta en una entrevista depende de variables como:

* Cuanta experiencia tienes
* Cuales son tus antecedentes tecnicos
* Para qué puestos estás entrevistando
* Con qué empresas estás entrevistando
* Suerte

Por lo general, se espera que los candidatos con más experiencia sepan más sobre el diseño de sistemas. Se puede esperar que los arquitectos o líderes de equipo sepan más que los colaboradores individuales. Es probable que las empresas de alta tecnología tengan una o más rondas de entrevistas de diseño.

Comience amplio y profundice en algunas áreas. Es útil saber un poco sobre varios temas clave del diseño de sistemas. Ajuste la siguiente guía en función de su cronograma, experiencia, para qué puestos está entrevistando y con qué empresas está entrevistando.

* **Corto Plazo**: apunta a la **amplitud** con los temas de diseño del sistema. Practica resolviendo ** algunas ** preguntas de la entrevista.
* **Mediano Plazo**: apunta a **amplitud** y **algo de profundidad** con los temas de diseño del sistema. Practica resolviendo ** muchas ** preguntas de la entrevista.
* **Largo Plazo** - Apunta a **amplitud** y **más profundidad** con temas de diseño de sistemas. Practica resolviendo la **mayoría** de las preguntas de la entrevista.

| | Corto | Mediano | Largo |
|---|---|---|---|
| Lee sobre [temas de diseño de sistemas](#index-of-system-design-topics) para obtener una comprensión amplia de cómo funcionan los sistemas | :+1: | :+1: | :+1: |
| Lea algunos artículos sobre [Blogs de ingeniería de empresas](#company-engineering-blogs) para las empresas con las que está entrevistando | :+1: | :+1: | :+1: |
| Lea algunos [Arquitecturas del mundo real](#real-world-architectures) | :+1: | :+1: | :+1: |
| Revisa [Cómo abordar una pregunta de entrevista de diseño de sistema](#how-to-approach-a-system-design-interview-question) | :+1: | :+1: | :+1: |
| Trabaja a través de [Preguntas de la entrevista de diseño del sistema con soluciones](#system-design-interview-questions-with-solutions) | Algunos | Muchos | La mayoría |
| Trabaja a través de [Preguntas de entrevista de diseño orientado a objetos con soluciones](#object-oriented-design-interview-questions-with-solutions) | Algunos | Muchos | La mayoría |
| Revisa [Preguntas adicionales de la entrevista sobre el diseño del sistema](#additional-system-design-interview-questions) | Algunos | Muchos | La mayoría |

## Como abordar una pregunta de entrevista de diseño de sistemas

> Cómo abordar una pregunta de entrevista de diseño de sistema.

La entrevista de diseño de sistemas es un **conversacion abierta**. Tu debes ser quien la dirija.

Puedes usar los siguientes pasos para guiar la conversacion. Para ayudar a solidificar el proceso, trabaja a traves de la session de [Preguntas de la entrevista de diseño del sistema con soluciones](#system-design-interview-questions-with-solutions) usando los siguintes pasos.

### Paso 1: Describir casos de uso, restricciones y suposiciones.

Reune requerimientos y alcance del problema. Haz preguntas para aclarar casos de uso y restricciones. Dialoga suposiciones.

* Quien lo usara?
* Como lo usaran?
* Cuantos usuarios habra?
* Que hace el sistema?
* Cuales son las entradas y salidas del sistema?
* Cuanta informacion es esperada manejar?
* Cuantas peticiones por segundo se espera manejar?
* Cuál es la proporción esperada de lectura a escritura?

## Paso 2: Crea un diseño de alto nivel

Esboce un diseño de alto nivel con todos los componentes importantes.

* Realiza un bosquejo de los componentes principales y sus connecciones
* Justifica tus ideas

## Paso 3: Diseña componentes centrales

Profundiza en cada uno de los componentes centrales. Por ejemplo, si se te preguntara que [diseñes un servicio de acortamiento de urls](solutions/system_design/pastebin/README.md), discute:

* Generacion y almacenamiento de un hash de el url completo
    * [MD5](solutions/system_design/pastebin/README.md) and [Base62](solutions/system_design/pastebin/README.md)
    * Collisiones hash
    * SQL o NoSQL
    * Esquema de base de datos
* Traduciones el url hasheado al url completo
    * Busqueda en la base de datos
* API y diseño orientado a objectos

## Paso 4: Escala y diseño

Identifica y aborda enbotellamientos, dadas las restricciones. Por ejemplo, necesitas lo siguiente para abordar asuntos de escalabilidad?

* Equilibrador de carga
* Escalamiento horizontal
* Almacenamiento en caché
* Fragmentación de la base de datos

Dialoga las posibles soluciones y compensaciones. Todo es una compensación. Aborda enbotellamientos usando [los principios diseño de sistemas escalables](#index-of-system-design-topics).

### Cálculos del reverso del sobre

Se te podria preguntar que hagas unos calculos a mano. Dirigite al [Apendice](#appendix) para los siguientes recursos.

* [Utilice los cálculos del reverso del sobre](http://highscalability.com/blog/2011/1/26/google-pro-tip-use-back-of-the-envelope-calculations-to-choo.html)
* [Tabla de potencias de dos](#powers-of-two-table)
* [Números de latencia que todo programador debe conocer](#latency-numbers-every-programmer-should-know)

### Fuente (s) y lectura adicional

Consulte los siguientes enlaces para tener una mejor idea de qué esperar:

* [Cómo lograr una entrevista de diseño de sistemas](https://www.palantir.com/2011/10/how-to-rock-a-systems-design-interview/)
* [La entrevista de diseño del sistema](http://www.hiredintech.com/system-design)
* [Introducción a las entrevistas de diseño de sistemas y arquitectura](https://www.youtube.com/watch?v=ZgdS0EUmn70)
* [Plantilla de diseño del sistema](https://leetcode.com/discuss/career/229177/My-System-Design-Template)

## Preguntas de entrevista sobre diseño de sistemas con soluciones

> Preguntas comunes de entrevista sobre diseño de sistemas con ejemplos de dialogo, codigo y diagramas.
>
> Soluciones vinculadas al contenido estan la carpeta de `solutions/`.

| Question | |
|---|---|
| Diseña un Pastebin.com (o Bit.ly) | [Solucion](solutions/system_design/pastebin/README.md) |
| Diseña la busqueda y el muro en Twitter (o la busqueda y el muro de Facebook ) | [Solucion](solutions/system_design/twitter/README.md) |
| Diseña rastreador web | [Solucion](solutions/system_design/web_crawler/README.md) |
| Diseña Mint.com | [Solucion](solutions/system_design/mint/README.md) |
| Diseña la estructura de datos de una red social | [Solucion](solutions/system_design/social_graph/README.md) |
| Diseña un almancemiento de clave-valor para un motor de busqueda | [Solucion](solutions/system_design/query_cache/README.md) |
| Diseña el ranking de ventas de Amazon por función de categoría | [Solucion](solutions/system_design/sales_rank/README.md) |
| Diseña un sistema que se escale a millones de usuarios en AWS | [Solucion](solutions/system_design/scaling_aws/README.md) |
| Agregar una pregunta de diseño del sistema | [Contribuye](#contributing) |

### Diseña un Pastebin.com (o Bit.ly)

[Ver ejercicio y solución](solutions/system_design/pastebin/README.md)

![Imgur](images/4edXG0T.png)

### Diseña la busqueda y el muro en Twitter (o la busqueda y el muro de Facebook )

[Ver ejercicio y solución](solutions/system_design/twitter/README.md)

![Imgur](images/jrUBAF7.png)

### Diseña rastreador web

[Ver ejercicio y solución](solutions/system_design/web_crawler/README.md)

![Imgur](images/bWxPtQA.png)

### Diseña Mint.com

[Ver ejercicio y solución](solutions/system_design/mint/README.md)

![Imgur](images/V5q57vU.png)

### Diseña la estructura de datos de una red social

[Ver ejercicio y solución](solutions/system_design/social_graph/README.md)

![Imgur](images/cdCv5g7.png)

### Diseña el almancemiento clave-valor para un motor de busqueda

[Ver ejercicio y solución](solutions/system_design/query_cache/README.md)

![Imgur](images/4j99mhe.png)

### Diseña el ranking de ventas de Amazon por función de categoría

[Ver ejercicio y solución](solutions/system_design/sales_rank/README.md)

![Imgur](images/MzExP06.png)

### Diseña un sistema que se escale a millones de usuarios en AWS

[Ver ejercicio y solución](solutions/system_design/scaling_aws/README.md)

![Imgur](images/jj3A5N8.png)

## Preguntas de entrevista de diseño orientado a objetos con soluciones

> Preguntas comunes de entrevista de diseño orientado a objetos con ejemplos de dialogo, codigo y diagramas.
>
> Soluciones vinculadas al contenido estan la carpeta de `solutions/`.

>**Nota: Esta seccion se encuentra bajo desarrollo**

| Preguntas | |
|---|---|
| Diseña un mapa hash | [Solucion](solutions/object_oriented_design/hash_table/hash_map.ipynb)  |
| Diseñar una caché usada menos recientemente | [Solucion](solutions/object_oriented_design/lru_cache/lru_cache.ipynb)  |
| Diseñar un centro de llamadas | [Solucion](solutions/object_oriented_design/call_center/call_center.ipynb)  |
| Diseña una baraja de cartas | [Solucion](solutions/object_oriented_design/deck_of_cards/deck_of_cards.ipynb)  |
| Diseñar un estacionamiento | [Solucion](solutions/object_oriented_design/parking_lot/parking_lot.ipynb)  |
| Diseña un servidor de chat | [Solucion](solutions/object_oriented_design/online_chat/online_chat.ipynb)  |
| Diseña una arreglo circular | [Contribuye](#contributing)  |
| Agregar una pregunta de diseño orientado a objetos | [Contribuye](#contributing) |