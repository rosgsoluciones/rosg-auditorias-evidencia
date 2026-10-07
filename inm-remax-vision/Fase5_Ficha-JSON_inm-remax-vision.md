# Fase 5 · Ficha JSON para Auditoría en Vivo
**Prospecto:** RE/MAX Vision

```json
{
  "ficha_rosg": 1,
  "cliente": {
    "nombre": "RE/MAX Vision",
    "nicho": "inmobiliario",
    "subnicho": "oficina inmobiliaria de compra, venta y alquiler de propiedades",
    "ciudad": "Caracas, Miranda, Venezuela",
    "instagram": "",
    "web": "http://www.remax.com.ve/vision",
    "whatsapp": "+584242304404",
    "email": "",
    "decisor": "",
    "sedes": "Torre Humboldt, piso 6, oficina 6-11, Av. Río Caura, Prados del Este, Caracas (según el sitio)"
  },
  "resumen_previo": "RE/MAX Vision es una oficina en Prados del Este, Caracas, con 2 brokers y 6 agentes según el sitio. Lista propiedades residenciales, comerciales y terrenos, con ventas de $20.000 a $2,3 millones y alquileres de $110 a $3.900 al mes, además de recorridos virtuales de 360 grados. Publica WhatsApp, teléfono y correo. El Instagram mencionado no pudo verificarse, así que el diagnóstico se basa en el sitio. La oportunidad es ordenar consultas de muchos agentes y propiedades.",
  "observaciones": [
    "Oficina con 2 brokers y 6 agentes; propiedades residenciales, comerciales y terrenos en Caracas",
    "Ventas de $20.000 a $2,3 millones y alquileres de $110 a $3.900 al mes, con recorridos de 360 grados",
    "Publica WhatsApp +58 424 230 4404, correo de gerencia y dirección en Torre Humboldt",
    "En lo leído no se observó agenda de visitas ni calificación previa",
    "El sitio menciona @vision_remax, pero Apify indicó que el perfil no existe; no se recibió evidencia",
    "Tiempo de respuesta de WhatsApp: no verificable con lo recibido; prueba pendiente en llamada."
  ],
  "preguntas_extra": {
    "captacion": [],
    "triaje": [
      {
        "tema": "Asignación de consultas",
        "pregunta": "Cuando llega una consulta al WhatsApp de la oficina, ¿cómo se decide qué agente la atiende?",
        "opciones": [
          "No hay criterio definido",
          "Responde quien la ve primero",
          "Se reparte a mano por zona o tipo",
          "Se asigna por zona y tipo de propiedad con aviso al agente"
        ],
        "recomendacion": "Asignar por zona y tipo de propiedad con aviso inmediato al agente."
      }
    ],
    "agenda": [
      {
        "tema": "Visitas",
        "pregunta": "Cuando alguien quiere visitar una propiedad, ¿cómo se coordina el día y la hora?",
        "opciones": [
          "No se coordina de forma fija",
          "Se acuerda por mensajes sueltos",
          "Se anota en una agenda personal",
          "Se agenda con confirmación y recordatorio automático"
        ],
        "recomendacion": "Agendar la visita con confirmación y recordatorio para reducir las citas perdidas."
      }
    ],
    "crm": []
  },
  "calculadora": {
    "leads_mes": 90,
    "ticket": 3500,
    "cierre": 15
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
