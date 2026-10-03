# Fase 2 · Diagnóstico pre-contacto
**Prospecto:** Tu Techo Ideal Inmobiliaria en Caracas · **Nicho:** `inmobiliario` (venta, alquiler y terrenos) · **Fecha de recolección:** 03-oct-2026
**Fuentes:** Instagram @inmobiliaria_tutechoideal (Apify: perfil, 6 publicaciones, comentarios de 3 publicaciones), sitio tutechoideal.com (navegador), datos del registro de Airtable.

## 2.1 Resumen ejecutivo
Tu Techo Ideal tiene una comunidad sólida (19.755 seguidores, 478 publicaciones, más de 7 años en el mercado según su bio) y una oferta muy variada: apartamentos, oficinas, terrenos y galpones. Su contenido genera conversación real: un solo reel acumula 356 comentarios. Las fugas más costosas que se ven desde afuera: (1) interesados con intención clara en los comentarios sin respuesta visible, (2) el canal de contacto depende de que la persona escriba o agende por su cuenta, sin calificación ni agenda en línea verificables, y (3) las campañas recientes con llamado a la acción ("comenta ONYX") muestran muy poca interacción.

## 2.2 Observaciones verificadas

| Canal | Observación | Evidencia | Impacto comercial |
|---|---|---|---|
| Instagram | Cuenta de negocio con 19.755 seguidores, 478 publicaciones y bio con enlace a Linktree | Datos del perfil (Apify) | Audiencia suficiente para generar flujo constante de interesados |
| Instagram · comentarios | El reel del 13-nov-2025 ("¿Buscas vender, alquilar o comprar en Caracas?") tiene 356 comentarios. En los 20 más recientes, 6 expresan intención explícita: compra con crédito hipotecario, alquilar y/o vender, compra en curso, terreno de 43 mil m² en Guatire, vender en Caracas | Texto de los comentarios, usuarios `arlenedesideria`, `casadejuan.ccs`, `yrenemariasanchez`, `sofia368887`, `bettinabenoudiz`, `ansofcano` | Son prospectos de captación (propietarios) y de demanda (compradores) que piden atención en público |
| Instagram · comentarios | Los otros 14 de esos 20 comentarios son una sola palabra ("Ideal" o "Real"), propia de una dinámica de palabra clave | Texto de los comentarios | Cada uno es un posible interesado que necesita un siguiente paso ordenado |
| Instagram · comentarios | En los 25 comentarios recolectados de 3 publicaciones, ninguno muestra respuesta de la cuenta a una consulta (el único comentario de la cuenta es un emoji en un blooper). El campo de respuestas viene vacío | Apify, campo `repliesCount` sin valor | Interesados con intención sin respuesta visible (sujeto a que el scraper no capte todas las respuestas) |
| Instagram · alquiler | En el reel de alquiler en Los Palos Grandes (29-sep) hay 2 comentarios con dudas sobre precio y zona, sin respuesta visible. La descripción cierra con "agenda una visita" sin indicar cómo | Comentarios de `rickmsusa` y `aitorandony72`; texto de la descripción | La duda sin resolver y el contacto poco claro enfrían al interesado |
| Instagram · campañas | Los 3 reels más recientes (29 y 30-sep) tienen entre 6 y 11 likes y entre 0 y 4 comentarios. El reel "ONYX" pide comentar la palabra para recibir acceso por DM y tiene 0 comentarios | Apify (`likesCount`, `commentsCount`) | Hoy el alcance de las campañas nuevas parece muy inferior al de publicaciones anteriores del mismo perfil (3.528 y 14.779 likes en dos "VENDIDO") |
| Sitio web | Tiene botón de WhatsApp, formulario de contacto (nombre, correo, mensaje), buscador por operación, tipo y ubicación, y botón "Agendar visita" en cada ficha | Revisión de la página de inicio y su código | Buena base de captación en web; falta confirmar qué ocurre tras cada acción |
| Sitio web | En el texto visible de la página no aparece un chat de atención ni un calendario de citas; "Agendar visita" lleva a la ficha del inmueble | Revisión de texto y enlaces de la página de inicio | La persona debe actuar por su cuenta; no hay calificación inicial visible (zona, presupuesto, crédito) |
| Google | Calificación 5,0 con 10 reseñas | Registro de Airtable | Buena reputación, pero con poca presencia de reseñas para el tamaño de la audiencia |

**Inferencias a validar en la llamada**

- Probablemente el equipo responde mensajes y comentarios de forma manual, según disponibilidad de los asesores.
- La palabra clave "Ideal" parece formar parte de una dinámica de comentarios con envío posterior por DM; no se puede confirmar si es automática o manual.
- Es posible que parte de las respuestas a comentarios se den por mensaje privado y por eso no se vean en público.
- No se sabe si existe un CRM donde se registre el tipo de lead (propietario que vende, comprador, inversionista) ni su origen.
- El contenido del Linktree de la bio y la experiencia real al agendar visita no fueron verificados.
- **WhatsApp:** no verificable con lo recibido — prueba de tiempo de respuesta pendiente en llamada.

## 2.3 Estimación financiera
**Fórmula (misma de la app de Auditoría en Vivo):**
- Ingreso potencial mensual = consultas con potencial al mes × tasa de cierre × ticket promedio.
- Exposición mensual = ingreso potencial × % de fuga.

**Supuestos (todos son estimaciones prudentes, a validar con ellos en la llamada):**
- *Consultas con potencial al mes:* con 356 comentarios en un solo reel, varios reels activos y la audiencia de 19.755 seguidores, se asume entre 40 (conservador) y 80 (probable) personas al mes que escriben por comentario, DM, WhatsApp o web con interés real.
- *Tasa de cierre:* 3 % (conservador) y 5 % (probable), rango prudente para inmobiliarias con operaciones de ticket alto.
- *Ticket promedio:* ingreso por operación para la agencia, estimado en $2.000 (conservador) y $3.000 (probable). Para referencia, el sitio publica inmuebles desde $50.000 hasta $2.250.000; se asume una comisión baja sobre esos montos.
- *Fuga:* 15 % (conservador) y 30 % (probable), por los comentarios con intención sin respuesta visible y la falta de calificación y agenda verificables.

| Escenario | Consultas/mes | Cierre | Ticket | Ingreso potencial | Fuga | Exposición mensual |
|---|---|---|---|---|---|---|
| Conservador | 40 | 3 % | $2.000 | $2.400 | 15 % | **$360** |
| Probable | 80 | 5 % | $3.000 | $12.000 | 30 % | **$3.600** |

Con supuestos prudentes, la fuga equivale a entre $360 y $3.600 al mes. Son estimaciones, no resultados garantizados.
