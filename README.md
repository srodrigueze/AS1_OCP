# AS1_OCP
Reto Arquitectura de Software - Open/Closed Principle

# Enunciado
Eres un desarrollador de una empresa que está creando un sistema para procesar pagos con diferentes métodos, incluyendo:

- Tarjeta de Crédito
- PayPal
- Transferencia Bancaria

El sistema debe permitir en el futuro agregar nuevos métodos de pago sin modificar el código ya existente.

## Problema Actual
Actualmente, la clase ProcesadorPagos viola el Principio de Abierto/Cerrado, ya que cada vez que se añade un nuevo método de pago, es necesario modificar esta clase, lo que hace que el código sea difícil de mantener y poco escalable.

## Objetivo del Reto
- Refactorizar el código para cumplir con OCP, de manera que se puedan agregar nuevos métodos de pago sin modificar ProcesadorPagos.
- Usar herencia y polimorfismo para que cada método de pago maneje su propia lógica de procesamiento.
