# Sistema de vida — Infraestructura
> Estable · Cambia poco · Contiene: principios, arquitectura, reglas marco, criterios de decisión
> Idioma del archivo: español (infraestructura es independiente del idioma activo)

---

## Índice
- [1. Ejercicio — arquitectura y reglas](#1-ejercicio--arquitectura-y-reglas)
- [2. Nutrición — framework](#2-nutrición--framework)
- [3. Sueño — fundamentos](#3-sueño--fundamentos)
- [4. Energía circadiana — framework](#4-energía-circadiana--framework)
- [5. Estudio — sistema de 8 técnicas](#5-estudio--sistema-de-8-técnicas)
- [6. Idiomas — arquitectura del sistema](#6-idiomas--arquitectura-del-sistema)
- [7. PKM — arquitectura](#7-pkm--arquitectura)
- [8. Hábitos — estructura permanente](#8-hábitos--estructura-permanente)
- [9. Dashboard semanal — métricas y reglas de ajuste](#9-dashboard-semanal--métricas-y-reglas-de-ajuste)
- [10. Protocolo enfermedad / lesión](#10-protocolo-enfermedad--lesión)
- [11. Suplementos — criterios y stack lógico](#11-suplementos--criterios-y-stack-lógico)
- [12. Finanzas — estructura base](#12-finanzas--estructura-base)
- [13. Datos relevantes](#13-datos-relevantes)

---

## 1. Ejercicio — arquitectura y reglas

### Distribución semanal

| Día | Actividad | Duración |
|---|---|---|
| Lunes | Rutina fuerza completa | ~50 min |
| Martes | Zona 2 | 45–60 min |
| Miércoles | Rutina fuerza completa | ~50 min |
| Jueves | Zona 2 | 45–60 min |
| Viernes | Rutina fuerza completa | ~50 min |
| Sábado | Zona 2 (fijo si <150 min acumulados) | 30–60 min |
| Domingo | Descanso real | — |

Micro-cardio adicional: 10–15 min caminata rápida post-comida en días de fuerza cuando sea posible.

---

### Rutina fuerza ~50 min

**CALENTAMIENTO — 5 min (sin descanso)**
- Jumping jacks: 30 seg
- Arm circles: 30 seg
- Hip circles: 30 seg
- Leg swings: 30 seg c/lado
- Inchworm: 5 reps

**PRE-SUPERSET A — prehab hombro (30–60 seg)**
- Scapular push-ups: 10–15 reps
- Band external rotations: 15–20 reps c/lado (si tienes banda)

**BLOQUE TIER 1 — 3 rondas en supersets**
- **Superset A:** Pull-up 6–8 ↔ Dip 8–10 — descanso 90 seg al terminar ronda
- **Superset B:** Bulgarian split squat 10–12 c/pierna ↔ RDL con mochila 8–12 — descanso 60 seg
- **Solo C:** Push-up 12–15 — 3 sets, 60 seg

**BLOQUE TIER 2 — Circuito 2 rondas (descanso corto entre ejercicios)**
- Pike push-up 8–10
- Australian row 10–12
- Band pull-aparts 15–25
- Glute bridge 15
- Calf raises 15–20

**CORE FINISHER — 5 min**
- Hollow body hold: 3 × 20 seg (30 seg descanso)
- Plank: 2 × 30 seg (30 seg descanso)
- Side plank: 2 × 30 seg c/lado (30 seg descanso)

**MOVILIDAD ACTIVA — 5 min**
- Deep squat hold: 3 × 30 seg
- Shoulder CARs: 5 reps c/lado
- Hip openers dinámicos: 30 seg c/lado
- Isquiotibiales activos: 30 seg c/lado

---

### Reglas de progresión y seguridad

**REGLA DE PROGRESIÓN**
Tope alto del rango en todos los sets → aumenta dificultad siguiente sesión. RIR: mayoría de sets a RIR 1–2. Último set de 1–2 ejercicios: RIR 0–1 si te sientes bien.

Progresiones:
- Push-up → declinadas
- Pull-up → lastre o tempo lento (3 seg bajada)
- Bulgarian → añade peso o eleva pie trasero
- RDL → aumenta peso en mochila

**REGLA ANTI-ESTANCAMIENTO**
Si 2 semanas seguidas el indicador no sube Y el sueño está bien → cambia 1 variable por 2 semanas:
- +2.5–5% carga en mochila (RDL/Bulgarian), o
- +1 rep por set hasta tope, o
- tempo 3s bajada solo en el primer set (pull-up/push-up)

**REGLA DE SEGURIDAD — DIPS**
Sin dolor y con rango controlado. Señal roja: si dolor anterior de hombro aparece durante dips o dura >24–48h → reemplaza dips por 2 semanas completas por: push-up declinado/close-grip, rango reducido, o agarre neutro (anillas).

**SEÑAL DE FATIGA SISTÉMICA**
Si 2–3 días seguidos: sueño "malo" + rendimiento percibido ≤5/10 → esa semana:
- Tier 2 baja a 1 ronda
- Tier 1 todo a RIR 2
- No forzar PRs

---

### Modo contingencia

**DÍA APRETADO (50 → 35 min) — jerarquía de recorte:**
1. Warm-up + prehab hombro — no negociable
2. Tier 1 completo — no negociable
3. Core: solo hollow + side plank (1–2 sets)
4. Tier 2: bajar a 1 ronda
5. Movilidad: recortable

**VERSIÓN MÍNIMA (12–15 min) — viajes / días caóticos**
2–3 rondas sin llegar al fallo:
- Pull-up o Australian row: 5–8
- Push-up: 8–15
- Bulgarian split squat: 8–12 c/pierna
- 1 set: Side plank 30 seg c/lado

*Regla: si no puedo hacer el plan completo → hago la mínima.*

---

### Zona 2 — criterios de intensidad

- Talk test: puedes hablar en frases completas pero no cantar
- RPE 4–5/10. FC aprox. 60–70% del máximo
- Intensidad estable durante toda la sesión
- Hidratación días largos (45–60 min): agua + pizca de sal yodada o electrolitos si sudas bastante

**REGLA DE GARANTÍA — 150 min/sem**
Mínimo: Mar 45 + Jue 45 + Sáb 30 = 120. Completar con micro-cardio 10 min en 3 días de fuerza = 150 ✅
Si al llegar el sábado el total acumulado es <150 min → sábado es 45–60 min fijo, no opcional.

> **CRITERIO MICRO-CARDIO COMPUTABLE**
> Solo cuenta hacia los 150 min si: talk test positivo (puedes hablar en frases pero no cantar) O RPE ≥4/10. Una caminata lenta sin ese umbral no computa. Duda → no contar.

---

## 2. Nutrición — framework

> **DATO BASE REQUERIDO (en archivo operativo)**
> Meta proteína: 1.8g × peso corporal (kg) = ___g/día. Actualizar si el peso cambia ≥3kg sostenido.

Distribuir ~20–40g proteína por comida.
Sal yodada en casa — solución automática para yodo.
Fibra: subir gradual (1/4 taza menestras → 1/2 taza) + agua para evitar malestar inicial.

### Estructura de comidas (base)

**DESAYUNO**
- 2 huevos
- 100g brócoli
- 1 cda maca
- 1 scoop proteína
- 5g creatina (cualquier hora — consistencia > timing)
- 100g fresas
- 1 cda aceite de oliva
- 1 cda chía o linaza (~5–6g fibra)

**ALMUERZO**
- 150–180g proteína animal — 1 día/cada 2 semanas: hígado de res 85–100g *(ver nota vitamina A)*
- Días de pescado: sardina o caballa > pollo. Meta: 2 porciones/sem
- 100g col morada
- 100g camote
- 1/2 taza menestras (lentejas/garbanzos/frijoles)
- 10–15g nueces o semillas de calabaza
- 1 fuente de calcio: yogur / queso / sardinas con espina / leche o alternativa fortificada
- Vitamina D3 2,000 IU *(ajustar con analítica 25-OH-D; UL adultos 4,000 IU/día)*

> **NOTA VITAMINA A — HÍGADO**
> Hígado de res cocido aporta ~8,000–9,500 µg RAE por 100g. UL vitamina A preformada: 3,000 µg RE/día (EFSA). La vitamina A es liposoluble y se acumula. Opciones (elegir 1):
> - **Opción A (recomendada):** hígado 1× cada 2 semanas, 85–100g
> - **Opción B:** hígado 1×/sem pero 30–50g
> - **Opción C:** hígado 85–100g/sem → eliminar toda otra fuente concentrada de vitamina A preformada
> - **Hard stop:** evitar en embarazo o posibilidad de embarazo.

**CENA**
- 100g espinaca
- 2 huevos
- 100g camote
- 1 cda aceite de oliva
- Magnesio glicinato 300mg *(UL suplementos ~350mg — bajar si hay malestar GI)*

**ADICIONES**
- Betarraga: pre-entreno 2–3h antes. No usar enjuague bucal antiséptico cerca del consumo.
- Zanahoria noche
- Jengibre 3–5g + 1 limón + 2 ajo post-entreno *(interacción con anticoagulantes — ajustar si aplica)*

### Regla de ajuste calórico (sin contar macros)

Usa tendencia semanal (peso o cintura + rendimiento):
- Cintura/peso baja demasiado y rendimiento cae → **+1 porción carbohidrato** en almuerzo o cena
- Cintura sube sostenido y no es tu objetivo → **−1 porción carbohidrato** (camote a ~70g o menestras a 1/4 taza)

---

## 3. Sueño — fundamentos

### Duración y consistencia
- 7–9h, horario fijo
- Magnesio glicinato 300mg con cena — ya integrado en nutrición

### Ambiente — 3 variables que más mueven aguja

| Variable | Objetivo | Solución mínima |
|---|---|---|
| Temperatura | 18–20°C | Ventilador + ropa ligera + descubrir pies si no hay AC |
| Oscuridad | Blackout total | Antifaz o cortinas opacas |
| Ruido | Estable | Tapones o ruido blanco/marrón si entorno variable |

### Protocolo pre-sueño (60–90 min antes)
- Reducir luz azul: bajar brillo al máximo + modo cálido. Óptimo: gafas bloqueadoras o luz naranja/vela
- Evitar contenido de alta activación cognitiva: series de acción, redes sociales → arousal tarda 20–40 min en bajar
- Ducha tibia (no fría) 60–90 min antes → acelera descenso de temperatura core

**ANCLA CIRCADIANA PRINCIPAL**
Hora fija de despertar 7 días/sem + luz natural en los primeros 30 min post-despertar. Sin exposición temprana a luz natural, la hora fija pierde parte de su efecto.

**ANCLA CIRCADIANA SECUNDARIA**
Evitar luz intensa (especialmente azul) en las 2h previas al sueño.

### Métricas
- Dashboard: calidad subjetiva 1–10 junto a horas
- Wearable (opcional): Oura o Garmin — útil para tendencias, no diagnóstico clínico

---

## 4. Energía circadiana — framework

### Determinar cronotipo

| Hora despertar natural (sin alarma) | Cronotipo | Pico cognitivo aprox. |
|---|---|---|
| Antes de 7am | Alondra | 7–10am |
| 7–9am | Intermedio | 9am–1pm |
| Después de 9am | Búho | 11am–3pm |

### Estructura de día (base: cronotipo intermedio)

| Franja | Actividad |
|---|---|
| Despertar + 30 min | Luz natural, no pantallas, desayuno |
| + 1–4h post-despertar | Bloque mental principal (estudio, idioma activo output) |
| Post-almuerzo | Zona 2 o tareas mecánicas (inbox, admin) |
| 16–18h | Fuerza o segundo bloque mental |
| 2h pre-sueño | Sin trabajo exigente, reducir estimulación |

**REGLA FUERZA TARDÍA**
El ejercicio de fuerza eleva temperatura core y cortisol ~2–4h. Si entrenas después de 19–20h y duermes mal → mover fuerza a mañana o mediodía.

### Cafeína (opcional — solo si la usas)
- Solo antes del bloque mental principal
- Corte: mínimo 8–10h antes de dormir
- Dosis de referencia: hasta ~400mg/día (FDA); efecto útil con 100–200mg
- **Stop rule:** si calidad de sueño baja ≥1 punto sostenido → reducir dosis o adelantar corte antes de cualquier otro ajuste

---

## 5. Estudio — sistema de 8 técnicas

1. **Retrieval Practice:** al cerrar sesión → 5 min escribir de memoria + 3–5 preguntas tipo examen auto-creadas + corrección el mismo día. Trigger obligatorio.
2. **Spaced Repetition adaptativo:** fácil → duplicar intervalo; con esfuerzo → mantener; falla → acortar + generar 1 ejemplo propio. Base: día siguiente → semana → 15d → 30d.
3. **Interleaving:** 70% bloque + 30% interleaving. Se siente peor — mejora discriminación y retención; el efecto varía según material.
4. **Elaborative Interrogation:** "¿Por qué esto es así?" y "¿Cómo conecta con lo que ya sé?"
5. **Concrete Examples (self-generated):** propios ejemplos > los del libro.
6. **Dual Coding:** texto + diagrama propio. No copiado.
7. **Espaciado interno en sesión:** bloques 10–15 min → pausa → 10–15 min. Separar revisiones mañana/tarde si posible.
8. **Simulacro mensual:** 20–30 min sin apuntes, tipo examen acumulativo. Métrica real de terreno.

---

## 6. Idiomas — arquitectura del sistema

> El sistema siempre tiene 1 idioma **activo** (adquisición) y puede tener 1 idioma en **mantenimiento** (consolidación). El idioma activo y el plan específico van en el archivo operativo.

### Framework de adquisición (aplica a cualquier idioma activo)

**Input — 30 min/día (jerarquía)**
- Prioridad 1: audio/video con transcript. Nivel i+1: entiendes 70–80%, 20% restante es el reto
- Prioridad 2: textos técnicos en tu dominio

**Output — 30 min/día (rotación 3 días)**

| Sesión | Actividad | Detalle |
|---|---|---|
| Sesión A | Escritura + corrección | Escritura libre 15 min → feedback IA → 15 min implementar |
| Sesión B | Shadowing + speaking | Shadowing 15 min + grabar 2–3 min en tema técnico → escuchar → 1 error |
| Sesión C | Retrieval en L2 + micro-corrección | Explicar 1 concepto técnico sin notas, 20 min → 5 min micro-corrección IA → registrar en PKM |

> **CORRECCIÓN SESIÓN C**
> El retrieval sin corrección solidifica errores. 5 min de micro-corrección son el mínimo para cerrar el loop. Doble función: producción L2 + detección de fosilización temprana.

**Speaking — protocolo mínimo anti-bloqueo**
2–3 min grabación de voz, 3×/sem (dentro del bloque output). No requieres interlocutor para empezar. Objetivo inicial: reducir latencia de producción, no perfección.

**Métricas (estructura)**
- Cada 60 días: mock test estándar del idioma (mide las 4 skills por separado)
- Skill más baja → +10 min esa semana
- Apps de vocabulario gamificadas: herramienta auxiliar, **no** indicador de progreso real

---

## 7. PKM — arquitectura

*Principio: un PKM que no se usa en <30 segundos de captura no se sostiene. Complejidad mata adherencia.*

### 3 capas

| Capa | Frecuencia | Acción | Integración |
|---|---|---|---|
| 1 — Captura | Continua | Bandeja única, sin procesar | Últimos 2 min de reflexión diaria |
| 2 — Procesamiento | 1×/sem (sábado) | Inbox → accionable / referencia / insight a desarrollar | Primeros 5 min de escritura del sábado |
| 3 — Conexión | 1×/mes | Revisar insights, buscar 1–2 conexiones entre dominios distintos | Últimos 10 min del simulacro mensual |

### Criterio de herramienta
- **Fase 1:** notas nativas del teléfono — 3 carpetas: Inbox / Referencia / Insights. Setup: 2 min.
- **Fase 2:** Notion u Obsidian — solo si adherencia ≥8 semanas Y el volumen o la búsqueda lo justifican. No antes.

---

## 8. Hábitos — estructura permanente

### Diario
- Sueño: 7–9h, horario fijo
- Ejercicio: según distribución semanal
- Vacío mental: 10–15 min sin estímulo — integrable en caminata outdoor
- Bloque mental: 1h según rotación
- Alimentación: verduras + proteína + carbohidratos complejos + fibra. Sin procesados como base
- Reflexión: 15 min — qué pasó / qué agradezco / qué ajusto + últimos 2 min captura PKM

### Reglas del bloque mental
- **1 tarea por bloque** (MIT): definirla antes de abrir cualquier herramienta
- **Teléfono fuera del alcance visual** — fuera de la habitación o cara abajo en otro cuarto
- **Notificaciones: solo urgentes** — modo avión o DND activo durante el bloque
- **Cierre estructurado (2–3 min):** anotar "¿qué sigue?" para reducir fricción al retomar

> **TRIGGER DE FATIGA COGNITIVA (señal temprana)**
> Rendimiento percibido ≤5/10 **Y** calidad percibida del bloque ≤4/10 por **2 días seguidos** → reducir bloque de 60 a 30 min y priorizar retrieval/repaso sobre input nuevo. No eliminar — reducir carga. Restaurar a 60 min cuando rendimiento vuelva a ≥6 durante 2 días consecutivos.

### Ducha fría
3×/sem, 2–3 min. Timing: mañana al despertar o días cardio/descanso. No inmediatamente post-entrenamiento de fuerza.

### Rotación semanal de bloques mentales

| Día | Actividad | Métrica |
|---|---|---|
| Lun / Mié / Vie | Idioma activo — 30min input + 30min output rotativo | Mock test c/60 días |
| Mar / Jue | Proyecto principal (certificación, máster, u otro definido en operativo) | Según objetivo del ciclo |
| Sábado | Escritura — síntesis semanal + procesamiento PKM | — |
| Domingo | Libre o skill monetizable | — |

### Semanal
- **Ayuno 18h — Domingo:** última comida sábado ~7pm, romper domingo ~1pm. Día sin zona 2 ni bloque cognitivo obligatorio. Si el domingo se activa evento social → reducir a 14–16h ese día o mover al lunes.
- **Conexión social:** 1h calidad + 1 micro-conexión (10–15 min). Métrica: ¿saliste diferente de como entraste?
- **Dashboard del sistema (5 min)**

### Mensual
- Revisión financiera: 30 min — gastos vs. ahorro vs. inversión
- Auditoría de pantalla: ¿tecnología apoya o sabotea el sistema?
- Simulacro de estudio acumulativo: 20–30 min sin apuntes + últimos 10 min revisión conexiones PKM

### Trimestral
- Revisión de dirección: 1h — ¿hacia dónde voy?, ¿qué cambió?, ¿qué elimino?
- Stop doing list: ¿qué hábito, persona o actividad quita energía sin retorno?
- Revisión de relaciones: ¿quién suma, quién resta? Meta: 1 persona nueva de valor por trimestre
- Ciclo de descarga: 1 semana al 50–60% cada 6–8 semanas

### Anual
- Chequeo médico: análisis de sangre completo + 25-OH-D + perfil lipídico
- Auditoría de entorno: casa, trabajo, teléfono — ¿facilita o dificulta los hábitos?

---

## 9. Dashboard semanal — métricas y reglas de ajuste

### 8 métricas

| # | Área | Métrica | Objetivo |
|---|---|---|---|
| 1 | Físico | Zona 2 min/semana (solo min con RPE ≥4) | 150+ min |
| 2 | Físico | Pull-ups totales en 3 sets (u otro indicador elegido) | Tendencia al alza |
| 3 | Físico | Dolor articular 0–10 | ≤3 sostenido |
| 4 | Energía | Sueño promedio (horas + consistencia) | 7–9h |
| 5 | Energía | Calidad de sueño 1–10 | ≥7 |
| 6 | Cuerpo | Peso o cintura (solo tendencia semanal) | Estable |
| 7 | Adherencia | % bloques clave cumplidos: fuerza 3×, cardio 3×, sueño, estudio | ≥80% |
| 8 | Cognitivo | # bloques mentales completados/sem | 5–7 |

### Reglas de ajuste
- 2 semanas: baja rendimiento + sube dolor → reducir Tier 2 a 1 ronda
- 2–3 semanas sin progreso + sueño bien → aplicar regla anti-estancamiento
- Adherencia <80% dos semanas seguidas → identificar el bloque que falla y ajustar, no eliminar
- Señal de fatiga 2–3 días seguidos → Tier 2 a 1 ronda + RIR 2 esa semana
- Métrica cognitiva <5 bloques/sem por 2 semanas → revisar reglas del bloque mental

---

## 10. Protocolo enfermedad / lesión

### Enfermedad

**REGLA CUELLO ARRIBA / ABAJO**
- Síntomas **sobre** el cuello: versión mínima de fuerza o caminata suave. Sin zona 2 intensa.
- Síntomas **bajo** el cuello (fiebre, dolor muscular generalizado, GI, pecho): pausa total hasta 24–48h después de que desaparezcan síntomas.
- **Fiebre: pausa absoluta.** Entrenar con fiebre eleva riesgo cardíaco real.

**Reentrada post-enfermedad**

| Días de pausa | Protocolo |
|---|---|
| ≤3 días | Retomar al 70% de volumen — semana de transición |
| 4–7 días | Semana completa al 60–70%, sin buscar PRs |
| >7 días | 2 semanas de reintroducción progresiva. Tier 1 completo pero RIR 2–3 todo |

**Nutrición en enfermedad**
- Mantener proteína aunque baje el apetito (prioridad 1)
- Hidratación +500ml sobre lo habitual
- Creatina: continuar (sin contraindicación)

---

### Lesión

**PEACE & LOVE (reemplaza RICE)**
- Primeras 48h: Protección + Elevación + Evitar antiinflamatorios + Compresión + Educación
- Después: Carga progresiva + Optimismo + Vascularización + Ejercicio

**Árbol de decisión**

| Señal | Acción |
|---|---|
| Dolor en movimiento pasivo | Médico antes de continuar |
| Dolor solo en carga | Modificar ejercicio, no pausar todo |
| Dolor >6/10 durante ejercicio | Parar ese ejercicio, continuar el resto |
| Dolor desaparece al calentar y no vuelve | Entrenable con monitoreo |

**Trabajo alrededor**
- Lesión tren inferior → mantener tren superior + zona 2 en bicicleta/natación
- Lesión hombro → mantener tren inferior + core
- Lesión muñeca/codo → Bulgarian, RDL, zona 2 sin impacto en zona afectada

---

## 11. Suplementos — criterios y stack lógico

### Stack base

| Suplemento | Dosis | Timing | Nota |
|---|---|---|---|
| Creatina | 5g | Cualquier hora | Consistencia > timing |
| Proteína whey | 1 scoop | Desayuno | Completar meta 1.8g/kg |
| Vitamina D3 | 2,000 IU | Almuerzo | **Requiere baseline 25-OH-D.** UL: 4,000 IU/día. Si ≥40 ng/ml: suspender y reevaluar. Si <30: mantener o subir según indicación. |
| Magnesio glicinato | 300mg | Cena | UL ~350mg desde suplementos. Bajar si malestar GI |

> **VITAMINA D3 SIN BASELINE**
> Lima (~12°S) tiene alta irradiación UV año redondo. Es posible que los niveles ya sean suficientes. Incluir 25-OH-D en el próximo análisis — no esperar al chequeo anual si ya pasaron >6 meses sin medición.

### Stack condicional

| Suplemento | Cuándo añadir | Dosis | Nota |
|---|---|---|---|
| Omega-3 (EPA+DHA) | Si sardina/caballa <2×/sem | 1–2g EPA+DHA | Con almuerzo (con grasa). Forma triglicérido > etil éster. Certificación IFOS. |
| Zinc | Solo si analítica confirma déficit | 15–25mg bisglicinato | Con comida, no ayunas. No junto a magnesio alta dosis. No exceder 25mg/d. Si uso >8–12 semanas: vigilar cobre/hemograma. |
| Ashwagandha KSH-66 | Último recurso — preferible evitar (ver nota) | 300–600mg extracto | Con cena. Ciclar: 8–12 sem on / 4 off. Contraindicado en Hashimoto, embarazo, lactancia, enfermedad hepática. Stop rules: somnolencia inusual, malestar GI persistente, ictericia u orina oscura → suspender y consultar médico inmediatamente. |

> **UMBRAL DE INICIO ASHWAGANDHA**
> Ambas condiciones simultáneas: rendimiento percibido promedio ≤5/10 durante ≥2 semanas **+** calidad de sueño ≥6. Si el sueño también está mal → resolver sueño primero. No iniciar sin consulta médica dado el perfil de riesgo hepático documentado (BfR Alemania).

**NO suplementar sin analítica:** hierro, B12, yodo (cubiertos por dieta base).

---

## 12. Finanzas — estructura base

- Cuenta separada de ahorro: transferencia automática el día de cobro
- Fondo de emergencia: 3–6 meses de gastos básicos
- Inversión pasiva indexada: sin timing, sin apuestas activas
- Broker: Interactive Brokers (IBKR) — sin mínimo de cuenta, comisiones bajas. Disponible en Perú.
- Vehículo: VT (Vanguard Total World) — ~10,000 posiciones, 50+ países, expense ratio 0.06%, un solo ticker
  - Si residencia fiscal es UE/EEE: usar equivalente UCITS con KID (regulación PRIIPs). Ejemplo: VWCE (acumulación) o VWRL (distribución) de Vanguard FTSE All-World UCITS.
- Estrategia: DCA mensual fijo sin mirar precio — consistencia > timing
- Retiro sostenible: 3% anual como base con guardrails

**NOTA FISCAL — estate tax**
No residentes / no ciudadanos USA: IRS requiere Form 706-NA si activos en EE.UU. superan USD 60,000 al fallecimiento. No cambia la estrategia; obliga a elegir bien el domicilio del ETF y/o planificar.

---

## 13. Datos relevantes

**Toma de decisiones en L2**
Tomar decisiones en segunda lengua puede reducir influencia emocional en dilemas de alta carga afectiva. Efecto real pero variable por dominio y nivel de L2 — herramienta, no ley universal.

**Protocolo de estrés / activación emocional alta**
Si activación emocional alta → esperar 20 min y escribir:
1. ¿Qué pasó?
2. ¿Qué siento?
3. ¿Qué necesito?
4. ¿Qué acción mínima haría bien?
5. ¿Qué empeoraría todo?

Convierte el delay en regulación, no en evitación.
