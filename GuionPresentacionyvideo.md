
Link de Video: https://youtu.be/YjPIan8L3RM


# Guion de Presentación: Sistemas Expertos
**Laura Michel Buenfil Tolosa**

---

## Diapositiva 1 — Portada

Buenas tardes. Mi nombre es Laura Michel Buenfil Tolosa y el día de hoy voy a presentar el tema **Sistemas Expertos**.

Al inicio me pareció un tema bastante técnico o difícil de comprender, pero al empezar a investigar y leer sobre él, me di cuenta de que en realidad es un tema muy interesante, ya que tiene que ver con cómo intentamos que las computadoras “piensen”, por así decirlo, como lo haría un especialista humano.

Además, tiene mucha relación con la **inteligencia artificial**, una tecnología que usamos constantemente hoy en día, tanto estudiantes como personas en general.

Durante esta presentación veremos conceptos importantes como qué es el conocimiento en este contexto, qué es una base de conocimiento, cómo funciona el motor de inferencia, un poco de historia de los sistemas expertos y los tipos que existen.

---

## Diapositiva 2 — ¿Qué es un Sistema Experto?

Antes de entrar en detalles, primero debemos entender qué es un sistema experto.

Un sistema experto es básicamente un programa de computadora que intenta imitar la forma en la que razona un experto humano en un área específica.

Por ejemplo, puede simular el razonamiento de un médico, un ingeniero o un asesor financiero.

El sistema recibe información y, utilizando reglas y conocimiento almacenado, puede llegar a una conclusión o generar una recomendación.

En esta presentación veremos cinco temas principales, los cuales iré explicando uno por uno.

---

## Diapositiva 3 — El Conocimiento

El primer concepto importante es el **conocimiento**.

Aquí es importante aclarar que no hablamos del conocimiento en un sentido filosófico, sino de algo más concreto: toda la información, reglas y experiencia que el sistema necesita para poder funcionar.

Existen cuatro tipos principales de conocimiento utilizados en sistemas expertos:

- **Conocimiento fáctico:** son hechos concretos del área.
- **Conocimiento heurístico:** son estrategias o experiencia que normalmente solo posee alguien con práctica.
- **Conocimiento procedimental:** describe cómo se realizan las cosas paso a paso.
- **Metaconocimiento:** consiste en saber cuándo y cómo usar el resto del conocimiento.

Sin conocimiento de calidad, el sistema simplemente no funciona, sin importar qué tan avanzada sea la tecnología detrás.

---

## Diapositiva 4 — Base de Conocimiento

Ahora surge una pregunta: ¿dónde se guarda todo ese conocimiento?

Ahí entra la **base de conocimiento**.

Podemos imaginarla como una biblioteca altamente especializada.

Está compuesta por tres partes principales:

### Hechos
Son datos que el sistema reconoce como verdaderos.

### Reglas SI... ENTONCES
Esta es una de las partes más importantes.

Por ejemplo:

> SI la temperatura es mayor a 40°C  
> ENTONCES hay fiebre alta.

Estas reglas representan la manera en la que razona el experto.

### Ontologías o marcos
Son estructuras que organizan conceptos y sus relaciones.

Esta base es construida por ingenieros del conocimiento en colaboración con expertos reales del área.

Su calidad es fundamental para que el sistema funcione correctamente.

---

## Diapositiva 5 — Motor de Inferencia

Ya tenemos el conocimiento almacenado, pero ahora surge otra pregunta: ¿quién lo utiliza?

Aquí entra el **motor de inferencia**, considerado el cerebro del sistema experto.

Su función es:

1. Tomar los hechos disponibles  
2. Aplicar las reglas de la base de conocimiento  
3. Llegar a una conclusión  

Existen dos estrategias principales:

### Encadenamiento hacia adelante
Parte de hechos conocidos y aplica reglas hasta alcanzar una conclusión.

### Encadenamiento hacia atrás
Parte de una hipótesis y busca hechos que la confirmen o descarten.

También puede manejar incertidumbre, es decir, situaciones donde no todo es completamente exacto, utilizando factores de certeza o lógica difusa.

---

## Diapositiva 6 — Arquitectura Completa

En esta parte vemos cómo trabajan juntos todos los componentes.

El usuario interactúa con el sistema mediante una interfaz.

Esa interfaz se comunica con el motor de inferencia, el cual consulta tanto la base de conocimiento como la base de hechos para generar una respuesta.

Además, existe un **módulo de explicación**, que permite al sistema explicar por qué llegó a una determinada conclusión.

Esto hace que el sistema sea más confiable y útil para el usuario.

---

## Diapositiva 7 — Línea del Tiempo

Los sistemas expertos no son tan nuevos como podría parecer.

Veamos cómo evolucionaron:

- **1965 — DENDRAL:** primer sistema experto real, desarrollado en Stanford para analizar estructuras químicas.
- **1972 — MYCIN:** sistema usado para el diagnóstico de enfermedades infecciosas.
- **1980 — R1 o XCON:** utilizado para configurar computadoras y considerado un gran éxito comercial.
- **1986:** ocurre un gran boom comercial y muchas empresas comienzan a adoptarlos.
- **Década de 1990:** empiezan a combinarse con redes neuronales.
- **2000 en adelante:** se integran con internet, Big Data e inteligencia artificial moderna.

---

## Diapositiva 8 — Tipos de Sistemas Expertos

No todos los sistemas expertos tienen la misma función.

Dependiendo de su propósito, se clasifican en distintos tipos:

### Diagnóstico
Identifican la causa de un problema.

### Planificación
Generan planes o secuencias de acciones.

### Configuración
Combinan componentes para cumplir ciertos requisitos.

### Predicción
Intentan anticipar situaciones futuras basándose en datos.

Ejemplos: clima o mercados financieros.

### Instrucción
Funcionan como tutores y adaptan el contenido al usuario.

### Reparación
Proponen soluciones cuando existen fallas en equipos o sistemas.

---

## Diapositiva 9 — Conclusión

Para concluir, los sistemas expertos representan una de las aplicaciones más importantes de la inteligencia artificial, ya que permiten simular el razonamiento y la toma de decisiones de un especialista humano en un área específica.

Gracias a su capacidad para analizar información y ofrecer soluciones o recomendaciones, han sido útiles en campos como la medicina, la industria, la agricultura y la educación.

Aunque presentan ventajas como la rapidez y la reducción de errores, también tienen limitaciones, principalmente porque dependen del conocimiento previamente programado y no pueden adaptarse tan fácilmente como una persona.

Aun así, su desarrollo ha sido clave para el avance de la inteligencia artificial y demuestra cómo la tecnología puede apoyar en la resolución de problemas complejos.

Cada día continúan desarrollándose nuevas aplicaciones, por lo que seguirán siendo una herramienta muy importante en el futuro.

**Muchas gracias.**