# Proyecto-final-DA---Santiago-Rodriguez
Desarrollo de un sistema de alertas basado en comportamiento de fondos de inversión para implementación de estrategia en un portafolio de inversión simulado.

1. Introducción
El mercado de inversiones se caracteriza por una alta volatilidad, donde las decisiones basadas únicamente en intuición o experiencia pueden ser insuficientes para generar retornos consistentes. En este contexto, los sistemas de análisis cuantitativo y ciencia de datos ofrecen herramientas poderosas para identificar patrones, evaluar riesgos y generar señales de alerta basadas en el comportamiento histórico de activos financieros. Esta propuesta busca desarrollar un sistema automatizado de alertas que permita detectar eventos clave en el comportamiento de fondos de inversión, con el fin de evaluar su impacto potencial en un portafolio de inversión simulado.
2. Objetivo General
Desarrollar un sistema de alertas basado en modelos de análisis del comportamiento histórico de fondos de inversión, que permita informar decisiones dentro de una estrategia de manejo de portafolio de inversión simulado.
3. Objetivos Específicos
•	Integrar en mi estrategia elementos basados en el análisis del histórico de inversiones de Berkshire Hathaway, el holding de Warren Buffett, cuya gestión se distingue por sus excelentes resultados.
•	Recopilar y procesar datos históricos de fondos de inversión.
•	Aplicar técnicas de análisis de series temporales, detección de anomalías y clustering para caracterizar comportamientos relevantes.
•	Diseñar e implementar un sistema de alertas que identifique condiciones críticas, oportunidades o riesgos potenciales.
•	Integrar el sistema con un simulador de portafolio que evalúe el impacto de las alertas en decisiones de compra/venta.
4. Justificación
El desarrollo de sistemas inteligentes de inversión representa una frontera importante para la ciencia de datos aplicada a las finanzas. Esta propuesta combina análisis de datos, modelado predictivo y diseño de sistemas para crear una herramienta que podría ser replicada o adaptada en contextos reales de gestión de activos. El uso de un portafolio simulado permite evaluar resultados sin riesgo financiero directo, pero en condiciones suficientemente realistas.
5. Metodología
•	Etapa 1: Recolección y Limpieza de Datos
o	Bases como Yahoo Finance, dataset en Kaggle, EDGAR - portal del SEC (ente regulador de los mercados financieros de EEUU)
•	Etapa 2: Análisis Exploratorio y Modelado
o	Análisis de correlación, volatilidad, tendencias.
o	Modelos: ARIMA, Prophet, LSTM, clustering K-Means o DBSCAN.
o	Técnicas de detección de anomalías (Isolation Forest, Z-score, etc.).
•	Etapa 3: Desarrollo del Sistema de Alertas
o	Reglas basadas en umbrales dinámicos y comportamientos detectados.
o	Generación de señales: compra, venta, mantener.
•	Etapa 4: Simulación de Portafolio
o	Herramientas como bt, PyPortfolioOpt o simulación personalizada.
o	Evaluación bajo escenarios base y estresados.
•	Etapa 5: Evaluación y Validación
o	Backtesting.
o	Comparación con benchmarks pasivos o estrategias tradicionales.
6. Resultados Esperados
•	Un sistema funcional de generación de alertas.
•	Evaluación del desempeño del sistema en términos de precisión y rentabilidad.
•	Un portafolio simulado que refleje decisiones basadas en alertas generadas automáticamente.
•	Recomendaciones para uso real en entornos de inversión.

