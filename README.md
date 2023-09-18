# DevOps For Machine Learning | MLOps
Este repositorio es un taller práctico de MLOps utilizando [Azure Machine Learning]( https://docs.microsoft.com/en-us/azure/machine-learning/) and [Azure DevOps]( https://docs.microsoft.com/en-us/azure/devops/?view=azure-devops&viewFallbackFrom=vsts). 

![ML Loop](./architecture/ml-loop.PNG)

##  MLOps Workflow

Machine Learning Operations ([MLOps]( https://docs.microsoft.com/en-us/azure/machine-learning/concept-model-management-and-deployment)) se basa en principios y prácticas de DevOps que aumentan la eficiencia de los flujos de trabajo. 

Este repositorio contiene códigos y pautas para configurar el flujo de trabajo MLOps con Azure como se muestra a continuación:

![Flow](./architecture/flow.PNG)

##  MLOps with Azure Machine Learning 

Azure Machine Learning proporciona las siguientes capacidades de MLOps:

- **Canales de aprendizaje automático - Pipelines** le permiten definir pasos repetibles y reutilizables para sus procesos de preparación, capacitación y puntuación de datos.
- **Cree entornos de software reutilizables - Environments** para entrenar e implementar modelos.
- **Registre, empaquete e implemente modelos** desde cualquier lugar. También puede realizar un seguimiento de los metadatos asociados necesarios para utilizar el modelo.
- **Capture los datos de gobernanza** para el ciclo de vida del aprendizaje automático de un extremo a otro. La información registrada puede incluir quién publica los modelos, por qué se realizaron cambios y cuándo se implementaron o utilizaron los modelos en producción.
- **Notificar y alertar sobre eventos en el ciclo de vida de ML**. Por ejemplo, finalización de experimentos, registro de modelos, implementación de modelos y detección de desviación de datos.
- **Supervise las aplicaciones de ML para detectar problemas operativos y relacionados con ML**. Compare las entradas del modelo entre entrenamiento e inferencia, explore métricas específicas del modelo y proporcione monitoreo y alertas en su infraestructura de aprendizaje automático.
- **Automatice el ciclo de vida del aprendizaje automático de un extremo a otro con Azure Machine Learning y Azure Pipelines**. El uso de canalizaciones le permite actualizar modelos con frecuencia, probar nuevos modelos e implementar continuamente nuevos modelos de ML junto con sus otras aplicaciones y servicios.

![ML Lifecycle](./architecture/ml-lifecycle.png)
