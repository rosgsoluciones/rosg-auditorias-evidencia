# Fase 5 · Ficha JSON para Auditoría en Vivo
**Prospecto:** Skinklinik Med Spa

```json
{
  "ficha_rosg": 1,
  "cliente": {
    "nombre": "Skinklinik Med Spa",
    "nicho": "salud",
    "subnicho": "clínica de estética y spa con depilación láser, faciales y tratamientos corporales",
    "ciudad": "Monterrey, Nuevo León, México",
    "instagram": "",
    "web": "https://skinklinik.mx/",
    "whatsapp": "+528112286916",
    "email": "",
    "decisor": "",
    "sedes": "12 sucursales listadas en el sitio: seis en el área de Monterrey, cuatro en Ciudad de México, una en Saltillo y una en Tijuana"
  },
  "resumen_previo": "Skinklinik reúne servicios faciales, de spa, corporales y de depilación láser en 12 sucursales de Monterrey, Ciudad de México, Saltillo y Tijuana, y ofrece una valoración gratuita. El sitio publica un WhatsApp general, un call center y un WhatsApp distinto por cada sucursal. No se vio agenda en línea con horarios. El diagnóstico se basa solo en el sitio web, porque no se recibió evidencia de Instagram.",
  "observaciones": [
    "Presenta facial, spa, tratamientos estéticos, corporales y depilación láser, con una promoción de retiro de tatuajes (6 sesiones con 35 % de descuento) y la invitación Agenda tu valoración gratis",
    "12 sucursales con un WhatsApp distinto cada una, un call center (81) 1234 1737 y un WhatsApp general",
    "Hay formulario (nombre, correo, celular, ciudad y mensaje) y enlace de WhatsApp; no se vio agenda en línea con horarios",
    "Atención de lunes a viernes de 8 am a 8 pm, sábados de 9 am a 4 pm y domingo cerrado",
    "No se recibió evidencia: el perfil enlazado en el sitio no pudo recuperarse con Apify",
    "Tiempo de respuesta de WhatsApp: no verificable con lo recibido; prueba pendiente en llamada."
  ],
  "preguntas_extra": {
    "captacion": [
      {
        "tema": "Sucursales",
        "pregunta": "Cuando alguien escribe al WhatsApp general, ¿cómo se decide a qué sucursal se deriva?",
        "opciones": [
          "No se deriva, se atiende todo ahí",
          "Se pregunta la ciudad al final de la conversación",
          "Se pregunta la zona y se pasa el número de la sucursal",
          "Se pregunta la zona al inicio y se envía a la sucursal más cercana con su horario"
        ],
        "recomendacion": "Preguntar la zona al inicio y derivar a la sucursal más cercana con su horario y su WhatsApp."
      }
    ],
    "triaje": [],
    "agenda": [
      {
        "tema": "Valoración gratis",
        "pregunta": "Cuando alguien pide la valoración gratuita, ¿cómo se confirma y se recuerda la cita?",
        "opciones": [
          "No se confirma",
          "Se confirma por llamada cuando hay tiempo",
          "Se confirma por mensaje, sin recordatorio",
          "Se confirma por mensaje y se envía un recordatorio antes de la cita"
        ],
        "recomendacion": "Confirmar por mensaje y enviar un recordatorio antes de la valoración."
      }
    ],
    "crm": []
  },
  "calculadora": {
    "leads_mes": 400,
    "ticket": 110,
    "cierre": 30
  },
  "propuesta": {
    "titular": "",
    "subtitular": "",
    "introduccion": "",
    "soluciones": [],
    "nota": ""
  },
  "plataformas_sugeridas": [
    {
      "id": "achieveapex",
      "plan": "professional"
    }
  ]
}
```

Abra Auditoria-en-Vivo-ROSG.html → Cargar ficha → pegue este bloque.
