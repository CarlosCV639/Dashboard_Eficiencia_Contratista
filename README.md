# Análisis de la Eficiencia y Rendimiento del Contratista

<img width="1050" alt="image" src="https://github.com/user-attachments/assets/9e93f7c3-2093-4164-88a1-9717edb58461" />

# Background del Proyecto

Este proyecto automatiza el procesamiento de datos relacionados con las órdenes de **corte y reconexión** hechas por el contratista, generando un conjunto de datos limpio que se visualizan mediante un dashboard en Power BI.

# Modelado de datos

<img width="602" alt="image" src="https://github.com/user-attachments/assets/83d7814b-25bb-43bc-9684-8705ce82a765" />

El dashboard consiste de las siguientes tablas:

- **Calendario**: Tabla de fechas utilizada para segmentar y analizar los datos por año, día, día de la semana, entre otros.
- **Cx y Rcx**: Tabla principal que contiene los registros de cortes y reconexiones en el periodo establecido, incluyendo datos clave como acción realizada, efectividad y operador.
- **Tiempo**: Muestra los tiempos mínimos, máximos y promedios entre ejecuciones por operador y día.
- **Operadores**: Contiene metadatos de los operadores.

# Hallazgos clave

- De las 24,634 órdenes emitidas, solo el 36% fueron efectivas.
- El rendimiento de los operadores varía desde un 92% (Operador 33) hasta un 65%, mostrando disparidades importantes que deben optimizarse.
- Un 48% de las órdenes no fueron visitadas, lo que representó una oportunidad clara de mejora en la asignación o seguimiento operativo.
- La mayor cantidad de órdenes de corte atendidas se concentran entre las 8:00 a.m. y 12:00 p.m., con un pico de 2.6 mil órdenes/hora.
- Algunos operadores presentan tiempos máximos de inactividad de más de 4 horas, lo cual podría indicar problemas de planificación, zonas asignadas mal distribuidas o tiempos muertos no productivos.

# Conclusión

Este análisis demuestra el valor de integrar automatización en Python con herramientas de visualización como Power BI para monitorear y mejorar operaciones de campo como cortes y reconexiones de suministro. A través del procesamiento y modelado de datos se logró:

- Identificar cuellos de botella en tiempos de atención.
- Medir el rendimiento de operadores con datos objetivos.
- Detectar ineficiencias en la asignación y cumplimiento de órdenes.
- Facilitar decisiones basadas en datos mediante visualizaciones dinámicas.


