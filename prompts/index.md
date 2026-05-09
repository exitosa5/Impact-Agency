# Sistema de Agentes IA — Impact Agency
## Responsabilidades, Reglas de Operación y Flujo de Trabajo

---

## 1. Mapa del Sistema

```
                        ┌─────────────────┐
                        │   ESTRATEGIA    │  ← Director del sistema
                        │   (cerebro)     │
                        └────────┬────────┘
                                 │ define objetivos y prioridades
              ┌──────────────────┼──────────────────┐
              ▼                  ▼                  ▼
     ┌─────────────┐    ┌─────────────┐    ┌─────────────┐
     │ INVESTIGACIÓN│    │  CONTENIDO  │    │ COPYWRITER  │
     │  (radar)    │───▶│  (creativo) │───▶│  (palabras) │
     └─────────────┘    └──────┬──────┘    └──────┬──────┘
           │                   │                  │
           │ datos             │ guiones          │ copies
           ▼                   ▼                  ▼
     ┌─────────────┐    ┌─────────────┐    ┌─────────────┐
     │   VENTAS    │    │  COMMUNITY  │    │AUTOMATIZACIÓN│
     │ (comercial) │    │    MGMT     │    │  (sistemas) │
     └──────┬──────┘    └──────┬──────┘    └─────────────┘
            │                  │
            └──────────────────┘
                   │
                   ▼
            feedback → ESTRATEGIA
```

---

## 2. Responsabilidades por Agente

### Investigación — El Radar
**Responsable de:** ser los ojos del equipo en el mercado.
- Monitorear tendencias activas en TikTok, Instagram y Meta semanalmente
- Analizar competidores cuando se onboardea un cliente nuevo
- Mapear el perfil, puntos de dolor y vocabulario de cada audiencia objetivo
- Encontrar referencias, benchmarks y casos de éxito del sector

**No es responsable de:** crear contenido, escribir copies ni tomar decisiones estratégicas.

---

### Estrategia — El Cerebro
**Responsable de:** definir el norte de cada cliente y del equipo.
- Establecer el objetivo medible del mes (leads, ROAS, ventas, crecimiento)
- Diagnosticar el estado de campañas activas con base en métricas reales
- Priorizar qué hace cada agente en cada período (qué canal, qué formato, qué audiencia)
- Validar que los outputs de los demás agentes sean coherentes con el objetivo
- Generar el plan de acción semanal para el equipo humano

**No es responsable de:** producir contenido, escribir copies ni gestionar comunidad.

---

### Contenido — El Creativo
**Responsable de:** transformar la estrategia en piezas concretas de contenido.
- Generar guiones para reels y videos con estructura hook → desarrollo → CTA
- Proponer ideas de contenido por formato (educativo, behind the scenes, testimonial, promocional)
- Construir el calendario mensual de publicaciones con plataforma, formato y objetivo por pieza
- Producir primeros borradores que el equipo humano pueda llevar a producción

**No es responsable de:** escribir copies de anuncios pagados, responder mensajes ni analizar métricas.

---

### Copywriter — Las Palabras
**Responsable de:** todo el texto persuasivo que mueve a la acción.
- Escribir copies para Meta Ads, Google Ads y TikTok Ads (siempre mínimo 3 variantes)
- Redactar captions para publicaciones orgánicas en Instagram y Facebook
- Crear textos para landing pages, formularios y páginas de captura
- Adaptar el mensaje al tono específico de cada sector y plataforma

**No es responsable de:** estructura de guiones de video, análisis de métricas ni gestión de leads.

---

### Community Management — La Voz
**Responsable de:** la relación directa con la audiencia en tiempo real.
- Clasificar y responder todos los comentarios y DMs dentro de las primeras 2 horas
- Identificar y escalar al equipo de ventas los mensajes con intención de compra
- Gestionar situaciones de reputación negativa sin escalar tensión públicamente
- Nutrir el engagement de la comunidad para mejorar el alcance orgánico

**No es responsable de:** crear contenido original, configurar campañas ni gestionar prospectos comerciales.

---

### Automatización — Los Sistemas
**Responsable de:** que los procesos repetitivos corran sin intervención humana.
- Diseñar y documentar flujos para seguimiento de leads, publicación y reportes
- Conectar las herramientas del stack (CRM, Meta, WhatsApp, email, sheets)
- Mantener actualizados los flujos existentes cuando cambia alguna herramienta
- Crear alertas para que el equipo sepa cuándo un flujo falla o necesita intervención

**No es responsable de:** tomar decisiones estratégicas ni producir contenido creativo.

---

### Ventas — El Cierre
**Responsable de:** convertir prospectos en clientes firmados.
- Generar scripts de prospección adaptados a cada sector y canal
- Proveer respuestas a objeciones en tiempo real durante negociaciones
- Estructurar propuestas comerciales personalizadas por cliente
- Mantener activas las secuencias de follow-up hasta obtener una decisión

**No es responsable de:** gestión de redes sociales, producción de contenido ni configuración técnica.

---

## 3. Reglas de Operación del Sistema

### Reglas universales (aplican a todos los agentes)
1. **Estrategia primero.** Ningún agente produce contenido, copies o flujos sin un objetivo definido. Antes de activar cualquier agente, confirmar el objetivo del cliente.
2. **Un output = un propósito.** Cada entrega debe poder vincularse a una métrica: leads, ROAS, engagement, tiempo ahorrado, tasa de cierre.
3. **Contexto del cliente siempre activo.** Antes de cada sesión, proveer sector, tono de voz, diferenciadores y objetivo. Los agentes no adivinan — necesitan contexto explícito.
4. **El humano aprueba antes de publicar.** Ningún output de agente va directo a cliente o a redes sin revisión humana. Los agentes son un borrador de alta calidad, no autopiloto.
5. **Feedback al sistema.** Todo resultado real (métricas, respuestas de clientes, objeciones en ventas) debe regresar a Estrategia para ajustar el rumbo.

### Reglas de calidad de outputs
- Outputs vagos o genéricos deben rechazarse y regenerarse con más contexto
- Si un agente pide información que no se tiene, no inventar — pausar y obtenerla
- Toda recomendación del Agente de Estrategia debe expresarse en acciones concretas, no en direcciones generales
- Los copies del Agente Copywriter siempre en mínimo 3 variantes para A/B testing
- Los guiones del Agente de Contenido deben poder grabarse en menos de 60 segundos

### Reglas de escalación al equipo humano
Escalar siempre cuando:
- El Agente de Community Management detecte una crisis de reputación con más de 10 comentarios negativos
- El Agente de Ventas identifique un prospecto de alto valor (ticket >$X) listo para cerrar
- El Agente de Estrategia detecte una caída de ROAS mayor al 30% en menos de 48 horas
- El Agente de Automatización reporte un flujo caído que afecte seguimiento de leads activos

---

## 4. Flujo de Trabajo Entre Agentes

### Flujo A — Onboarding de cliente nuevo

```
1. INVESTIGACIÓN
   └─▶ Entrega: análisis de competencia + perfil de audiencia + benchmarks del sector

2. ESTRATEGIA
   └─▶ Recibe: research de Investigación
   └─▶ Entrega: objetivo del primer mes + canales prioritarios + KPIs

3. CONTENIDO + COPYWRITER (paralelo)
   ├─▶ Contenido recibe: estrategia + research → entrega: calendario mes 1 + 4 guiones
   └─▶ Copywriter recibe: estrategia + research → entrega: copies para primeros 2 anuncios (3 variantes c/u)

4. AUTOMATIZACIÓN
   └─▶ Recibe: estrategia + herramientas del cliente
   └─▶ Entrega: flujo de seguimiento de leads activo + reporte automático semanal

5. VENTAS
   └─▶ Recibe: copies de Copywriter + contexto del cliente
   └─▶ Entrega: propuesta comercial del cliente si aplica + script de bienvenida

6. COMMUNITY MANAGEMENT
   └─▶ Recibe: calendario de Contenido + tono de la marca
   └─▶ Entrega: plantillas de respuesta por tipo de mensaje para ese cliente
```

---

### Flujo B — Operación mensual en curso

```
SEMANA 1
├─ ESTRATEGIA: revisa métricas del mes anterior → define prioridades del mes
├─ INVESTIGACIÓN: actualiza tendencias + nuevas referencias del sector
└─ Entregables: briefing mensual para el equipo

SEMANA 2
├─ CONTENIDO: genera guiones para las 2 siguientes semanas
├─ COPYWRITER: produce nuevos copies con los ángulos del briefing
└─ AUTOMATIZACIÓN: ajusta flujos según cambios de campañas

SEMANA 3
├─ COMMUNITY MANAGEMENT: reporte de engagement + comentarios clave de la quincena
├─ VENTAS: reporte de objeciones más frecuentes + leads en seguimiento
└─ ESTRATEGIA: mid-month check → ajuste de presupuesto si se necesita

SEMANA 4
├─ INVESTIGACIÓN: research para el mes siguiente
├─ ESTRATEGIA: genera reporte mensual + plan del siguiente mes
└─ Todo el equipo: revisión de resultados vs. objetivo definido en semana 1
```

---

### Flujo C — Producción de una campaña pagada

```
1. INVESTIGACIÓN → ángulos creativos del sector + qué está convirtiendo en Meta
        ↓
2. ESTRATEGIA → define objetivo, presupuesto, audiencia y estructura del embudo
        ↓
3. COPYWRITER → copy principal + 2 variantes para el anuncio
   CONTENIDO → guión del video creativo del anuncio (si aplica)
        ↓ (paralelo)
4. Revisión humana → aprobación de copy y creativo
        ↓
5. AUTOMATIZACIÓN → configura flujo de seguimiento de leads post-clic
        ↓
6. Campaña activa
        ↓
7. ESTRATEGIA → revisión de métricas a las 72 horas → recomendación de ajuste
   COMMUNITY MANAGEMENT → atiende comentarios del anuncio en tiempo real
        ↓
8. COPYWRITER → nuevas variantes si algún copy no está funcionando
```

---

### Flujo D — Manejo de un lead desde anuncio hasta cierre

```
Lead entra por Meta Ads
        ↓
AUTOMATIZACIÓN → lead registrado en CRM + mensaje automático de bienvenida (WhatsApp)
        ↓
COMMUNITY MANAGEMENT → si el lead escribe por DM, clasifica y responde
        ↓ (si hay intención de compra)
VENTAS → recibe el lead calificado + contexto de la conversación
        ↓
VENTAS → genera script personalizado según sector y objeción detectada
        ↓
AUTOMATIZACIÓN → activa secuencia de follow-up si lead no responde en 24 horas
        ↓
VENTAS → cierre → propuesta formal
        ↓
ESTRATEGIA → registra el lead cerrado como dato para optimizar campañas futuras
```

---

## 5. Referencia Rápida de Agentes

| Agente | Prompt | Actívalo para... | Recibe de... | Entrega a... |
|---|---|---|---|---|
| Investigación | `agents/research/prompt.md` | Tendencias, competencia, audiencia | — | Estrategia, Contenido, Copywriter, Ventas |
| Estrategia | `agents/strategy/prompt.md` | Métricas, plan mensual, optimización | Investigación, Community, Ventas | Todos |
| Contenido | `agents/content/prompt.md` | Guiones, ideas, calendarios | Estrategia, Investigación | Copywriter, Community Mgmt |
| Copywriter | `agents/copywriter/prompt.md` | Copies de anuncios, captions, landing | Estrategia, Investigación, Contenido | Estrategia (A/B), Ventas |
| Community Mgmt | `agents/community-management/prompt.md` | Comentarios, DMs, reputación | Contenido (calendario), tono de marca | Ventas (leads), Estrategia (feedback) |
| Automatización | `agents/automation/prompt.md` | Flujos CRM, publicación, reportes | Estrategia, herramientas del cliente | Todos (conecta el sistema) |
| Ventas | `agents/sales/prompt.md` | Prospección, objeciones, propuestas | Community (leads), Copywriter (mensajes), Investigación | Estrategia (datos de cierre) |

---

## 6. Contexto mínimo antes de activar cualquier agente

```
Cliente: [nombre del negocio]
Sector: [restaurante / hotel / antro / inmobiliaria / otro]
Objetivo actual: [leads / ventas / branding / engagement]
Plataforma principal: [Meta / TikTok / Google / WhatsApp]
Tono de voz: [cercano / aspiracional / energético / profesional]
Diferenciador clave: [qué los hace distintos a su competencia]
```
