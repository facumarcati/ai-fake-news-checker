# Introduccion

La proliferación de noticias falsas sobre salud, politica y temas sociales genera desinformacion y afecta la toma de decisiones de las personas.
Este proyecto propone una guia asistida por IA que ayuda a verificar, resumir y simplificar informacion, facilitando el acceso a contenido confiable.

---

# Problema

* Circulacion masiva de informacion engañosa en redes sociales y medios digitales.
* Dificultad para que el usuario comun evalúe la veracidad de las fuentes
* Impacto social negativo de la desinformacion en temas sensibles.

---

# Propuesta de solución

Se utilizarán tecnicas de Fast Prompting para:
* Verificacion - comparar una noticia con fuentes confiables.
* Resumen - generar una version clara y accesible para el usuario final.

---

# Justificacion de la viabilidad

* Uso de modelos accesibles y disponibles publicamente como OpenAI o Gemini y plataformas de generacion de imagenes como Stable Diffusion.
* Bajo costo: se optimizan los prompts para reducir la cantidad de consultas necesarias.
* Proyecto modular, implementable dentro de un Jupyter Notebook en etapas simples.

---

# Objetivos 

* Demostrar como el Fast Prompting mejora la verificacion de noticias falsas.
* Optimizar las consultas a la API para hacer el proyecto rentable.
* Producir un output claro, resumido y confiable para el usuario final.

---

# Metodologia

1- Seleccionar una noticia falsa (real o inventada)
2- Probar un prompt basico ("Es verdadera esta noticia"?)
3- Refinar con Fast Prompting - actua como un verificador de hechos. Busca inconsistencias, menciona fuentes confiables y responde en un maximo de 3 puntos.
4- Comparar outputs y documentar resultados con el notebook.

---

# Herramientas y tecnologias

* Jupyter Notebook (POC)
* OpenAi o Gemini (texto)
* Stable Diffusion (imagenes)
* Tecnicas de Fast Prompting
  * Claridad y concision.
  * Restricciones de formato
  * Few shot prompting

---

# Implementacion

* El notebook va a mostrar:
  1- Prompt inicial vs Prompt refinado
  2- Comparacion de resultados
  3- Ejemplo de como el refinamiento mejora la precision y claridad
* Se medirá el costo en consultas a la API y se documentará como se optimizó el flujo
