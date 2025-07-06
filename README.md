# TelecomX
Análisis de TelecomX
1. Distribución de churn
Aproximadamente el 27% de los clientes abandonan (Churn == "Yes"), el 73% se quedan.

2. Variables categóricas con mayor impacto en churn
Contract: clientes con contratos mensuales (Month-to-month) tienen tasas de churn muy superiores (alrededor del 43%) comparados con contratos anuales (casi 10% o menos).

InternetService: clientes con servicio DSL o fibra óptica abandonan más que los que no tienen internet.

PaymentMethod: pagos por transferencia electrónica o tarjeta de crédito tienden a presentar menos churn que pagos en efectivo o por cheque.

TechSupport y OnlineSecurity: ausencia de estos servicios aumenta la probabilidad de abandono.

Dependents y Partner: clientes sin pareja o dependientes presentan un poco más de churn.

3. Variables numéricas con diferencias notables
tenure (antigüedad en meses): clientes con menor tiempo como usuarios tienen más churn (media de ~15 meses en abandonos vs 40 meses en clientes activos).

MonthlyCharges: clientes que abandonan pagan más en promedio.

Total (TotalCharges): aunque algunos que abandonan tienen cargos totales altos, en promedio tienden a tener menor total, probablemente por ser clientes nuevos.

4. Correlación con churn
tenure correlación negativa moderada (clientes con mayor antigüedad menos churn).

MonthlyCharges correlación positiva baja (más cobranza, más churn).

Total correlación negativa débil (clientes con mayor total tienden a quedarse más).
