# Captio — Documento de marca y producto

> Referencia interna para el equipo de diseño y marketing. Cubre identidad de marca, paleta de colores, features, casos de uso y propuesta de valor. Uso principal: landing page + pricing page + video demo page

---

## 1. El nombre

**Captio** viene del latín *captio* — "toma, captura, recepción". En derecho romano clásico también tenía el sentido de "captación de la intención", es decir, entender exactamente lo que alguien quiere expresar antes de actuar.

El nombre encapsula lo que hace el producto en una sola palabra:

- **Captura** la historia del cliente en el primer contacto.
- **Capta** su intención, sus miedos, sus prioridades — no solo los hechos.
- **Convierte** esa captura en un documento profesional listo para el abogado.

### Tagline

> **intake · brief · equipo** (ES)
> **intake · brief · team** (EN)

Los tres pilares del producto en tres palabras:

| Palabra | Significado |
|---|---|
| **intake** | La recepción del caso — el formulario que llena el cliente |
| **brief** | El resumen generado por IA que lee el abogado |
| **equipo** | La plataforma que conecta al equipo del despacho con cada caso |

---

## 2. Identidad visual

### Logotipo

El wordmark se escribe `capt·o` — la `i` es reemplazada por un punto azul (`·`). Es un guiño visual: la `i` de *intake*, la `i` de *IA*, el punto que marca el inicio de algo. El punto es el único elemento de color en el logo; todo lo demás es en navy oscuro.

```
capt · o
     ↑
   #3B6FE8 (azul Captio)
```

**Tipografía:** Inter — peso 700, letter-spacing -1. Limpio, moderno, sin serifas. Mismo font que la UI.

### Paleta de colores

| Nombre | Hex | Uso |
|---|---|---|
| **Azul Captio** | `#3B6FE8` | CTA, botones primarios, acento principal, links activos, el punto del logo |
| **Navy profundo** | `#1B2E5E` | Textos de encabezado, nav activo, versión oscura del acento |
| **Fondo claro** | `#F8F9FC` | Background principal — casi blanco con un toque azulado frío |
| **Fondo secundario** | `#EEF1F8` | Sidebar, cards, áreas de contenido secundario |
| **Texto primario** | `#1A1F36` | Todo el cuerpo de texto — navy casi negro |
| **Texto secundario** | `#6B7694` | Labels, subtítulos, metadata — azul grisáceo |
| **Texto terciario** | `#A0A8BF` | Placeholders, hints, texto desactivado |
| **Verde éxito** | `#22C55E` | Estado "Aceptado", confirmaciones, indicadores positivos |
| **Rojo peligro** | `#EF4444` | Errores, eliminar, estados críticos |
| **Ámbar advertencia** | `#F59E0B` | Plazos próximos, estados en revisión, alertas |
| **Morado** | `#8B5CF6` | Herramienta de resaltado, funciones secundarias |

### Por qué estos colores

El azul `#3B6FE8` es deliberadamente más vivo que el azul corporativo clásico (navy o royal blue), pero más sobrio que un azul tech saturado. Transmite **confianza + modernidad** — exactamente lo que un abogado necesita sentir al adoptar tecnología. No es un azul de startup de consumo; es un azul de herramienta profesional.

El navy `#1B2E5E` ancla la paleta en el mundo legal — evoca formalidad, precisión, seriedad — sin caer en el cliché del color corporativo aburrido.

El fondo `#F8F9FC` tiene un toque azulado frío casi imperceptible que mantiene la coherencia tonal con el resto de la paleta sin competir con el contenido.

---

## 3. Propuesta de valor central

> **Captio convierte el primer contacto con un cliente — habitualmente un caos de llamadas, correos y apuntes — en un proceso estructurado que termina con un resumen listo para el abogado en minutos.**

El abogado llega a la primera llamada sabiendo exactamente qué pasó, qué quiere el cliente, qué documentos tiene, quiénes son las partes y si hay conflicto de interés. Sin sorpresas, sin improvisación.

---

## 4. Problemas que resuelve

### Para el abogado

| Problema antes de Captio | Cómo lo resuelve Captio |
|---|---|
| La primera llamada se va en preguntas básicas que el cliente debería haber respondido por escrito | El cliente llena el formulario antes — el abogado llega informado |
| El resumen del caso se escribe a mano o se improvisa en una libreta | La IA genera un brief estructurado de 10 secciones en segundos |
| Los casos están dispersos en correos, WhatsApp, notas de papel y hojas de cálculo | Todos los casos en un panel, con historial, estado y notas centralizadas |
| La verificación de conflicto de interés es manual y ad hoc | Está integrada en el formulario y en cada brief generado |
| Es difícil delegar el primer contacto a un asistente sin que se pierda información | El enlace puede enviarlo cualquier miembro del equipo; el caso aparece automáticamente |
| Releer notas de audiencias o estrategia requiere buscar en varios archivos | Las notas de caso están vinculadas al expediente, organizadas jerárquicamente |

### Para el cliente

| Problema | Solución |
|---|---|
| Tiene que explicar su caso varias veces antes de que alguien lo atienda | Llena el formulario una sola vez, en su propio tiempo, desde cualquier dispositivo |
| No sabe qué información es relevante | El formulario guía con preguntas claras y contexto en cada campo |
| La primera interacción con un despacho se siente impersonal o caótica | Recibe un enlace limpio, profesional, con el nombre del despacho |

---

## 5. Features

### 5.1 Nuevo Cliente — Generación de enlace

**Qué es:** El abogado genera un enlace único para un cliente potencial con un solo clic.

**Cómo funciona:**
1. Desde la sección "Nuevo Cliente", el abogado escribe una referencia opcional (ej. "Toledo Bienes Raíces — contrato").
2. Captio genera un enlace único (`/i/[token]`).
3. El abogado copia el enlace y lo envía por correo, WhatsApp o cualquier canal.
4. El cliente abre el enlace — sin login, sin app que descargar.
5. Cuando el cliente envía el formulario, el caso aparece automáticamente en el panel del abogado.

**Panel de enlaces pendientes:** La sección también muestra todos los enlaces generados que aún no han recibido respuesta, con el nombre de referencia y opción de copiar el enlace nuevamente.

**Cómo aprovecharlo:**
- Enviar el enlace antes de la primera llamada — la llamada se convierte en estrategia, no en recolección de datos.
- Usar la referencia para identificar el caso fácilmente mientras espera respuesta.
- Delegar la generación del enlace a una recepcionista o asistente.

---

### 5.2 Formulario de ingreso del cliente

**Qué es:** Un formulario estructurado de 6 secciones que el cliente llena desde su dispositivo. Diseñado para capturar toda la información que un abogado necesita antes del primer contacto.

**Las 6 secciones:**

| # | Sección | Qué captura |
|---|---|---|
| 1 | **Información básica** | Nombre, ocupación, correo, teléfono, fecha de nacimiento, documento de identidad |
| 2 | **Resumen del caso** | Narrativa libre ("¿qué pasó?"), fechas clave, partes involucradas, acciones legales previas, abogado anterior, expectativas de presupuesto |
| 3 | **Objetivos y resultado** | Qué quiere lograr, qué sería un resultado realista, prioridad principal (rapidez / costo / mejor resultado), intentos previos de resolución, mayor preocupación |
| 4 | **Documentos** | Qué documentos tiene disponibles (checkboxes), testigos, notas sobre documentos, si ya envió algo a un abogado anterior |
| 5 | **Conflicto de interés** | Nombres de todas las partes, abogado de la contraparte, empresas relacionadas, relación previa con el despacho |
| 6 | **Algo más** | Campo libre para contexto adicional |

**Características del formulario:**
- Barra de progreso en tiempo real (0–100%).
- Todos los campos tienen texto de ayuda contextual.
- Validación de campos requeridos con scroll automático al primer error.
- Disponible en español e inglés (el cliente puede cambiar el idioma).
- El idioma del formulario se hereda del idioma del despacho al momento de generar el enlace.
- No requiere cuenta ni app.
- Funciona en móvil, tablet y desktop.

**Áreas de práctica disponibles:** Derecho familiar, Defensa penal, Inmigración, Negocios/contrato, Inmobiliario, Lesiones personales, Laboral, Sucesiones, Otro, No estoy seguro.

---

### 5.3 Historial de clientes

**Qué es:** El panel central donde viven todos los casos del despacho.

**Stats en tiempo real:**

| Stat | Descripción |
|---|---|
| **Total** | Todos los casos del despacho |
| **Aceptados (Engaged)** | Casos donde el cliente fue aceptado formalmente |
| **En revisión** | Casos en evaluación o revisión de conflicto |
| **Nuevos** | Casos que llegaron pero aún no se han revisado |

**Estados del caso:**

```
Invitado → Nuevo → En revisión ──→ Consulta agendada ──→ Aceptado ✓
                        └──→ Revisión de conflicto ──→ Rechazado
                                                   └──→ Cerrado
```

| Estado | Cuándo usarlo |
|---|---|
| **Invitado** | El enlace fue enviado, el cliente no ha respondido |
| **Nuevo** | El cliente envió el formulario, no se ha revisado |
| **En revisión** | El equipo está evaluando el caso |
| **Consulta agendada** | Ya hay una cita con el cliente |
| **Revisión de conflicto** | Se detectó un posible conflicto de interés |
| **Aceptado ✓** | El cliente fue admitido como cliente del despacho |
| **Rechazado** | El caso fue declinado |
| **Cerrado** | El caso concluyó |

**Búsqueda y filtros:** Búsqueda por nombre o tipo de caso. Filtro por cualquier estado.

**Cada tarjeta de caso muestra:** Número de caso, nombre, clasificación, estado (con color), preview de las respuestas o del brief, fecha de creación y número de eventos en la línea de tiempo.

---

### 5.4 Resumen de caso con IA (Brief)

**Qué es:** Al abrir un caso, el abogado puede generar un brief estructurado en segundos usando Claude (Anthropic) como motor de IA.

**Las 10 secciones del brief:**

| # | Sección | Contenido |
|---|---|---|
| 1 | **Encabezado** | Nombre del cliente, fecha, clasificación del caso (inferida por IA) |
| 2 | **Puntos clave** | 3–6 bullets con los hechos que el abogado necesita de un vistazo |
| 3 | **La versión del cliente** | Narrativa en prosa limpia, fiel a las palabras del cliente |
| 4 | **Resumen del caso** | Naturaleza del problema, fechas, partes, acciones previas, presupuesto |
| 5 | **Objetivos y resultado deseado** | Qué quiere el cliente, resultado realista, prioridad, intentos |
| 6 | **Información de apoyo** | Documentos, testigos, notas |
| 7 | **Verificación de conflicto de interés** | Todas las partes, abogado contrario, empresas relacionadas |
| 8 | **Riesgos clave y consideraciones** | Plazos urgentes, documentos firmados, puntos de riesgo |
| 9 | **Información pendiente** | Lo que el cliente no proporcionó y aún falta recopilar |
| 10 | **Consideraciones legales para el abogado** | Puntos de derecho relevantes para revisión interna (no son asesoramiento al cliente) |

**Características:**
- Los campos vacíos se marcan con `[FALTA: descripción]` en lugar de inventarse.
- Fiel a las respuestas — nunca inventa hechos, nombres, montos o fechas.
- Se genera en el mismo idioma en que se llenó el formulario (español o inglés).
- Soporta archivos de referencia del despacho como contexto adicional.
- El brief se guarda en el expediente y puede regenerarse en cualquier momento.

**Cómo aprovecharlo:**
- Leer el brief en 2 minutos antes de la primera llamada con el cliente.
- Compartir el brief con colegas del despacho para revisión.
- Usar los "Puntos clave" como agenda de la primera consulta.
- Revisar "Información pendiente" para saber qué preguntar en la llamada.
- Usar las "Consideraciones legales" como punto de partida para la investigación.

---

### 5.5 Editor de brief

**Qué es:** Herramientas de edición y anotación directamente sobre el brief generado.

**Herramientas disponibles:**

- **Edición inline:** Click en cualquier parte del brief para editar el texto directamente, sin salir de la app.
- **Resaltado en 5 colores:** Selecciona texto y resáltalo en amarillo, verde, azul, rojo o morado. Ideal para marcar puntos clave, zonas de riesgo o estrategia por discutir.
- **Borrar resaltado:** Selecciona texto resaltado y usa el borrador para quitarlo.
- **Guardar cambios:** Los cambios se guardan en Firestore y persisten en el expediente.
- **Descarga HTML:** Exporta el brief como archivo HTML autocontenido — se abre en cualquier navegador, se puede imprimir o enviar a un colega.

**Cómo aprovecharlo:**
- Amarillo para puntos que requieren seguimiento.
- Rojo para riesgos o inconsistencias en la narrativa.
- Verde para fortalezas del caso.
- Azul para información que debe verificarse.
- Descargar e imprimir para llevar al despacho o a una audiencia.

---

### 5.6 Línea de tiempo del caso

**Qué es:** Un historial cronológico por cliente que registra todos los eventos relevantes del caso.

**Cómo funciona:**
- Se crea automáticamente con el primer evento ("Enlace generado", "Formulario enviado", "Resumen generado con IA").
- El abogado puede agregar notas o eventos manualmente en cualquier momento (ej. "Consulta agendada para el martes", "Cliente envió documentos").
- Los cambios de estado también se registran automáticamente.

**Cómo aprovecharlo:**
- Como bitácora rápida de cada caso sin abrir otro sistema.
- Para delegar casos a colegas — llegan con todo el historial visible.
- Como registro de evidencia de seguimiento ante cualquier disputa sobre comunicación.

---

### 5.7 Notas de caso (Cuaderno)

**Qué es:** Un cuaderno de notas interno vinculado a casos específicos, con soporte para jerarquía de notas.

**Características:**
- Cada nota se vincula a un caso específico.
- Soporte para **notas padre e hijo**: una nota puede "pertenecer a" otra nota, creando una estructura jerárquica (ej. una nota "Estrategia general" como padre, con notas hijo "Estrategia audiencia inicial", "Estrategia para documental").
- Búsqueda de notas por texto dentro de un caso.
- Las notas se muestran con sus relaciones (notas de las que depende / notas que dependen de ella).

**Casos de uso:**
- Estrategia del caso: notas de alto nivel con sub-notas por etapa procesal.
- Pendientes por audiencia.
- Apuntes de reuniones con el cliente.
- Investigación jurídica vinculada al expediente.
- Ideas de argumentación antes de que estén listas para el brief.

---

### 5.8 Archivos de referencia

**Qué es:** Un repositorio de documentos del despacho que Claude usa como contexto al generar briefs.

**Qué se puede subir:**
- Tablas de honorarios y tarifas.
- Plantillas de brief del despacho.
- Política de conflicto de interés del despacho.
- Perfil del despacho (áreas de práctica, jurisdicciones, especialidades).
- Cualquier documento que deba informar el tono o contenido de los briefs.

**Cómo funciona:** Cuando el abogado genera un brief, los archivos de referencia activos se envían a Claude junto con las respuestas del cliente. La IA usa esos documentos para contextualizar el brief según la política y las tarifas del despacho — sin inventar información.

**Solicitud de archivos:** Los usuarios del despacho pueden enviar una solicitud describiendo el archivo que necesitan ("Lista de honorarios 2025", "Plantilla para casos familiares"). El administrador revisa y sube el archivo.

**Indicador de archivos activos:** La barra lateral muestra cuántos archivos de referencia están activos en todo momento.

---

### 5.9 Soporte multilingüe

**Qué es:** La plataforma completa funciona en español e inglés — tanto el dashboard del abogado como el formulario del cliente.

**Cómo funciona:**
- El despacho tiene un idioma por defecto (configurado por el administrador).
- El abogado puede cambiar el idioma del dashboard con un toggle ES/EN en cualquier momento.
- Al generar un enlace, el idioma del formulario se hereda del idioma actual del despacho.
- El cliente puede cambiar el idioma del formulario manualmente antes de enviarlo.
- El idioma en que se llenó el formulario determina el idioma del brief generado — si el formulario se llenó en inglés, el brief se genera en inglés con instrucciones y secciones en inglés.

**Por qué importa:** Despachos con clientes internacionales o que operan en mercados bilingües pueden atender ambas audiencias sin fricción.

---

## 6. Flujo completo de un caso

```
1. ABOGADO crea un enlace en "Nuevo Cliente"
         ↓
2. Envía el enlace al cliente por correo / WhatsApp / SMS
         ↓
3. CLIENTE abre el enlace (sin login), llena el formulario en 10–15 min
         ↓
4. El caso aparece en el panel del abogado con estado "Nuevo"
         ↓
5. ABOGADO hace click en el caso → ve las respuestas del cliente
         ↓
6. Click en "Generar resumen" → Claude genera el brief en segundos
         ↓
7. ABOGADO lee, edita, resalta y descarga el brief
         ↓
8. Primera llamada con el cliente — el abogado ya sabe todo
         ↓
9. El estado del caso se actualiza (En revisión → Consulta agendada → Aceptado)
         ↓
10. El ABOGADO agrega notas de caso y eventos en la línea de tiempo
```

---

## 7. Audiencia objetivo

### Perfil principal
- **Abogados independientes y despachos pequeños (1–15 personas)**
- Que reciben consultas nuevas con frecuencia.
- Que ya usan alguna forma de IA en su trabajo o están dispuestos a hacerlo.
- Que sienten que el primer contacto con clientes consume demasiado tiempo sin estructura.

### Roles dentro del despacho que usan Captio
| Rol | Cómo usa Captio |
|---|---|
| **Abogado titular / socio** | Revisa briefs, toma decisiones de admisión de casos |
| **Abogado asociado** | Genera enlaces, revisa casos, agrega notas |
| **Asistente / recepcionista** | Genera y envía enlaces, actualiza estados, agrega notas en la línea de tiempo |

### Práctica óptima
Captio es especialmente útil en:
- Derecho familiar
- Lesiones personales
- Negocios y contratos
- Derecho laboral
- Inmobiliario
- Defensa penal

---

## 8. Diferenciadores clave

1. **El formulario es para el cliente, no para el abogado** — El abogado no llena nada; el cliente lo hace desde su dispositivo, en su idioma, a su ritmo.

2. **El brief habla el lenguaje del abogado** — No es un resumen genérico; sigue la estructura de un expediente legal con secciones como conflicto de interés, riesgos clave y consideraciones legales internas.

3. **Fiel a las respuestas** — La IA nunca inventa. Si falta información, lo dice claramente con `[FALTA]`. El abogado siempre sabe qué tiene y qué le falta.

4. **No requiere cambiar de sistema** — Se integra al flujo de trabajo existente: el abogado sigue usando su CRM o agenda; Captio solo gestiona el intake y el brief inicial.

5. **Multilingüe nativo** — No es una traducción parcial; la experiencia completa — formulario, dashboard, brief — existe en español e inglés de forma paralela.

6. **Privacidad primero** — Los datos del cliente se almacenan en Firestore bajo el `firmId` del despacho. Ningún dato se comparte entre firmas.

---

## 9. Precio

1. **El precio es por firma** _ No pagues por cada abogado de tu firma, un solo pago para todos los miembros de tu firma.

2. **60 dolares mensuale** _ Uso ilimitado. 

## 10. Tono de marca

**Captio habla como un colega que entiende derecho.**

- Preciso sin ser frío.
- Profesional sin ser solemne.
- Directo — sin florituras, sin jerga de tech innecesaria.
- Respetuoso con el tiempo del abogado.

**Evitar:** palabras como "revolucionario", "disruptivo", "game changer". El abogado es escéptico de la hipérbole. Lo que funciona es mostrar, no prometer.

**Frases que funcionan:**
- "El cliente llena. El abogado llega listo."
- "Primera llamada sin sorpresas."
- "Intake estructurado. Brief en segundos."
- "Todo lo que necesitas saber antes de la primera llamada."
- "Del formulario al brief, sin trabajo manual."

---

## 11. Preguntas frecuentes anticipadas

**¿Mis datos son seguros?**
Sí. Los datos de cada despacho están aislados por `firmId`. Captio no comparte datos entre firmas ni los usa para entrenar modelos.

**¿El cliente necesita una cuenta?**
No. El cliente solo necesita el enlace. Sin registro, sin contraseña.

**¿En qué idioma se genera el brief?**
En el mismo idioma en que se llenó el formulario. Si el cliente llenó en inglés, el brief es en inglés.

**¿Puedo editar el brief después de generarlo?**
Sí. El editor inline permite modificar cualquier parte del texto y guardar los cambios.

**¿Funciona en móvil?**
El formulario del cliente está optimizado para móvil. El dashboard del abogado está diseñado para desktop y tablet.

**¿Qué pasa si el cliente no llena el formulario?**
El caso queda en estado "Invitado" con el enlace activo. El abogado puede copiar y reenviar el enlace en cualquier momento desde el panel de enlaces pendientes.
