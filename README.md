## Diseño de Agentes Inteligentes

Este proyecto tiene como objetivo implementar un simulador que determine la medida de rendimiento para el entorno de una aspiradora. La implementación será modular, permitiendo la modificación de sensores, actuadores y características del entorno.

### Pasos para la Implementación:

1. **Definir Recompensas**:
   - Las recompensas serán la medida de rendimiento del simulador.
   - Posibles recompensas:
     - Positivas: Aspiradora limpia la suciedad.
     - Negativas: Aspiradora choca con un obstáculo.
     - Neutrales: Aspiradora no realiza ninguna acción.

2. **Definir Algoritmo de Aprendizaje**:
   - Se utilizará un algoritmo de aprendizaje, como el aprendizaje por refuerzo, para aprender de las acciones y recompensas recibidas.

3. **Entrenar el Modelo**:
   - Una vez definido el entorno, la aspiradora, las acciones, las recompensas y el algoritmo de aprendizaje, se procede al entrenamiento del modelo en el simulador.

4. **Evaluar el Modelo**:
   - Se evaluará el modelo para determinar su rendimiento, incluyendo la cantidad de suciedad limpiada, la evitación de obstáculos y la eficiencia en el movimiento.

### Implementación del Agente Sin Estado:

- **Agente Sin Estado**:
  - Recorrerá la cuadrícula realizando un zig-zag desde la posición de inicio del agente.
  
### Tecnologías y Herramientas Utilizadas:

- El lenguaje de programación es libre, pero se sugiere utilizar un lenguaje adecuado para la implementación del simulador y el algoritmo de aprendizaje, como Python.
- Se pueden utilizar bibliotecas como OpenAI Gym para la implementación del entorno y el aprendizaje por refuerzo.

### Pasos Futuros:

- Una vez implementado el agente sin estado, se pueden explorar otras estrategias de agentes inteligentes, como agentes basados en estados, redes neuronales, etc.
- Se puede mejorar la modularidad del código para permitir una fácil extensión y modificación de las características del entorno, sensores y actuadores.
