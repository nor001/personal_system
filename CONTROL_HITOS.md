# Control de hitos del sistema
> Registro maestro de consolidaciones · Sirve como ancla para futuras actualizaciones
> Regla maestra: siempre existe una **última versión válida** del sistema. Todo lo demás son exploraciones, observaciones o cambios pendientes.

---

## 1. Cómo usar este archivo

### Regla de actualización
Cuando se quiera actualizar algún documento, la instrucción base será:

> **Tomar como base la última versión válida y aplicar solo los cambios aprobados desde el último hito consolidado.**

### Tipos de actualización permitidos
- **Actualizar solo operativo** → cambia `SISTEMA_OPERATIVO.md`
- **Actualizar solo infraestructura** → cambia `SISTEMA_INFRAESTRUCTURA.md`
- **Consolidar sistema completo** → cambia ambos documentos
- **Registrar nuevo hito** → actualiza este archivo y, si corresponde, los otros dos

### Fórmulas recomendadas para pedir cambios
- **Actualiza el operativo desde Hito 0.1 con estos cambios aprobados...**
- **Actualiza infraestructura desde Hito 0.1 solo si afecta principios o reglas permanentes...**
- **Consolida Hito 0.2 usando como base Hito 0.1 y excluyendo cambios exploratorios...**
- **Sincroniza maestro solo con decisiones cerradas desde Hito 0.1...**

### Regla de seguridad
Si una idea fue discutida pero **no** fue aprobada explícitamente para entrar al sistema, se considera **exploratoria** y **no** entra al maestro.

---

## 2. Estructura documental del sistema

| Documento | Función | Frecuencia de cambio | Estado actual |
|---|---|---|---|
| `SISTEMA_INFRAESTRUCTURA.md` | Principios, arquitectura, reglas estables, criterios de decisión | Baja | Vigente |
| `SISTEMA_OPERATIVO.md` | Ciclo actual, horario, proyectos activos, métricas y estado real | Media/Alta | Vigente |
| `CONTROL_HITOS.md` | Ancla de versiones, resumen de consolidaciones y protocolo de actualización | Baja/Media | **Nuevo — vigente** |

### Regla de separación
- **Infraestructura** cambia solo si cambia la arquitectura del sistema.
- **Operativo** cambia cuando cambian datos, foco, métricas, prioridades o ejecución.
- **Control de hitos** cambia cuando se consolida una nueva versión válida.

---

## 3. Hito 0.1 — baseline consolidado vigente

**Estado:** vigente  
**Fecha de consolidación:** 2026-03-27  
**Base documental:**
- `SISTEMA_INFRAESTRUCTURA.md`
- `SISTEMA_OPERATIVO.md`

### Propósito del Hito 0.1
Fijar una primera versión operativa real del sistema, ya separada en infraestructura y operativo, con horario, prioridades del ciclo, proyecto principal, idioma activo, finanzas básicas y estructura semanal coherente con la vida actual.

### Alcance consolidado en Hito 0.1
- separación **infraestructura / operativo** validada
- prioridad central: **preparación para la vejez**
- reserva cognitiva como lógica del sistema
- proyecto principal del ciclo definido
- inglés tratado como **infraestructura activa**, no como proyecto competidor
- máster tratado como **proyecto secundario en mantenimiento**
- sábado definido como **Shabat / descanso real**
- domingo definido para **zona 2 + dashboard + máster**
- horario diario consolidado con despertar 05:30 y bloque profundo desde 06:00
- proteína diaria ya anclada con peso real
- finanzas instanciadas a nivel mínimo
- suplementos base acotados a lo ya decidido

### Estado resumido del Hito 0.1
| Área | Estado |
|---|---|
| Arquitectura general | Estable |
| Operativo actual | Activo |
| Proyecto principal | Definido |
| Idioma activo | Definido |
| Máster | En mantenimiento |
| Finanzas | Instanciadas en nivel básico |
| PKM | Activo simple |
| Cronotipo | Pendiente de validación en uso real |
| Inglés baseline | Pendiente de mock inicial |

---

## 4. Contenido aprobado dentro del Hito 0.1

### 4.1 Datos base aprobados
- Edad: **39 años**
- Estatura: **167 cm**
- Peso: **62 kg**
- Meta proteína: **112 g/día**
- Grado académico relevante: **Bachiller en Informática y Sistemas (2009), Universidad Nacional Agraria de la Selva**

### 4.2 Prioridades aprobadas del ciclo
1. **Proyecto principal:** ABAP Cloud / RAP / clean core / SAP BTP ABAP environment con capa de IA aplicada a SAP
2. **Idioma activo estructural:** inglés
3. **Proyecto secundario:** máster en Alemania — universidad pública — objetivo octubre 2027
4. **Backlog:** IA horizontal fuera de SAP (parqueado)

### 4.3 Reglas aprobadas de fin de semana
- **Sábado:** Shabat, recuperación, descanso real, sin ejercicio estructurado
- **Domingo:** zona 2, dashboard y bloque del máster
- **Ayuno:** opcional y flexible; no obligatorio si compite con energía, recuperación o bloque del domingo

### 4.4 Stack base aprobado del ciclo
- Creatina
- Proteína whey
- Magnesio glicinato
- Omega-3 solo si no se cubre pescado

**No aprobado dentro del Hito 0.1:**
- K2
- D3 alta dosis
- Ashwagandha como compra o prioridad operativa

---

## 5. Observaciones externas recibidas y estado dentro del Hito 0.1

### 5.1 Observaciones aceptadas
| Observación | Estado en Hito 0.1 | Acción |
|---|---|---|
| Separación infra/operativo correcta | Aceptada | Ya consolidada |
| Proyecto principal debe estar claramente jerarquizado | Aceptada | Ya consolidada |
| Riesgo de rigidez horaria matutina | Aceptada con validación | Se valida en 2 semanas de uso real |
| PKM simple y escalable | Aceptada | Ya consolidada |
| Métricas ligadas a objetivos del ciclo | Aceptada | Ya consolidada |
| Máster debe mantenerse como carril secundario | Aceptada | Ya consolidada |

### 5.2 Observaciones aceptadas con ajuste
| Observación | Ajuste aplicado |
|---|---|
| Protocolo de fatiga cognitiva era insuficiente | Se amplió: si se activa, la consolidación nocturna baja a 10 min máximo |
| Finanzas deben reflejar estado real y no solo filosofía | Se instanció ahorro, fondo, inversión y prioridad del ciclo |
| Inglés necesita baseline real | Se añadió mock baseline en el operativo |

### 5.3 Observaciones descartadas o desactualizadas
| Observación | Motivo |
|---|---|
| Tomar D3 diariamente como parte del stack base | No aprobada en el sistema actual |
| Comprar ashwagandha como prioridad alta | Contradice criterio del sistema: último recurso y no prioridad operativa |
| Abrir ya vehículo UCITS / inversión | No aplica al foco del ciclo mientras la prioridad financiera sea liquidez + máster |

---

## 6. Pendientes formales para futuro Hito 0.2

Estos puntos **no impiden operar Hito 0.1**, pero son candidatos naturales para la siguiente consolidación.

### Pendientes de validación
- [ ] Validar cronotipo real con 2 semanas de uso del horario 05:30–20:00
- [ ] Ejecutar mock baseline de inglés y registrar resultados por skill
- [ ] Definir 3 hitos concretos del ciclo para el proyecto principal
- [ ] Refinar shortlist del máster (mantener / descartar universidades)
- [ ] Fijar primera revisión financiera mensual efectiva

### Pendientes opcionales
- [ ] Añadir número de versión visible al inicio de los otros dos documentos
- [ ] Crear changelog corto dentro del operativo
- [ ] Convertir el proyecto principal en roadmap trimestral más granular

---

## 7. Criterio para declarar un nuevo hito

Un nuevo hito se declara solo si ocurre una de estas condiciones:
1. cambia la jerarquía del ciclo
2. cambia el proyecto principal
3. cambia el horario base
4. cambia una regla permanente de infraestructura
5. se consolidan varios cambios aprobados que ya alteran el estado operativo real

Si solo cambian métricas semanales, resultados o pequeños datos, **no** se crea un hito nuevo; solo se actualiza el operativo.

---

## 8. Plantilla para futuros hitos

### Hito X.X — nombre breve
- **Fecha:**
- **Estado:** vigente / reemplazado / archivado
- **Base:** Hito previo
- **Documentos afectados:** infraestructura / operativo / ambos
- **Cambios aprobados:**
- **Cambios excluidos:**
- **Razón del hito:**
- **Pendientes que pasan al siguiente hito:**

---

## 9. Instrucción operativa estándar

Cuando se quiera modificar el sistema, usar esta fórmula:

> **Actualiza [operativo / infraestructura / ambos] tomando como base Hito 0.1 y aplicando solo los cambios aprobados desde entonces. No incluyas ideas exploratorias.**

Esa será la convención estándar a partir de ahora.

