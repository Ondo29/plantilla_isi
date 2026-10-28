# Historias de usuario de búsqueda

| Campo | Valor |
| --- | --- |
| Proyecto | Proyecto Simbiosis |
| Estudiante | [jacinta Ondó] |
| Grupo | [ISI_n] |
| Fecha | [28/10/2026] |
| Versión | [Versión de trabajo] |
| Estado | Borrador |

## Fuentes comunes

- [Acta de UC-21 Buscar recetas](../captura/acta-acuerdos-uc-21-buscar-recetas.md), v1.1, Vigente.
- [Catálogo de requisitos](catalogo-requisitos.md), UR-08 y FR pertinentes.
- [Modelo de casos de uso](../modelos/modelo-casos-de-uso.md), UC-21.

## Épica de búsqueda

Una épica expresa una necesidad amplia que se descompone en historias con valor propio.

Como [rol], quiero [capacidad amplia], para [beneficio].

**Estado:** descompuesta en US-01, US-02 y US-03. Conserva la necesidad conjunta. No cuenta como una cuarta historia de la entrega.

## Justificación de la división

[un cliente esta buscando por internet alimentos que empiecen con ciertas frases o palabras , en el que estan incluidos 
ciertos ingredientes  y excluidos otros ingredientes.]

## US-01

**Título:** [Buscar alimentos]

Como cliente quiero buscar alimentos que empiecen con la palabra alegría para encontrar lo que necesito con mayor rapidez ].

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado [el cliente esta comprando online], cuando [ introduce una palabra relacionada  con un alimento en el buscador], entonces [el sistema muetra los productos].
- **CA-02.** Dado [que el cliente esta en la tienda online], cuando [introduce una frase en el buscador ], entonces [el sistema debe mostrar los productos que coicidan  con los terminos de la busqueda].
- **CA-03.** Dado [que el cliente haya introducido una palabra o frase], cuando [ningun producto coincide con la busqueda], entonces [tiene que introducir una nueva palabra o frase].

## US-02

**Título:** [Buscar por ingredientes]

Como cliente de una tienda online quiero buscar por ingrdientes especificos para así encontrar exactamente lo que necesito encontrar .

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado [el cliente está comprando online, cuando [introduce en la busqueda un ingrdiente especifico], entonces [el sistema muestra los productos con ese ingrediente].
- **CA-02.** Dado [el cliente sigue en la tienda online], cuando [introduce un ingrediente en el buscador], entonces [el sistema muestra roductos que coinciden con la busqueda].
- **CA-03.** Dado [el cliente introduce un ingrediente ], cuando [ningun producto coincide con la busqueda], entonces [tiene que volver a empezar ].

## US-03

**Título:** [buscar por ingredientes excluidos]

Como cliente quiero localizar alimentos que excluyan ciertos ingredientes, para no interferir en la busqueda .

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado [el cliente esta comprado online, cuando [pone en la busqueda alimentos en el que excluye ciertos ingredientes], entonces [el sistema muestra los alimentos ].
- **CA-02.** Dado [el cliente sigue comprando online ], cuando [introduce los ingredientes excluidos], entonces [].
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## Mejora tras la revisión INVEST

[Indicar la mejora principal y su motivo. Si se mantiene la redacción, justificar una decisión concreta.]

## Dudas pendientes

[Indicar una duda real si queda algún criterio incompleto. Si no hay dudas, escribir «Ninguna».]

## Declaración de uso de IA

No he utilizado IA ( un poco) .
