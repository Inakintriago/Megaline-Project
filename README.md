# 📞 Megaline: Análisis de Tarifas

## 📝 Contexto
Megaline es un operador de telecomunicaciones que ofrece dos planes de prepago: **Surf** y **Ultimate**.  
El objetivo de este proyecto es analizar el comportamiento de 500 clientes a lo largo del 2018 para determinar cuál de las dos tarifas genera mayores ingresos y así optimizar las estrategias comerciales y de publicidad.

## 🛠️ Herramientas Utilizadas
- **Python**: Análisis de datos y modelado estadístico.
- **Pandas** y **NumPy**: Limpieza y transformación de datos.
- **Matplotlib** y **Seaborn**: Visualización de patrones y tendencias.
- **SciPy**: Pruebas estadísticas de hipótesis.
- **Jupyter Notebook**: Documentación del flujo de análisis.

## 📈 Análisis de Resultados
El proyecto se estructuró en varias fases:
1. **Preprocesamiento de datos**:
   - Limpieza de valores atípicos y ausentes.
   - Conversión de unidades de medición (por ejemplo, minutos y megabytes).
   - Fusión de cinco tablas para consolidar la información de clientes, llamadas, mensajes, datos móviles y planes.

2. **Análisis descriptivo**:
   - Cálculo de ingresos mensuales para cada cliente.
   - Comparación gráfica de uso y gastos entre los planes Surf y Ultimate.

3. **Pruebas de hipótesis**:
   - Evaluación estadística para determinar si las diferencias en ingresos entre planes y regiones son significativas.

## 📋 Conclusiones
- El preprocesamiento adecuado permitió un análisis robusto y confiable.
- Las gráficas y estadísticas demostraron que el plan **Surf** genera mayores ingresos para la empresa, principalmente porque muchos usuarios exceden las inclusiones del plan y deben pagar costos adicionales.
- El uso de pruebas de hipótesis brindó soporte estadístico para validar las diferencias observadas, fortaleciendo la recomendación comercial.
- El análisis destaca la importancia de tomar decisiones basadas en datos para optimizar la oferta de servicios y asignar el presupuesto de marketing de manera más efectiva.
