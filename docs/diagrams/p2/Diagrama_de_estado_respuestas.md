# RESPUESTAS

## CANTIDAD DE OBJETOS

- Hay tres: Cliente, Procesamiento del Pedido, Realización.

## DISTINTOS ESTADOS DE LOS OBJETOS

- Cliente: Encargar producto, Pagar.
- Procesamiento del Pedido: Validar pedido, Cobrar pago,  
  Dar cervezas a los transportistas, Enviar recibo, Añadir cliente a la lista  
  de satisfechos.
- Realización: Obtener producto, Enviar (urgente / ordinario).

## CANTIDAD DE ACTIVIDADES

- Contando todas las actividades: diez (10).

## BIFURCACIÓN

- Seis (6).

## UNIÓN DE BIFURCACIÓN

- Cuatro (4).

## NODO DE DECISIONES

- Uno (1).

## USO DE PARTICIONES O CARRILES

- Los carriles (swimlanes) organizan las actividades según el propietario del  
  carril (el objeto).

## MOMENTO EN QUE LOS TRANSPORTISTAS RECIBEN LAS CERVEZAS

-- Ocurre después de cobrar el pago y antes de enviar el recibo;
  Forma parte del flujo de Procesamiento del Pedido.

## AÑADIR EL CLIENTE A LA LISTA DE SATISFECHOS Y ENVIAR EL RECIBO

- El cliente se añade a la lista de satisfechos y se envía el recibo de forma simultánea.
