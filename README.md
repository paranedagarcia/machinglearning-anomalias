# Maching Learning - anomalias
Detección de anomalias con iforest.
Basado en un dataset que contiene mediciones del consumo de energía eléctrica en un hogar con una tasa de muestreo de un minuto durante un período de casi 4 años. Están disponibles diferentes magnitudes eléctricas y algunos valores de submedición.

**Dataset**: https://patricioaraneda.cl/public_data/household_power_consumption.txt

Información de atributos:

dt: Fecha en formato dd/mm/aaaa hh:mm:ss
Global_active_power: potencia activa global promediada por minuto del hogar (en kilovatios)
Global_reactive_power: potencia reactiva global media por minuto del hogar (en kilovatios)
voltage: voltaje medio por minuto (en voltios)
Global_intensity: intensidad de corriente promediada por minutos global del hogar (en amperios)
Sub_metering_1: submedición de energía nº 1 (en vatios-hora de energía activa). Corresponde a la cocina, que contiene principalmente un lavavajillas, un horno y un microondas (las placas no son eléctricas sino de gas).
Sub_metering_2: submedición de energía nº 2 (en vatios-hora de energía activa). Corresponde al lavadero, que contiene una lavadora, una secadora, un frigorífico y una luz.
Sub_metering_3: submedición de energía nº 3 (en vatios-hora de energía activa). Corresponde a un calentador de agua eléctrico y a un aire acondicionado.
