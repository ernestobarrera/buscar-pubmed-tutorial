---
layout: default
title: Casos Clínicos
parent: Tutorial buscar-pubmed
nav_order: 4
---

# Casos Clínicos: domina la búsqueda con práctica real

## Objetivos de aprendizaje

- Aplicar lo aprendido a preguntas clínicas reales en distintas especialidades.
- Practicar la combinación de GPT, filtros y contadores para llegar a respuestas útiles y rápidas.
- Traducir los resultados de la búsqueda en información clara y comprensible para pacientes.

---

## Introducción

La mejor manera de consolidar un aprendizaje es **ponerlo en práctica** con casos reales. En este módulo te enfrentarás a situaciones habituales en consulta y tendrás la oportunidad de resolverlas usando todo lo aprendido. Así, tu curva de aprendizaje será rápida, efectiva y orientada a la práctica diaria.

---

## Selecciona tu área de práctica

<div class="specialty-cards">
  <div class="specialty-card" onclick="showSpecialty('family')">
    <h4>👨‍⚕️ Medicina Familiar</h4>
    <p>Casos de consulta diaria en atención primaria</p>
  </div>
  <div class="specialty-card" onclick="showSpecialty('emergency')">
    <h4>🚨 Urgencias</h4>
    <p>Decisiones rápidas basadas en evidencia</p>
  </div>
  <div class="specialty-card" onclick="showSpecialty('geriatrics')">
    <h4>🧓 Geriatría</h4>
    <p>Intervenciones y seguridad en mayores</p>
  </div>
  <div class="specialty-card" onclick="showSpecialty('pediatrics')">
    <h4>🧒 Pediatría</h4>
    <p>Búsquedas en problemas frecuentes infantiles</p>
  </div>
</div>

---

## 📚 Caso maestro: Medicina Familiar

### Situación clínica real

María, 45 años, con diabetes tipo 2 (HbA1c 8.2%) y tratamiento con metformina, consulta sobre si el ayuno intermitente podría ayudarle a controlar la enfermedad.  
**Pregunta:** ¿Es seguro y realmente funciona el ayuno intermitente en diabetes tipo 2?

---

### Paso 1: Consulta estratégica con GPT

Antes de buscar directamente, plantea la pregunta a GPT.

{% raw %}
{% include reflection-box.html 
   title="✍️ ¿Cómo le preguntarías a GPT?"
   content="<textarea rows='4' style='width: 100%;' placeholder='Incluye: contexto clínico, pregunta concreta y objetivo de búsqueda...'></textarea>"
%}
{% endraw %}

---

### Paso 2: Búsqueda inteligente dirigida

{% raw %}
{% include buscar-pubmed-iframe.html 
   title="Practica el caso de María"
   instructions="Usa términos: 'intermittent fasting diabetes type 2'. Aplica filtros: adultos, tratamiento-CQ, seguridad, atención primaria."
   params="?case=intermittent-fasting-diabetes"
   height="500px"
   checklist="<ul><li>Usaste términos base correctos</li><li>Aplicaste filtros de población y evidencia</li><li>Incluiste filtro de seguridad</li><li>Alcanzaste una cantidad útil de resultados</li></ul>"
%}
{% endraw %}

---

### Paso 3: Estrategia y comunicación clínica

¿Llegaste a 10-50 resultados? ¿Puedes revisar la evidencia en 3 minutos?

Ahora, traduce la respuesta para la paciente: clara, comprensible y basada en evidencia.

{% raw %}
{% include reflection-box.html 
   title="🗣️ ¿Cómo responderías a María?"
   content="<textarea rows='4' style='width: 100%;' placeholder='Explica la respuesta en lenguaje sencillo, incluyendo beneficios, riesgos y seguridad...'></textarea>"
%}
{% endraw %}

---

## Casos adicionales por especialidad

### 🚨 Urgencias  
**Caso:** Deportista de 28 años, dolor torácico atípico, ECG y troponinas normales.  
**Pregunta:** ¿Existe un protocolo de alta precoz seguro para dolor torácico de bajo riesgo?

### 🧓 Geriatría  
**Caso:** Paciente de 78 años con diabetes quiere empezar ejercicio.  
**Pregunta:** ¿Es seguro iniciar ejercicio en diabéticos mayores?

### 🧒 Pediatría  
**Caso:** Niño de 8 años con TDAH. La madre pregunta por la dieta sin gluten.  
**Pregunta:** ¿Existe evidencia para la dieta sin gluten en TDAH infantil?

---

> **Sugerencia:**  
> Puedes resolver estos casos siguiendo el mismo flujo:  
> 1. Plantea bien la pregunta a GPT  
> 2. Usa la herramienta y afina los filtros  
> 3. Revisa el rango de resultados  
> 4. Traduce la respuesta para el paciente o la familia

---

¿Listo/a para tu evaluación final?  
[Ir al siguiente módulo: Evaluación Maestría](evaluacion.md){: .btn .btn-outline }
