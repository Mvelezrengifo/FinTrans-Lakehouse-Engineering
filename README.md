💳 FinTrans – Lakehouse en Microsoft Fabric
Proyecto integral de ingeniería de datos financieros implementado en Microsoft Fabric con arquitectura Lakehouse + Spark.

📌 Descripción
Procesa 10.000 transacciones financieras.

Aplica reglas de estandarización y limpieza de datos.

Construye modelos dimensionales y genera tablas analíticas agregadas listas para BI.

🏗️ Flujo de Arquitectura
Código
CSV → Lakehouse → Transformaciones Spark → Modelado Dimensional → Tablas Agregadas
🧹 Procesamiento de Datos
Estandarización de importes negativos.

Creación de indicadores IsCredit e IsDebit.

Conversión de fechas de cadena a tipo fecha.

Validación de canales y tipos de transacción.

📊 Modelado Dimensional
Dimensiones:

dim_date

dim_account

dim_product

Tabla de hechos:

fact_transaction

Este modelo permite análisis financiero escalable y reproducible.

📈 Agregaciones Implementadas
Transacciones totales mensuales.

Importe total de transacciones positivas mensuales.

Top 5 productos más vendidos por importe.

Top 5 cuentas con mayor volumen de transacciones.

Distribución por tipo de transacción.

Distribución por canal.

⚙️ Tecnologías Utilizadas
Microsoft Fabric

Lakehouse Architecture

PySpark

SQL

Modelado Dimensional

✅ Resultado
Se construyó un sistema estructurado de análisis financiero que transforma datos transaccionales crudos en tablas listas para BI, con estandarización, gobernanza y agregaciones estratégicas.

👤 Autor
Mauricio Vélez Rengifo  
Ingeniero de Datos | Desarrollador Backend

GitHub: Mvelezrengifo

LinkedIn: Mauricio Vélez

👉 
