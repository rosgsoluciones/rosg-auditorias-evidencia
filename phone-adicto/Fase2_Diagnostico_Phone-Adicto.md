# Fase 2 · Diagnóstico pre-contacto
**Prospecto:** Phone Adicto · **Nicho:** `retail` (venta de equipos Apple usados, Caracas) · **Fecha de recolección:** 05-oct-2026
**Fuentes:** Instagram @phone.adicto (Apify: perfil, publicaciones y comentarios de una publicación) y Linktree de la bio.

## 2.1 Resumen ejecutivo
Phone Adicto tiene 107.211 seguidores y 1.904 publicaciones, y vende equipos Apple usados con delivery y envíos por ZOOM en Caracas. Las 12 publicaciones recientes suman entre 0 y 13 comentarios cada una. En la publicación leída, los 5 comentarios piden información, disponibilidad o fotos, sin respuesta visible. El Linktree reparte la atención entre cinco asesores por WhatsApp, y la oportunidad es ordenar esas consultas en un solo flujo.

## 2.2 Observaciones verificadas

| Canal | Observación | Evidencia | Impacto comercial |
|---|---|---|---|
| Instagram | 107.211 seguidores y 1.904 publicaciones; la bio ofrece equipos Apple usados, delivery y envíos por ZOOM en Caracas | Datos del perfil (Apify) | Audiencia grande con un catálogo que cambia a diario |
| Instagram · alcance | Las 12 publicaciones recientes suman entre 0 y 13 comentarios cada una; hay publicaciones con precios desde $239 | Métricas de publicación (Apify) | Consultas repartidas en muchas publicaciones de producto |
| Instagram · comentarios | Los 5 comentarios leídos en una publicación de MacBook piden información, disponibilidad y fotos o piden respuesta por mensaje privado | Comentarios (Apify) | Preguntas repetidas sobre disponibilidad que una respuesta automática puede resolver |
| Instagram · respuestas | Ninguno de los 5 comentarios leídos tiene respuesta visible | Campo de respuestas vacío (Apify) | Consultas sin respuesta visible; pudieron resolverse por mensaje privado |
| Sitio web · contacto | El Linktree de la bio lista cinco asesores de ventas por WhatsApp y un catálogo en Google Drive | Lectura del enlace (WebFetch) | La atención se reparte entre varios números sin un flujo único visible |

**Inferencias a validar en la llamada**

- Probablemente cada asesor atiende y registra sus consultas por separado.
- Es posible que el catálogo en Drive se actualice a mano.
- No se sabe cuántas consultas llegan al mes ni cuántas se convierten en venta.
- No se sabe cómo se asigna un cliente a un asesor.
- **WhatsApp (+58 424 159 2345 según el registro; el Linktree de la bio lista cinco asesores de ventas por WhatsApp):** no verificable con lo recibido — prueba de tiempo de respuesta pendiente en llamada.

## 2.3 Estimación financiera
**Fórmula (misma de la app de Auditoría en Vivo):**
- Ingreso potencial mensual = consultas con potencial al mes × tasa de cierre × ticket promedio.
- Exposición mensual = ingreso potencial × % de fuga.

**Supuestos (estimaciones prudentes, a validar con ellos en la llamada):**
- *Consultas con potencial al mes:* con 107.211 seguidores pero publicaciones con pocos comentarios, se estiman 30 (conservador) y 80 (probable) consultas al mes con intención real, a validar con los asesores.
- *Tasa de cierre:* 20 % (conservador) y 30 % (probable), por tratarse de equipos usados con disponibilidad puntual.
- *Ticket promedio:* $250 (conservador) y $350 (probable); en las publicaciones leídas hay precios desde $239 hasta $459.
- *Fuga:* 15 % (conservador) y 25 % (probable); no se ven respuestas en comentarios, pero pudieron darse por privado, que es una hipótesis a validar.

| Escenario | Consultas/mes | Cierre | Ticket | Ingreso potencial | Fuga | Exposición mensual |
|---|---|---|---|---|---|---|
| Conservador | 30 | 20 % | $250 | $1.500 | 15 % | **$225** |
| Probable | 80 | 30 % | $350 | $8.400 | 25 % | **$2.100** |

Con supuestos prudentes, la fuga equivale a entre $225 y $2.100 al mes. Son estimaciones, no resultados garantizados. El argumento principal es el volumen: responder a tiempo lo repetitivo y dejar al equipo las ventas.
