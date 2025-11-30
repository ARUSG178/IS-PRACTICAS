# Pregunta 1
### Significa que la carpeta _top_ usa calses, interfaces o funciones las cuales se encuentran defininas en _controllers_; pudiendo ser importaciones, instancias o relacioens como herencia. Esta dependencia no dice que los datos *fluyen automáticamente de _top_ a _controller_*. Si _controllers_ cambia, _top_ podría verse afectado. La flecha punteada indica una dependencia de uso, no necesariamente fuerte ni estructural.

# Pregunta 2
### Tiene un total de seis (6) dependencias con otros paquetes, de las cuales tres (3) son de salida y tres (3) son de entrada. Si se realiza algún cambio en algunos de los paquetes, variaría los efectos. Si algunos de los paquetes cambia: - Si es dependencia de salida:

### - *Si es dependencia de salida* el resultado puede cambiar porque el paquete usa otro. Si ese otro se modifica, el Threads puede fallar.
### - *Si es dependencia de entrada* también puede afectar, porque ahora el paquete es el que provee funcionalidad. Si se cambia Threads, los paquetes que dependen de él podrían quedarse sin lo que necesitan.

# Pregunta 3
### El diagrama muestra un *alto acoplamiento entre los paquetes*, ya que casi *todos dependen de varios otros*. Esto es negativo en términos de modularidad, porque dificulta el mantenimiento y aumenta el riesgo de que cambios en un paquete afecten a muchos otros.


