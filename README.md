# Sistema de Cálculo Distribuido

Este proyecto implementa un sistema de cálculo distribuido que permite realizar operaciones matemáticas básicas y avanzadas a través de una arquitectura cliente-servidor. El sistema está compuesto por múltiples servidores especializados que trabajan en conjunto para procesar las solicitudes de los clientes.

## Arquitectura del Sistema

El sistema está compuesto por cuatro componentes principales:

1. **Cliente**: Interfaz de usuario que permite enviar solicitudes de cálculo.
2. **Servidor de Cálculo**: Servidor principal que coordina las operaciones y distribuye el trabajo.
3. **Servidor de Operaciones Aritméticas**: Maneja operaciones básicas (suma, resta, multiplicación, división).
4. **Servidor de Operaciones Avanzadas**: Maneja operaciones complejas (potencia, raíz).

## Requisitos

- Python 3.6 o superior
- Conexión de red local (los servidores se ejecutan en localhost por defecto)

## Instalación

1. Clona este repositorio:

bash
git clone [URL_DEL_REPOSITORIO]
cd calculo-distribuido
