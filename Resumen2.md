# Sistemas Expertos Basados en Reglas

**Nombre:** Rosendo Maximiliano Rodriguez Alvarado

## 2. Sistemas Expertos Basados en Reglas

Los **sistemas expertos basados en reglas** representan una metodología altamente eficiente para enfrentar problemas deterministas, como los sistemas de control de tráfico o las transacciones. Todo el conocimiento de este tipo de sistemas se organiza en dos componentes primordiales:

### Base de Conocimiento

Almacena:

- **Hechos:** afirmaciones dinámicas pertenecientes a la situación particular que se analiza.
- **Reglas:** estatutos estáticos y permanentes del dominio en cuestión.

Una regla típica es una afirmación condicional integrada por:

- **Premisa:** el antecedente de la condición.
- **Conclusión:** el consecuente lógico resultante.

### Motor de Inferencia

Es el procesador encargado de deducir nuevas conclusiones aplicando la lógica sobre las reglas y hechos almacenados.

Para ello, utiliza dos reglas de inferencia esenciales:

- **Modus Ponens:** opera hacia adelante concluyendo un hecho si se cumple su premisa.
- **Modus Tollens:** opera hacia atrás invalidando la premisa si se comprueba que la conclusión es falsa.

### Estrategias de Encadenamiento

Para llegar a conclusiones más complejas, el **Motor de Inferencia** emplea estrategias como:

#### Encadenamiento hacia adelante

Las conclusiones de unas reglas se convierten en las premisas de otras, desencadenando nuevos hechos hasta que no sea posible deducir más información.

#### Encadenamiento orientado a un objetivo

Navega el árbol de decisiones desde un resultado deseado (la meta) hacia atrás, evaluando y requiriendo los hechos necesarios para validar dicha meta.

### Subsistemas Adicionales

#### Control de la Coherencia

Evita el ingreso de conocimiento y datos inconsistentes al sistema, previniendo que el motor lógico obtenga conclusiones erróneas.

Para ello, es necesario:

- Depurar constantemente los **valores no factibles** del sistema (hechos que contradicen otras reglas).
- Actualizar la base de conocimientos inmediatamente después de ingresar un hecho nuevo.

#### Explicación de Conclusiones

Un sistema experto debe contar con herramientas de trazabilidad para que el usuario pueda consultar el listado exacto de las reglas que determinaron las conclusiones finales y comprender el **por qué** de dichas conclusiones.