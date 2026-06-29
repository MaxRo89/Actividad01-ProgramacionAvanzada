# Guion de Exposición: Sistemas Expertos

## Diapositiva 1. Introducción

**Buenas  tardes.**

Hoy hablaremos sobre los **Sistemas Expertos**, una de las primeras aplicaciones exitosas de la inteligencia artificial.

El objetivo de estos sistemas es emular la forma en que un experto humano resuelve problemas dentro de un área específica, como medicina, ingeniería o finanzas.

A lo largo de la presentación veremos cómo almacenan el conocimiento, cómo razonan para tomar decisiones, su evolución histórica y los principales tipos que existen.

---

# Diapositiva 2. ¿Qué es un Sistema Experto?

Primero debemos entender qué es un sistema experto.

Un sistema experto es un programa diseñado para comportarse como un especialista en un dominio determinado.

La diferencia con un programa tradicional es que **no solamente ejecuta cálculos**, sino que también **razona utilizando conocimiento previamente almacenado**.

Además, puede explicar por qué llegó a una determinada conclusión, algo muy importante para generar confianza en sus respuestas.

Por ejemplo, un sistema experto médico puede recomendar un diagnóstico y explicar qué síntomas y reglas utilizó para llegar a esa conclusión.

---

# Diapositiva 3. El conocimiento

Uno de los elementos más importantes de un sistema experto es el **conocimiento**.

Podemos entender el conocimiento como toda la información y experiencia que posee un especialista sobre un tema y que posteriormente se almacena dentro del sistema.

Este conocimiento puede clasificarse en tres tipos principales:

- **Conocimiento declarativo**, que corresponde a los hechos y conceptos del dominio, como diagnósticos, recetas médicas o fórmulas.
- **Conocimiento procedimental**, que indica los pasos o reglas que deben seguirse para resolver un problema.
- **Conocimiento heurístico**, que representa la experiencia del experto, es decir, aquellos métodos prácticos que permiten encontrar soluciones de manera más eficiente.

En conjunto, estos tres tipos permiten que el sistema tome decisiones similares a las de un especialista humano.

---

# Diapositiva 4. Base de conocimiento y motor de inferencia

La arquitectura de un sistema experto está formada por varios componentes, pero los dos más importantes son la **base de conocimiento** y el **motor de inferencia**.

## Base de conocimiento

La base de conocimiento es donde se almacena toda la información del experto.

Aquí se guardan:

- los hechos,
- las reglas,
- y las relaciones entre ellos.

Podemos compararla con la memoria de un especialista.

## Motor de inferencia

El motor de inferencia es el componente encargado de analizar toda esa información para llegar a conclusiones.

En otras palabras, es el "cerebro" del sistema.

Su función consiste en revisar las reglas disponibles, comparar los datos proporcionados por el usuario y determinar cuál es la mejor respuesta o recomendación.

Sin una base de conocimiento el sistema no tendría información para trabajar, y sin un motor de inferencia no podría razonar sobre esa información. Ambos trabajan siempre de forma conjunta.

---

# Diapositiva 5. ¿Cómo razonan las máquinas?

Ahora bien, ¿cómo toma decisiones un sistema experto?

La mayoría utiliza reglas del tipo **"Si... Entonces..."**.

Por ejemplo:

> "Si el paciente presenta fiebre y dolor de garganta, entonces existe la posibilidad de una infección."

El motor de inferencia puede utilizar dos estrategias principales:

- **Encadenamiento hacia adelante**, donde parte de los hechos conocidos y aplica reglas hasta obtener una conclusión.
- **Encadenamiento hacia atrás**, donde primero plantea una hipótesis y después busca evidencia que permita confirmarla o descartarla.

Estas técnicas permiten que el sistema simule el razonamiento lógico de un experto humano.

---

# Diapositiva 6. Línea del tiempo

La evolución de los sistemas expertos puede resumirse en cuatro etapas.

### Década de 1960 — Los orígenes

Surgieron los primeros trabajos de inteligencia artificial junto con lenguajes como **LISP** y programas como **General Problem Solver (GPS)**.

### Década de 1970 — El salto cualitativo

Apareció **MYCIN**, uno de los sistemas expertos más famosos, desarrollado para apoyar el diagnóstico de enfermedades infecciosas.

### Década de 1980 — Auge comercial

Muchas empresas comenzaron a utilizar sistemas expertos y aparecieron herramientas especializadas para desarrollarlos.

### Actualidad — Nueva era

Los sistemas expertos se combinan con tecnologías modernas como el aprendizaje automático, el procesamiento de lenguaje natural y el análisis de grandes volúmenes de datos.

---

# Diapositiva 7. Aplicaciones

Los sistemas expertos tienen aplicaciones en muchos sectores.

- **Medicina:** ayudan a realizar diagnósticos y apoyar las decisiones clínicas.
- **Ingeniería:** permiten detectar fallas en maquinaria compleja de manera rápida.
- **Finanzas:** se utilizan para analizar riesgos y apoyar la toma de decisiones de inversión o de otorgamiento de créditos.

Esto demuestra que su utilidad no se limita a un solo campo, sino que puede extenderse a prácticamente cualquier área donde exista conocimiento especializado.

---

# Diapositiva 8. Tipos de sistemas expertos

Existen diferentes tipos de sistemas expertos dependiendo de cómo representan el conocimiento.

## Basados en reglas

Utilizan reglas del tipo **"Si... Entonces..."** y son ideales cuando el problema está bien definido y existen procedimientos claros.

## Basados en casos

Almacenan experiencias anteriores y buscan casos similares para resolver nuevos problemas.

## Basados en modelos

Representan el funcionamiento interno de un sistema físico o técnico, por lo que son muy utilizados en ingeniería y mantenimiento.

Cada uno tiene ventajas dependiendo del tipo de problema que se desea resolver.

---

# Diapositiva 9. Ventajas

Entre las principales ventajas encontramos:

- **Permanencia:** el conocimiento no se pierde con el tiempo.
- **Replicación:** el conocimiento de un experto puede compartirse con muchas personas simultáneamente.
- **Fiabilidad:** el sistema aplica siempre las mismas reglas sin verse afectado por cansancio o emociones.

Gracias a estas características, los sistemas expertos siguen siendo herramientas muy valiosas para apoyar la toma de decisiones.

---

# Conclusión

Para concluir, los sistemas expertos representan una de las aplicaciones más importantes de la inteligencia artificial.

Su objetivo no es reemplazar a los especialistas, sino **capturar su conocimiento y ponerlo al alcance de más personas**.

Actualmente continúan evolucionando al combinarse con tecnologías modernas como el aprendizaje automático y los modelos de lenguaje, lo que permite construir sistemas cada vez más inteligentes y capaces de ayudar en problemas complejos.



---
