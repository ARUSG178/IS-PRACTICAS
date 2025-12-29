# Pregunta 1

Significa que la carpeta `top` usa clases, interfaces o funciones las cuales se
encuentran definidas en `controllers`; pudiendo ser importaciones, instancias o
relaciones como herencia. Esta dependencia no dice que los datos _fluyen
automáticamente de `top` a `controller`_. Si `controllers` cambia, `top` podría
verse afectado. La flecha punteada indica una dependencia de uso, no
necesariamente fuerte ni estructural.

## Pregunta 2

Tiene un total de seis (6) dependencias con otros paquetes, de las cuales tres
(3) son de salida y tres (3) son de entrada. Si se realiza algún cambio en
algunos de los paquetes, variaría los efectos.

Si algunos de los paquetes cambian, puede suceder:

- Si es dependencia de salida: el resultado puede cambiar porque el paquete
  usa otro. Si ese otro se modifica, el componente que lo usa puede fallar.
- Si es dependencia de entrada: también puede afectar, porque ahora el paquete
  es el que provee funcionalidad. Si se cambia ese proveedor, los paquetes
  que dependen de él podrían quedarse sin lo que necesitan.

## Pregunta 3

El diagrama muestra un _alto acoplamiento entre los paquetes_, ya que casi
_todos dependen de varios otros_. Esto es negativo en términos de modularidad,
porque dificulta el mantenimiento y aumenta el riesgo de que cambios en unpaquete afecten a muchos otros.
