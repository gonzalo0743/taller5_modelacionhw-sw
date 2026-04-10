# Sistema de Parqueo Inteligente

## Descripción General

El sistema permite gestionar automáticamente los espacios de parqueo disponibles en un estacionamiento. Utiliza sensores para detectar la presencia de vehículos y muestra la disponibilidad en tiempo real.

## Usuario Objetivo

- Conductores que buscan estacionamiento
- Administradores del parqueo

## Entradas

- Sensor ultrasónico (detecta presencia de vehículo)
- Cámara (opcional para reconocimiento de placas)
- Botón de ingreso/salida

Tipo de señal:

- Digital (sensor ultrasónico)
- Analógica (cámara)

## Procesamiento

El sistema procesa la información de los sensores para:

- Determinar si un espacio está ocupado o libre
- Actualizar la base de datos de espacios
- Enviar información a una pantalla o app



## Salidas
- Pantalla LED indicando espacios disponibles
- Aplicación móvil con estado del parqueo
- Barrera automática (abre/cierra)

Tipo de señal:
- Digital (pantalla, barrera)

## Funcionalidades
- Conteo automático de espacios disponibles
- Registro de entradas y salidas
- Visualización en tiempo real

## Tecnologías Propuestas
- Arduino / Raspberry Pi
- Sensores ultrasónicos
- Base de datos (Firebase o similar)

## Posibles mejoras
- Integración con pagos digitales
- Reservación de espacios
- Reconocimiento automático de placas

## Escenarios de uso
1. Un vehículo entra → sensor detecta → sistema reduce espacios disponibles
2. Un vehículo sale → sensor detecta → sistema aumenta espacios disponibles
