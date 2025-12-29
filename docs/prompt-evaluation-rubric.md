# Prompt Evaluation Rubric / Rúbrica de Evaluación de Prompts

This rubric provides a structured way to evaluate the quality of prompts used with LLMs and Generative AI.
It is designed for **business, analytics, and production contexts**, not experimentation only.

Esta rúbrica proporciona una forma estructurada de evaluar la calidad de prompts utilizados con LLMs y AI generativa.
Está diseñada para **contextos de negocio, analítica y producción**, no solo para experimentación.

---

## How to use this rubric / Cómo usar esta rúbrica

**EN**
- Evaluate each criterion independently
- Score from 1 (Poor) to 5 (Excellent)
- Use total score as a comparative indicator, not absolute truth

**ES**
- Evalúa cada criterio de forma independiente
- Asigna un puntaje de 1 (Deficiente) a 5 (Excelente)
- Usa el puntaje total como indicador comparativo, no como verdad absoluta

---

## Evaluation Criteria / Criterios de Evaluación

### 1. Role Clarity / Claridad del Rol

**EN**
Is the role of the model clearly defined and appropriate for the task?

**ES**
¿El rol del modelo está claramente definido y es apropiado para la tarea?

| Score | Description |
|------|-------------|
| 1 | No role defined or irrelevant role |
| 3 | Generic role with limited guidance |
| 5 | Clear, specific, and context-aware role |

---

### 2. Context Quality / Calidad del Contexto

**EN**
Does the prompt provide sufficient and relevant context without overloading the model?

**ES**
¿El prompt proporciona contexto suficiente y relevante sin sobrecargar al modelo?

| Score | Description |
|------|-------------|
| 1 | Missing or vague context |
| 3 | Partial or generic context |
| 5 | Precise, relevant, and well-scoped context |

---

### 3. Task Definition / Definición de la Tarea

**EN**
Is the task clearly stated and unambiguous?

**ES**
¿La tarea está claramente definida y no deja lugar a ambigüedad?

| Score | Description |
|------|-------------|
| 1 | Task is unclear or open-ended |
| 3 | Task is defined but partially ambiguous |
| 5 | Task is explicit, focused, and testable |

---

### 4. Constraints & Guardrails / Restricciones y Límites

**EN**
Does the prompt define constraints that reduce hallucination and irrelevant output?

**ES**
¿El prompt define restricciones que reduzcan alucinaciones y salidas irrelevantes?

| Score | Description |
|------|-------------|
| 1 | No constraints |
| 3 | Some constraints, inconsistently applied |
| 5 | Clear, enforceable constraints aligned with the goal |

---

### 5. Output Structure / Estructura de Salida

**EN**
Is the expected output format clearly defined?

**ES**
¿El formato de salida esperado está claramente definido?

| Score | Description |
|------|-------------|
| 1 | No output structure |
| 3 | Basic structure |
| 5 | Clear, structured, and reusable format |

---

### 6. Reasoning & Explainability / Razonamiento y Explicabilidad

**EN**
Does the prompt encourage transparent reasoning and traceability?

**ES**
¿El prompt fomenta razonamiento transparente y trazabilidad?

| Score | Description |
|------|-------------|
| 1 | No reasoning requested |
| 3 | Implicit or partial reasoning |
| 5 | Explicit, structured reasoning |

---

### 7. Business Alignment / Alineación con Negocio

**EN**
Is the prompt aligned with real business decision-making needs?

**ES**
¿El prompt está alineado con necesidades reales de toma de decisiones de negocio?

| Score | Description |
|------|-------------|
| 1 | Purely theoretical or generic |
| 3 | Some business relevance |
| 5 | Strong alignment with business context and constraints |

---

## Scoring Interpretation / Interpretación del Puntaje

| Total Score | Interpretation |
|------------|----------------|
| 7–14 | Weak prompt – high risk of poor outputs |
| 15–24 | Acceptable prompt – improvement recommended |
| 25–30 | Strong prompt – suitable for repeated use |
| 31–35 | Production-grade prompt |

---

## Notes / Notas

**EN**
This rubric is meant to support human judgment, not replace it.
High scores do not guarantee correct outputs, but low scores almost guarantee problems.

**ES**
Esta rúbrica está pensada para apoyar el juicio humano, no para reemplazarlo.
Puntajes altos no garantizan resultados correctos, pero puntajes bajos casi garantizan problemas.
