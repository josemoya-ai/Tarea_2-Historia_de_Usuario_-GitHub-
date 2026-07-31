# Casos de Prueba - Historia de Usuario 05
## HU-05: Realizar pedido

---

# TC-009 - Pedido realizado correctamente

## Objetivo
Verificar que un usuario pueda confirmar un pedido.

## Precondiciones
- Usuario autenticado.
- Carrito con productos.

## Datos de prueba
Método de pago: Tarjeta (simulado).

## Pasos
1. Abrir el carrito.
2. Revisar el resumen.
3. Seleccionar el método de pago.
4. Confirmar el pedido.

## Resultado esperado
El sistema genera un número de orden, confirma el pedido y lo guarda en el historial.

## Resultado obtenido
Pendiente.

## Estado
Pendiente.

## Notas / Evidencias
Pendiente.

---

# TC-010 - Intentar confirmar pedido sin método de pago

## Objetivo
Verificar que el sistema solicite un método de pago antes de confirmar el pedido.

## Precondiciones
- Usuario autenticado.
- Carrito con productos.

## Datos de prueba
Sin método de pago.

## Pasos
1. Abrir el carrito.
2. Presionar "Confirmar pedido" sin seleccionar un método de pago.

## Resultado esperado
El sistema informa que debe seleccionarse un método de pago y no genera la orden.

## Resultado obtenido
Pendiente.

## Estado
Pendiente.

## Notas / Evidencias
Pendiente.