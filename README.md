# Proyecto-Islas_de_calor_Colombia
Análisis multiescalar del microclima en el contexto tropical Colombiano
# Descripción 
El proyecto se basa en el analisis de los cambios termicos relacionados con la urbanización, la cobertura vegetal y los pisos térmicos en Colombia. Esto se realizará por medio de modelación matemática, métodos numéricos y por medio de sensores, para obtener la variable de la temperatura y asi aplicar la modelación matemática.
# Problemática de investigación 
El aumento de temperaturas locales, asociado a la pérdida de cobertura vegetal y explotación agro-económica en zonas rurales; está generando cambios en el microclima que afectan el bienestar humano, la producción agrícola y el equilibrio ambiental; en un territorio donde aún falta fortalecer la educación y la gestión comunitaria sobre el valor de áreas verdes.
# Objetivo general 
Estudiar el comportamiento de microclimas con base al uso del suelo en diferentes pisos térmicos, para formar comunidades capaces de leer su entorno, interpretar sus cambios y actuar para transformarlo.
# Desarrollo
Análisis del fenómeno de islas de calor mediante una red de medición participativa que relacione la cobertura vegetal, el nivel de urbanización y el piso térmico; con las variaciones microclimáticas a partir del análisis de puntos focales en estudios cuantitativos y cualitativos.
# Herramientas 
- Sensores
- Github, Git Bash  
- Métodos numéricos
Las anteriores herramientas sirven para mejorar la recolección, visualización y análisis de datos climáticos; incorporando variables territoriales derivadas del uso del suelo, la cobertura vegetal y las prácticas comunitarias de manejo ambiental.
# Métodos utilizados 
- Ecuación diferencial ordinaria lineal de primer orden o modelo de balance térmico: Basada en la ley de enfriamiento de Newton, modificada para incluir variables territoriales como la cobertura vegetal y el nivel de urbanización. El proyecto busca estudiar como cambian las temperaturas según la urbanización, la cobertura vegetal y pisos térmicos, entonces para representar ese comportamiento se utiliza la ecuación diferencial mencionada, donde esta expresa como cambia la temperatura con el tiempo dependiendo de los factores ambientales.
- Método de pasos múltiples (método de Adams - Bashforth): Para resolver la ecuación diferencial, ya que la misma es dificil de resolver analíticamente con datos reales del territorio, por ello, el método permite trabajar con datos reales tomados en campo, aproximar soluciones, entre otros. Además, permite calcular las temperaturas futuras desde los datos, utilizando aproximaciones sucesivas.
- Medición participativa: Donde se va a tomar variables de temperatura y tiempo, para resolver los métodos que se van a utilizar
- Relación con sensor (Sistema Arduino): Este provee los datos reales de temperatura tomados en el sitio, donde los datos funcionan como términos iniciales del modelo, valores para se utilizados en la parte de métodos númericos y validación experiemntal de las simulaciones matemáticas.  
