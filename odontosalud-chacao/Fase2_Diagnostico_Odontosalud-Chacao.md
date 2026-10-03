# Fase 2 · Diagnóstico pre-contacto
**Prospecto:** Odontosalud Chacao (clínicas Chacao y CCCT) · **Nicho:** `salud` (clínica odontológica con láser y dos sedes, Chacao y Chuao, Caracas) · **Fecha de recolección:** 03-oct-2026
**Fuentes:** Instagram @odontosalud_official (Apify: perfil, 5 publicaciones asociadas al perfil, 12 comentarios de 1 publicación), sitio odontosalud.com (lectura web), datos del registro de Airtable. El registro rec9AvI5chK5Ogs3d (ODONTOSALUD) apunta al mismo sitio y quedó pendiente.

## 2.1 Resumen ejecutivo
Odontosalud, fundada en 1993 según su sitio, atiende en dos sedes (Chacao y Chuao) con una larga lista de servicios y odontología láser, y su Instagram tiene 30.972 seguidores. Lo que se ve desde afuera: el sitio publica el precio de la primera consulta ($30) y un WhatsApp, pero las publicaciones muestran al menos cuatro números de WhatsApp distintos, y el curso de odontología láser para colegas (56 comentarios) recibe pedidos de "información" y "precio" sin respuesta visible. No hay evidencia de pérdida de pacientes; la oportunidad es unificar el primer contacto de las dos sedes.

## 2.2 Observaciones verificadas

| Canal | Observación | Evidencia | Impacto comercial |
|---|---|---|---|
| Instagram | Perfil "Odontosalud®", 30.972 seguidores y 1.996 publicaciones; la bio indica marca registrada desde 1993, clínicas CCCT y Chacao y "odontología láser sin dolor" | Datos del perfil (Apify) | Marca consolidada con audiencia grande |
| Instagram · canales | Las publicaciones del 25-ago-2025, 20 y 30-sep-2026 y el curso del 23-sep-2026 muestran cuatro números de WhatsApp distintos (+58 424 244 5470, +58 412 264 0324, +58 414 231 5694 y +58 414 255 8223) | Descripciones de publicaciones | Cada publicación dirige a un número distinto; no hay un canal único visible |
| Instagram · sedes | Cada publicación repite direcciones y teléfonos de las dos sedes (Chacao y CCCT en Chuao), con 3 teléfonos fijos por sede | Descripciones del 20 y 30-sep-2026 | Información extensa que se repite a mano en cada publicación |
| Instagram · comentarios | En el curso "Dental Laser Experience" (23-sep-2026, 20.124 reproducciones, 56 comentarios) se leyeron 12: 10 piden "información" o "precio", 1 pregunta "Dónde en Mérida" y 1 es un emoji | `miguelrangel762`, `dra.rociougarte`, `omacaris` y otros | Demanda visible sin respuesta, aunque el curso es para colegas y no para pacientes |
| Instagram · respuestas | Los 12 comentarios leídos no tienen respuesta visible de la cuenta | Campo de respuestas vacío (Apify) | La entrega por mensaje privado, si existe, no se ve desde afuera |
| Instagram · interacción | Las demás publicaciones de la muestra tienen entre 14 y 293 "me gusta" y entre 0 y 13 comentarios | Métricas de publicación (Apify) | Audiencia grande con poca conversación pública sobre tratamientos |
| Sitio web | Lista 14 servicios, entre ellos odontología láser, implantología, ortodoncia y sedación endovenosa, y declara fundación en 1993 (el texto dice "29 años") | Lectura del sitio | Trayectoria larga; el texto de años parece desactualizado |
| Sitio web · agenda | WhatsApp +58 424 244 5470, teléfonos fijos, formulario en línea y atención de lunes a viernes de 9:00 a.m. a 5:00 p.m. | Lectura del sitio | Horario de oficina; no consta atención fuera de él |
| Sitio web · precio | Publica el precio de la primera consulta: $30 o su equivalente en bolívares BCV | Lectura del sitio | Una barrera menos para quien consulta el precio |
| Google | Calificación 5,0 con 3 reseñas para la sede de Chacao | Registro de Airtable | Pocas reseñas frente a la trayectoria |

**Inferencias a validar en la llamada**

- Probablemente cada doctor o sede maneja su propio número de WhatsApp.
- Es posible que las dos sedes agenden por separado.
- No se sabe cuántas solicitudes llegan por cada número ni cuántas se convierten en cita.
- No se conoce quién decide más allá del Dr. Jorge Luis Vergara, fundador según el sitio.
- Pudo haber consultas por mensaje privado que no se ven desde afuera.
- **WhatsApp (+58 424 244 5470):** no verificable con lo recibido — prueba de tiempo de respuesta pendiente en llamada.

## 2.3 Estimación financiera
**Fórmula (misma de la app de Auditoría en Vivo):**
- Ingreso potencial mensual = consultas con potencial al mes × tasa de cierre × ticket promedio.
- Exposición mensual = ingreso potencial × % de fuga.

**Supuestos (estimaciones prudentes, a validar con ellos en la llamada):**
- *Consultas con potencial al mes:* con 30.972 seguidores y dos sedes, se asumen entre 30 (conservador) y 70 (probable) personas al mes que piden cita o información de tratamientos con interés real, sin contar el curso para colegas.
- *Tasa de cierre:* 25 % (conservador) y 35 % (probable).
- *Ticket promedio:* ingreso por paciente nuevo en su primera consulta o tratamiento; se asumen $100 (conservador) y $180 (probable). La consulta inicial publicada es de $30.
- *Fuga:* 15 % (conservador) y 25 % (probable). En lo observado, los comentarios sin respuesta corresponden a un curso para colegas; la fuga en pacientes es una hipótesis a validar.

| Escenario | Consultas/mes | Cierre | Ticket | Ingreso potencial | Fuga | Exposición mensual |
|---|---|---|---|---|---|---|
| Conservador | 30 | 25 % | $100 | $750 | 15 % | **$112** |
| Probable | 70 | 35 % | $180 | $4.410 | 25 % | **$1.102** |

Con supuestos prudentes, la fuga equivale a entre $112 y $1.102 al mes. Son estimaciones, no resultados garantizados. Con dos sedes y varios números de WhatsApp, el argumento principal es unificar el primer contacto y la agenda, más que recuperar pacientes perdidos. La automatización se limita a procesos no clínicos: respuestas frecuentes, recolección de datos de contacto y agenda.
