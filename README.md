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
git clone https://github.com/DereKk8/Taller1_Distribuidos.git
cd calculo-distribuido

## Uso

El sistema requiere iniciar múltiples componentes en diferentes terminales. Sigue estos pasos en orden:

1. **Inicia el Servidor de Cálculo**:
   
bash
python main.py servidor_calculo

O en su defecto 

bash
python3 main.py servidor_calculo

2. **Inicia el Servidor de Operaciones Aritméticas**:

bash
python main.py servidor_op1

O en su defecto 

bash
python3 main.py servidor_op1

3. **Inicia el Servidor de Operaciones Avanzadas**:
   
bash
python main.py servidor_op2

O en su defecto 

bash
python3 main.py servidor_op2

4. **Inicia el Cliente**:
   
bash
python main.py cliente

O en su defecto 

bash
python3 main.py cliente


### Operaciones Disponibles

#### Operaciones Aritméticas (Servidor 1)
- `suma`: Suma dos o más números
- `resta`: Resta dos o más números
- `multiplicacion`: Multiplica dos o más números
- `division`: Divide dos números

#### Operaciones Avanzadas (Servidor 2)
- `potencia`: Calcula la potencia de un número
- `raiz`: Calcula la raíz de un número
- `calculo_complejo`: Realiza cálculos que combinan operaciones básicas y avanzadas

### Ejemplo de Uso
1. Inicia el cliente
2. Selecciona una operación
3. Ingresa los operandos separados por espacios
4. Observa el resultado

Cliente de cálculo distribuido
Operaciones disponibles: suma, resta, multiplicacion, division, potencia, raiz
Operación: suma
Operandos: 5 3 2
Resultado: 10
Tiempo de procesamiento: 0.0123 segundos


## Estructura del Proyecto
calculo-distribuido/
├── main.py # Punto de entrada principal
├── cliente.py # Implementación del cliente
├── servidor_calculo.py # Servidor principal de coordinación
├── servidor_operacion1.py # Servidor de operaciones aritméticas
├── servidor_operacion2.py # Servidor de operaciones avanzadas
└── README.md # Este archivo


## Características

- Procesamiento distribuido de operaciones matemáticas
- Manejo de errores robusto
- Logging detallado de operaciones
- Tiempo de procesamiento para cada operación
- Soporte para operaciones complejas que combinan múltiples cálculos

## Configuración

Los servidores utilizan las siguientes configuraciones por defecto:
- Servidor de Cálculo: `localhost:5000`
- Servidor Aritmético: `localhost:5001`
- Servidor Avanzado: `localhost:5002`

Para modificar estas configuraciones, puedes editar los parámetros en los respectivos archivos de servidor.

Link del proyecto: [https://github.com/tuusuario/calculo-distribuido](https://github.com/DereKk8/calculo-distribuido)
