# S25 - Módulo 2. Actividad didáctica 2

Este repositorio corresponde a la **Actividad número 2** del curso de Simulación, titulada:

**S25 - Módulo 2. Actividad didáctica 2**

## Descripción de la actividad

En esta actividad se desarrolla un sistema para detectar posibles fraudes bancarios mediante la simulación y análisis de transacciones financieras utilizando un **Modelo Oculto de Markov (HMM)**. Los objetivos centrales de la actividad incluyen:

- **Simulación de secuencias de transacciones financieras** usando un HMM, replicando el comportamiento de cuentas con distintos patrones de operación.
- **Verificación de la convergencia empírica**: Analizar cómo las frecuencias observadas en las simulaciones tienden a corresponderse con los valores teóricos previstos por la teoría de cadenas de Markov.
- **Aplicación y análisis del algoritmo de Viterbi** para evaluar su capacidad de inferir los estados ocultos a partir de las observaciones generadas, permitiendo identificar cuándo una transacción puede corresponder a un posible fraude.

## Contenido del repositorio

- Notebooks de Jupyter que muestran la implementación del HMM, la simulación de transacciones y la aplicación del algoritmo de Viterbi.
- Documentación y explicación detallada de cada parte del proceso, facilitando el entendimiento de cómo funcionan los modelos de Markov y cómo pueden emplearse para la detección de anomalías en contextos bancarios.
- Ejemplos y análisis de resultados obtenidos.

## Instrucciones de uso paso a paso

1. **Clona el repositorio**
   ```bash
   git clone https://github.com/ladylaura22/Deteccion_de_fraude_bancario.git
   cd Deteccion_de_fraude_bancario
   ```

2. **Instala los requisitos**
   
   Asegúrate de tener Python y Jupyter Notebook instalados. Instala las dependencias necesarias:
   ```bash
   pip install -r requirements.txt
   ```
   *Si no existe un archivo `requirements.txt`, instala paquetes típicos como `numpy`, `pandas`, y `matplotlib`.*

3. **Abre el notebook de la actividad**
   
   Inicia Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   Luego abre el notebook principal (por ejemplo, `Actividad2_HMM.ipynb`) desde el navegador.

4. **Sigue la guía dentro del notebook**
   
   El notebook está estructurado en secciones comprendiendo:
   - Explicación teórica.
   - Definición y simulación del modelo oculto de Markov.
   - Ejecución de simulaciones.
   - Análisis de frecuencias y comparación con la teoría.
   - Aplicación del algoritmo de Viterbi para inferencia de estados ocultos.
   - Visualización y análisis de resultados.

   Sigue cada celda en orden, ejecutando su contenido y leyendo las explicaciones.

5. **Modifica y experimenta**
   
   Puedes ajustar parámetros del modelo (por ejemplo, probabilidades de transición, longitud de la secuencia, estados observables) para ver diferentes resultados y escenarios.

## Integrantes de la actividad

- Lady Laura Olmos Contreras
- Juan Felipe Parra Palacios
- Jorge Andrés Hernández Campos

---

**Repositorio:** [ladylaura22/Deteccion_de_fraude_bancario](https://github.com/ladylaura22/Deteccion_de_fraude_bancario)

**Lenguaje principal:** Jupyter Notebook
