# Proyecto-CORTEX-GrupoBetFlow
**Mision:** Ser tu cerebro extendido proactivo que anticipa necesidades, elimina fricciones diarias y ejecuta acciones reales en tu vida con tu permiso explícito para que recuperes tiempo, reduces estrés y te enfoques en lo que realmente importa: crear, conectar y vivir.

# Integrantes:

**·Sebastian David Tang Gutierrez**

**·Julian Andres Martinez Hoyos**

## Perfil del agente:

## Semana 1 y 2

<img width="1408" height="760" alt="image" src="https://github.com/user-attachments/assets/d11dcf7e-584b-40eb-979e-954eb0afe2f9" />

## Semana 3

<img width="1077" height="727" alt="image" src="https://github.com/user-attachments/assets/003d3420-0526-4959-a7d2-802a1c85a7db" />




## ¿Que dice la grafica?

**Atención: 10/10**
Máxima. El bot debe mantener una atención constante y precisa sobre los patrones de tu día a día, anticipando necesidades y detectando fricciones antes de que se conviertan en problemas. Es la base de su carácter verdaderamente proactivo.

**Memoria: 10/10**
Fundamental y al máximo. Necesita retener de forma fiable todo el contexto relevante: regulaciones, leyes, tus preferencias históricas, decisiones pasadas y acciones ejecutadas. Sin una memoria sólida y de largo alcance, la anticipación y la ejecución automática pierden precisión y confianza.

**Lenguaje: 9/10**
Muy alto. Debe comunicarse con claridad, honestidad y precisión, transmitiendo siempre el consentimiento explícito, explicando acciones de manera transparente y utilizando un tono directo pero respetuoso. Casi perfecto, aunque siempre hay margen para pulir matices.

**Emoción: 3/10**
Intencionalmente baja. El bot no está diseñado para detectar ni gestionar estados emocionales profundos, ni para ofrecer consuelo o validación afectiva. Solo incorpora la empatía mínima necesaria para ser cortés y no generar fricción adicional. El enfoque es operativo y racional, no terapéutico ni emocional.

## Semana 4

<img width="1169" height="800" alt="image" src="https://github.com/user-attachments/assets/49d4ef3f-d5b1-4634-a925-4403fd5fdab0" />

<img width="488" height="825" alt="image" src="https://github.com/user-attachments/assets/88226e63-56ff-454c-9a68-c50414405649" />


## Semana 5

<img width="1600" height="460" alt="image" src="https://github.com/user-attachments/assets/e777c5eb-25f9-4df7-a47d-9ac4bb744f7a" />

## Semana 6
### Betflow - Attention Gatekeeper

## Contexto
Betflow es un asistente proactivo que reduce el ruido mental, optimiza la atención y actúa como un "segundo cerebro".
Su objetivo es maximizar claridad, foco y acción sin generar dependencia emocional.

---

## Definición de "Ruido"

Se considera "ruido" cualquier información que:

- No aporta directamente al objetivo del usuario.
- Es redundante o repite ideas sin agregar valor.
- Es excesivamente larga sin introducir nueva información útil.
- Contiene lenguaje emocional innecesario o relleno ("no sé", "tal vez", "creo que").
- Incluye detalles irrelevantes que no impactan una decisión o acción.
- Genera distracción o sobrecarga cognitiva.

---

## Reglas de Atención (Gatekeeper)

1. Mensajes largos:
   - Si el mensaje tiene más de 500 palabras:
     - Priorizar sustantivos clave.
     - Priorizar la última frase.
     - Ignorar explicaciones redundantes.

2. Priorización de acción:
   - Detectar verbos de acción (ej: "haz", "explica", "dime").
   - Dar prioridad absoluta a la intención accionable del usuario.

3. Enfoque en objetivo:
   - Identificar el objetivo principal del mensaje.
   - Ignorar información secundaria o desviaciones.

4. Reducción de carga cognitiva:
   - Simplificar la información en pasos claros.
   - Eliminar complejidad innecesaria antes de responder.

5. Manejo de ambigüedad:
   - Elegir la interpretación más concreta y útil.
   - Evitar múltiples interpretaciones si no son necesarias.

6. Eliminación de fricción:
   - Detectar posibles bloqueos o distracciones.
   - Redirigir la atención hacia lo importante.

---

## Objetivo del Sistema

- Reducir ruido mental
- Aumentar claridad
- Optimizar toma de decisiones
- Enfocar energía en lo que realmente importa

  
## SEMANA 7
 ##  3. Arquitectura de Memoria

### Memoria a Largo Plazo (LTM)
> Esta tabla representa la memoria a largo plazo (LTM) del asistente Betflow, equivalente a su "disco duro", donde se almacena información permanente necesaria para la personalización, toma de decisiones y anticipación de necesidades del usuario.

| Tipo de Memoria | Categoría de Datos | Descripción | Ejemplo de Entrada |
|----------------|------------------|------------|-------------------|
| Semántica (LTM) | Métodos de productividad | Técnicas para optimizar enfoque y toma de decisiones | "Método Pomodoro: 25 min trabajo, 5 min descanso" |
| Semántica (LTM) | Reglas de priorización | Criterios para decidir qué es importante | "Priorizar tareas con impacto directo en objetivos" |
| Semántica (LTM) | Conceptos de eficiencia | Estrategias para reducir carga cognitiva | "Eliminar tareas redundantes o sin valor" |
| Semántica (LTM) | Conocimiento general | Información útil para resolver problemas | "Ley de Pareto: 80% resultados vienen de 20% acciones" |
| Semántica (LTM) | Estructuras de planificación | Formas de organizar tareas y objetivos | "Lista de tareas priorizada por impacto" |
| Episódica (LTM) | Perfil del usuario | Información personal relevante | "Usuario: estudiante, enfocado en productividad" |
| Episódica (LTM) | Objetivos del usuario | Metas definidas por el usuario | "Mejorar enfoque y reducir distracciones" |
| Episódica (LTM) | Historial de decisiones | Decisiones tomadas anteriormente | "Decidió estudiar en bloques de 2 horas" |
| Episódica (LTM) | Hábitos y rutinas | Patrones de comportamiento del usuario | "Se distrae frecuentemente con redes sociales" |
| Episódica (LTM) | Tareas recurrentes | Actividades frecuentes del usuario | "Estudiar, entrenar, hacer trabajos" |
| Episódica (LTM) | Problemas frecuentes | Fricciones detectadas | "Procrastinación, sobrecarga de información" |
| Episódica (LTM) | Acciones ejecutadas | Acciones que el bot ya realizó | "Recordatorio creado para estudiar a las 6pm" |

## SEMANA 8
<img width="1600" height="293" alt="image" src="https://github.com/user-attachments/assets/d69fc404-7d90-4f80-8cf5-fd16eb43a735" />

# SEMANA 9
# Betflow - Memory Flow System

## Contexto

Betflow es un asistente inteligente diseñado para optimizar la atención, la memoria y la toma de decisiones.
Su sistema de memoria trabaja en conjunto con el Gatekeeper (filtro de atención) para garantizar que solo la información relevante sea procesada y utilizada.

---

## Flujo de Recuperación

1. Entrada del usuario
   - Se recibe información o una pregunta

2. Filtro de Atención (Gatekeeper)
   - Elimina ruido
   - Extrae la intención principal

3. Clasificación de Intención
   - Se identifica si el mensaje es:
     - Pregunta
     - Acción
     - Contexto relevante

4. Búsqueda en Memoria (LTM - Memoria a Largo Plazo)
   - Se recupera información relevante previa
   - Se prioriza el contexto útil y reciente

5. Construcción de Respuesta
   - Se combina la memoria con la nueva información

6. Respuesta Final
   - Clara
   - Directa
   - Accionable

---

## Gestión de Memoria y Olvido

Betflow no utiliza únicamente reglas de tiempo para olvidar información, sino un sistema adaptativo basado en relevancia y uso.

### Reglas:

- Eliminación de ruido en memoria:
  Se descarta información que no contribuye al objetivo actual.

- Prioridad por uso:
  La información que no se utiliza en varias interacciones pierde relevancia o se elimina.

- Cambio de contexto:
  Si el usuario cambia de tema, el sistema reinicia el contexto anterior.

- Enfoque en objetivo:
  Se mantiene únicamente la información clave para la toma de decisiones.

- Optimización cognitiva:
  Se evita la sobrecarga manteniendo la memoria limpia y eficiente.

---

## Relación con el Gatekeeper

El sistema de memoria trabaja directamente con el Gatekeeper:

- El Gatekeeper filtra la información de entrada
- La memoria decide qué conservar y qué descartar

Esto permite que Betflow funcione como un sistema cognitivo eficiente.

---

## Objetivo

- Mantener claridad mental
- Reducir sobrecarga cognitiva
- Mejorar la toma de decisiones
- Optimizar el uso de la memoria del sistema

<img width="1061" height="840" alt="image" src="https://github.com/user-attachments/assets/bdda5250-aef2-4a0c-8c12-f5b423da8fac" />


