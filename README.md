# ACTIVIDAD-LAB-3
### Miguel Motta
# Laboratorio de Simulación de Sistemas Cuánticos

**Autor:** Miguel Angel Motta

## Descripción

Este laboratorio simula el primer sistema cuántico descrito en la sección 4.1 de algún material de estudio. El sistema consiste en una partícula confinada a un conjunto discreto de posiciones en una línea. El simulador desarrollado permite especificar el número de posiciones y un vector ket de estado asignando las amplitudes correspondientes.

## Funcionalidades

El sistema ofrece las siguientes funcionalidades:

1. **Cálculo de Probabilidad**: Calcula la probabilidad de encontrar la partícula en una posición particular, dada su función de onda.
   
2. **Cálculo de Probabilidad de Transición**: Si se proporciona otro vector ket, calcula la probabilidad de transitar del primer vector al segundo.

## Código

El código proporcionado en Python para este laboratorio incluye las siguientes funciones:

- `calcular_probabilidad(vector, j)`: Calcula la probabilidad de observar un estado en la posición `j` del vector de estado.
  
- `calcular_probabilidad_transicion(vector_a, j)`: Calcula la probabilidad de transitar del primer vector ket al segundo.

- `main()`: Función principal que realiza pruebas generando 10 vectores de longitud 10 con números complejos aleatorios y prueba las funciones previamente definidas, mostrando los resultados redondeados a dos decimales.

## Uso

Para ejecutar el laboratorio, simplemente ejecuta el script `lab_simulacion_sistemas_cuantico.py`. Asegúrate de tener instalado Python y las bibliotecas necesarias.

```bash
python lab_simulacion_sistemas_cuantico.py
