---
layout: default
title: Contadores Inteligentes
parent: Tutorial buscar-pubmed
nav_order: 3
---

# Contadores Inteligentes: el arte de leer los números

## Objetivos de aprendizaje

- Comprender cómo interpretar los contadores en tiempo real para optimizar tu búsqueda.
- Saber cuándo tu búsqueda es demasiado amplia, demasiado específica, o está “en la zona óptima”.
- Desarrollar una estrategia basada en el refinamiento guiado por números, no por intuición.

---

## Introducción

En PubMed, la diferencia entre recibir 50.000 resultados irrelevantes y encontrar 30 artículos útiles suele ser cuestión de cómo lees y ajustas los **contadores**. Este módulo te enseña a pensar como los expertos: **leer los números, actuar en consecuencia y refinar estratégicamente**.

---

## Conceptos clave

- **Contador principal:** Te muestra el total de resultados según los filtros y términos aplicados.
- **Contadores individuales:** Cuando activas el "ojo", cada filtro te revela su impacto potencial.
- **Zona dorada:** Un rango de resultados manejable (habitualmente 20-80) que maximiza relevancia y eficiencia.

> **Regla de oro:**  
> - 15.000+ → Demasiado amplio: necesitas más filtros.
> - 100-500 → Zona perfecta para revisión clínica.
> - <10 → Demasiado específico: elimina filtros.

---

## Ejemplo paso a paso: cannabis y artritis

1. Escribe: `cannabis arthritis pain`
2. Observa el **contador principal** (probablemente >15.000)
3. **Activa el “ojo”** para ver cómo cada filtro puede reducir (o no) el volumen.
4. Aplica un filtro de población (por ejemplo, “geriatría”).
5. Aplica filtro de tratamiento (“Tratamiento-CQ”).
6. Observa cómo los números cambian y cuándo entras en la **zona dorada**.

---

## Laboratorio interactivo

{% raw %}
{% include buscar-pubmed-iframe.html 
   title="Laboratorio de contadores"
   instructions="Sigue la secuencia: aplica filtros y observa cómo varía el contador principal. Tu objetivo: 20-80 resultados relevantes."
   params="?demo=cannabis-arthritis"
   height="500px"
   checklist="<ul><li>Activaste el botón del ojo 👁️</li><li>Observaste números en cada filtro</li><li>Llegaste a la zona 20-80 resultados</li></ul>"
%}
{% endraw %}

---

## Práctica: afinando tu propia búsqueda

Piensa en una pregunta real de tu consulta.  
Prueba la herramienta buscando inicialmente con términos amplios, observa los números, y ve aplicando filtros hasta alcanzar una cantidad útil para revisar rápidamente.

{% raw %}
{% include reflection-box.html 
   title="🧩 ¿Cómo fue tu proceso de refinamiento?"
   content="<textarea rows='4' style='width: 100%;' placeholder='Describe cómo pasaste de muchos resultados a una búsqueda útil...'></textarea>"
%}
{% endraw %}

---

## Claves para recordar

- Los contadores te enseñan cuándo y cómo aplicar filtros.
- No busques a ciegas: usa los números como guía estratégica.
- La “zona dorada” (20-80) suele ser ideal para revisiones rápidas en consulta.
- El “ojo” es tu mejor aliado para anticipar el impacto de cada decisión.

---

¿Listo/a para poner a prueba lo aprendido con casos clínicos reales?  
[Ir al siguiente módulo: Casos Clínicos](casos-clinicos.md){: .btn .btn-outline }
