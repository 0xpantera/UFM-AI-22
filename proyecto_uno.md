# **Proyecto: Explorando Arquitecturas de Deep Learning con PyTorch**

### **Objetivo**

El objetivo de este proyecto es brindar a los estudiantes la oportunidad de explorar y comprender en profundidad tres arquitecturas críticas de redes neuronales profundas: Convolutional Neural Networks (CNN), Recurrent Neural Networks (RNN) y Long Short-Term Memory Networks (LSTM). A través de este proyecto, los alumnos aplicarán los conceptos y técnicas aprendidos durante el curso para construir, entrenar y evaluar modelos basados en estas arquitecturas utilizando PyTorch, una de las bibliotecas más populares para deep learning.

### **Instrucciones**

Para cada una de las arquitecturas de redes neuronales que se mencionan a continuación, los estudiantes deberán:

1. **Investigación Previa**
   - Investigar y comprender cómo funciona cada tipo de red neuronal.
   - Identificar un problema específico que se pueda resolver eficazmente utilizando la arquitectura correspondiente.

2. **Preparación de Datos**
   - Seleccionar un conjunto de datos adecuado para el problema identificado.
   - Crear un `Dataset` utilizando PyTorch y definir los `Dataloaders` para manejar la entrada y salida de datos durante el entrenamiento y la evaluación.

3. **Construcción del Modelo**
   - Definir la arquitectura del modelo como una subclase de `nn.Module` en PyTorch.
   - Explicar la elección de las diferentes capas y parámetros utilizados en el modelo.

4. **Selección del Optimizador y Función de Costo**
   - Elegir un optimizador y una función de costo apropiados para entrenar el modelo.
   - Justificar la elección del optimizador y la función de pérdida explicando cómo trabajan y por qué son adecuados para el problema en cuestión.

5. **Entrenamiento del Modelo**
   - Implementar el loop de entrenamiento donde el modelo será entrenado usando los datos de entrenamiento.
   - Asegurarse de que el modelo esté aprendiendo correctamente y ajustar los hiperparámetros si es necesario.

6. **Evaluación del Modelo**
   - Evaluar el desempeño del modelo utilizando un conjunto de datos de test.
   - Implementar métricas de evaluación adecuadas para el problema y discutir los resultados obtenidos.

7. **Documentación**
   - Documentar todo el proceso en un informe que incluya: código, explicaciones teóricas y análisis de los resultados.
   - Presentar las conclusiones y discutir posibles mejoras y futuras líneas de trabajo.

### **Arquitecturas a Explorar**

1. **Convolutional Neural Networks ([CNN](https://mila.quebec/wp-content/uploads/2016/03/2015-lecun-bengio-hinton-nature.pdf))**
   - Ideal para problemas relacionados con imágenes y visión por computadora.

2. **Recurrent Neural Networks (RNN)**
   - Adecuada para procesamiento de secuencias y series temporales.

3. **Long Short-Term Memory Networks ([LSTM](https://deeplearning.cs.cmu.edu/F23/document/readings/LSTM.pdf))**
   - Útil para tareas que requieren memoria de largo plazo, como traducción automática y reconocimiento de voz.

4. **Generative Adversarial Network ([GAN](https://arxiv.org/abs/1406.2661))**

### **Entregables**

En un solo Jupyter notebook incluir:
- **Código**: Python bien comentado para cada arquitectura que incluya todas las etapas desde la carga de datos hasta la evaluación del modelo.
- **Informe**: Detalle que describa cada paso del proceso, incluyendo las justificaciones para las decisiones tomadas y el análisis de los resultados obtenidos.

### **Criterios de Evaluación**

- **Comprensión Teórica**: Demuestra una comprensión profunda de cada arquitectura de red neuronal y su aplicación.
- **Implementación**: Calidad del código y correcta implementación de las arquitecturas utilizando PyTorch.
- **Análisis y Discusión**: Profundidad del análisis de los resultados y calidad de la discusión sobre posibles mejoras.

### **Fecha de Entrega**
Lunes 25 de septiembre
