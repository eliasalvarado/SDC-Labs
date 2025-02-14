# Laboratorio 2 - Gen AI Intensive Course

Durante éste laboratorio se tomó el curso otorgado por [`Google Learn Guide`](https://www.kaggle.com/learn-guide/5-day-genai) con el fin de aprender sobre distintos modelos fundamentales y sobre la ingeniería de prompts. Donde se aplicaron distintos casos de uso de la IA Gemini utilizando bases de datos, vectores, agentes de IA, search grounding. En cada uno de los módulos se combinaros distintas técnicas y la aplicación de la teoría.

# ¿Hubo alguna aplicación o caso de uso de los LLMs que le llamó más la atención? ¿Por qué?

Sí, el que se llevó a cabo en el día 3. Nunca se me había ocurrido la integración de una IA como un bot para algún servicio. Mucho menos que la IA pudiera tener herramientas las cuales le ayudarián a conocer la aplicación sobre la que está trabajando. Fue muy interesante ver cómo creando una base de datos simple y funciones para conocer dicha base de datos sería más que suficiente para que el agente de IA fuera capaz de responder cualquier pregunta sin importar que debeía conocer la base de datos o algún elemento en específico. Nunca había visto la integración de una API con una IA con el fin que sus respuestas estén basado en ello.

# Proponga un caso de ciberseguridad que considere se puede solucionar mediante un LLM y describa de forma general cómo lo resolvería.

Se me ocurre poder implementar de una forma u otra un LLM para un análisis continui en los intentos de loggin a cierta plataforma (que obviamente registre dicha acción) o alguna técnica forese para la revisión del sistema luego de un ataque (aunque ésta me parece más compleja y quizas no sea posible).
En general tomaría la tabla de logs que tiene la plataforma y se la enviaría al LLM continuamente, con el fin que llegue a detectar "patrones", con especial atención, en aquellos loggins fallidos. Ya que lo que se querrá realizar es una rápida revisión de si el loggin de cierto lugar con cierto usuario es legítima o no. Entonces el trabajo del LLM sería poder capturar patrones los cuales le ayuden a detectar luego de ciertos intentos si el log es auténtico o se trata de un intruso intentando entrar a la plataforma.