# Cumplimiento Normativo y Ética en el Uso de Datos

## Normativa Asociada

Para este proyecto, se ha utilizado una dataset que cumple con la normativa ISO/IEC 27001. Esta norma internacional establece los requisitos para un Sistema de Gestión de Seguridad de la Información (SGSI) y es relevante para asegurar la protección de datos, la gestión de riesgos de seguridad y la garantía de la confidencialidad, integridad y disponibilidad de la información.

## Uso de Datos y Cumplimiento Normativo

### Uso de Datos

Se eligió esta dataset porque proporciona un conjunto de datos adecuado para el análisis sin comprometer la privacidad y seguridad de la información personal. La dataset, proporcionada por UC Irvine Machine Learning Repository y donada a Bank Marketing el 13/02/2012, está licenciada bajo Creative Commons Attribution 4.0 International (CC BY 4.0). Esta licencia permite el uso y distribución libre de la obra, siempre y cuando se atribuya correctamente al creador original.

### Aseguramiento del Cumplimiento

Para asegurar el cumplimiento con la normativa ISO/IEC 27001, se han tomado las siguientes medidas:

- **Protección de Datos Sensibles:** Se verificó que la dataset no contiene datos sensibles como nombres, direcciones, números de identificación, datos financieros, o cualquier otra información personal que pudiera identificar a un individuo.
- **Controles de Acceso:** Se implementaron controles de acceso adecuados para garantizar que solo personas autorizadas puedan acceder a los datos.
- **Encriptación:** Se encriptaron los datos sensibles cuando era necesario para proteger la información durante su almacenamiento y transmisión.
- **Gestión de Incidentes de Seguridad:** Se establecieron procesos para la gestión adecuada de incidentes de seguridad y se realizan auditorías regulares para garantizar el cumplimiento continuo de las políticas de seguridad.

### Documentos Oficiales

- **ISO/IEC 27001:** [ISO/IEC 27001:2022 - Information security, cybersecurity and privacy protection](https://www.iso.org/standard/82875.html)
- **Creative Commons Attribution 4.0 International (CC BY 4.0):** [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/)

## Análisis de la Herramienta y Cumplimiento Normativo

La herramienta desarrollada utiliza un modelo predictivo de clasificación binaria basado en Random Forest para analizar la dataset. Esta solución cumple con la normativa establecida en la industria de la siguiente manera:

- **Seguridad de Datos:** El modelo Random Forest es una técnica de aprendizaje automático que clasifica datos sin necesidad de manejar datos sensibles directamente, minimizando el riesgo de exposición. Los datos utilizados para entrenar el modelo están adecuadamente anonimizados y procesados de acuerdo con las políticas de protección de datos.
  
- **Transparencia y Responsabilidad:** El modelo Random Forest, al ser un método interpretable, permite verificar cómo se toman las decisiones, asegurando que el análisis sea transparente y que los resultados sean explicables. Esto es esencial para mantener la integridad y confianza en el sistema.
  
- **Prevención de Sesgo Ético:** Se ha realizado un análisis exhaustivo de los datos y del modelo para evitar sesgos que puedan influir negativamente en los resultados. La validación cruzada y la evaluación continua del modelo aseguran que se mantenga justo y equitativo en su clasificación.

## Escenarios de Falta Ética

A pesar de las medidas de seguridad implementadas, se podrían incurrir en faltas éticas bajo los siguientes escenarios:

- **Malicia:** Un usuario malintencionado podría intentar manipular el modelo para obtener resultados deseados, alterar los datos de entrada para sesgar los resultados o utilizar el modelo para fines fraudulentos.
  
- **Negligencia:** Un manejo inadecuado del modelo, como la falta de monitoreo continuo, la no actualización de los datos de entrenamiento, o el uso de datos sin la debida anonimización, podría resultar en la violación de la normativa y en la exposición de datos sensibles.

Para evitar estos escenarios, es crucial seguir las mejores prácticas de seguridad, realizar auditorías periódicas del modelo y capacitar a los usuarios sobre el uso ético y seguro de la herramienta.

## Conclusión

Este proyecto ha sido diseñado para cumplir con la normativa ISO/IEC 27001 y la licencia CC BY 4.0, garantizando el uso ético y responsable de los datos. Se han implementado medidas para proteger la información y evitar cualquier violación de las políticas de seguridad y privacidad.
