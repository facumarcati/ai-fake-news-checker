# AI Fake News Checker

## Resumen
Este proyecto propone una **POC (Proof of Concept)** que utiliza IA para abordar el problema de la desinformación digital.  
Se emplean dos enfoques:  
1. **Texto→Texto**: un modelo de lenguaje (LLM) analiza noticias, verifica su veracidad y genera un resumen claro.  
2. **Texto→Imagen**: una herramienta externa (NightCafe / Stable Diffusion) genera imágenes ilustrativas que acompañan la explicación.

El objetivo es demostrar cómo las técnicas de **Fast Prompting** permiten mejorar la calidad de las verificaciones y optimizar recursos.

---

## Introducción

### Problema
La circulación masiva de noticias falsas en redes sociales y medios digitales genera confusión y afecta la toma de decisiones de las personas.  
Temas como salud, política o seguridad se ven especialmente afectados por la desinformación.  

### Propuesta de solución
Este proyecto plantea un **asistente IA** que:  
- Verifica si una noticia es verdadera, falsa o dudosa.  
- Resume la información de forma clara y accesible.  
- Genera material visual (imágenes ilustrativas) para reforzar la comprensión.  

---

## Justificación de la viabilidad
- Los modelos de lenguaje (OpenAI GPT o equivalentes) están disponibles públicamente.  
- La generación de imágenes puede hacerse con herramientas gratuitas (Stable Diffusion, NightCafe).  
- El enfoque modular permite implementar todo en un Jupyter Notebook sin requerir grandes recursos.  
- Los prompts optimizados reducen el costo de uso de APIs.  

---

## Objetivos
- Demostrar que el **Fast Prompting** mejora la verificación de noticias falsas.  
- Optimizar consultas a la API para mantener el proyecto accesible.  
- Entregar resultados claros, resumidos y confiables al usuario final.  
- Incorporar imágenes generadas automáticamente como complemento visual.  

---

## Metodología
1. Seleccionar un conjunto de noticias (falsas, verdaderas y dudosas).  
2. Probar un **prompt básico** (“¿Es verdadera esta noticia?”).  
3. Refinar el prompt aplicando técnicas de **Fast Prompting** (rol, few-shot, formato de respuesta en puntos).  
4. Comparar outputs y documentar mejoras.  
5. Generar imágenes ilustrativas con herramientas externas.  
6. Evaluar la claridad, consistencia y utilidad de los resultados.  

---

## Herramientas y tecnologías
- **Jupyter Notebook** (implementación).  
- **Modelos de lenguaje**: OpenAI GPT-4o mini (texto→texto).  
- **Generadores de imagen**: Stable Diffusion / NightCafe (texto→imagen).  
- **Técnicas de Fast Prompting**:  
  - Definición de roles.  
  - Restricciones de formato.  
  - Respuestas concisas.  
  - Few-shot prompting.  

---

## Implementación
La notebook (`notebooks/ia_fake_news_checker.ipynb`) incluye:  
- Prompt básico vs. prompt refinado.  
- Comparación de resultados con varias noticias.  
- Ejemplo de optimización de consultas a la API.  
- Celda con prompts de generación de imagen y visualización de resultados.  

---

## Resultados
- El prompt básico devuelve respuestas genéricas y poco confiables.  
- El Fast Prompting produce resultados más estructurados, con evidencias y recomendaciones claras.  
- La combinación de texto→texto e imágenes facilita la comprensión y aumenta el valor comunicativo.  

---

## Conclusiones
- Se lograron los objetivos propuestos: demostrar mejoras con Fast Prompting y complementar con generación de imágenes.  
- El proyecto es **viable, económico y escalable**: puede crecer con datasets reales de noticias y más técnicas de IA.  
- La propuesta muestra cómo IA puede ser un aliado en la lucha contra la desinformación.  

---

## Referencias
- OpenAI API docs.  
- Stable Diffusion Web UI.  
- NightCafe Studio.  
- Material del curso: “IA: Entretejiendo Imaginación y Algoritmos”.
