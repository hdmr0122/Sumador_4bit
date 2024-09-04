**Funciones y Usos del Sumador de 4 Bits**:
Suma de Números Binarios: El sumador de 4 bits puede sumar dos números binarios de 4 bits, produciendo un resultado de 4 bits y un bit adicional de acarreo (carry-out) si la suma excede el valor máximo de 4 bits (15 en decimal).

**Cálculo Aritmético en Microprocesadores**: Es un componente esencial en las Unidades Aritmético-Lógicas (ALU) de los microprocesadores, donde se realizan operaciones aritméticas como sumas, restas (al utilizar sumadores y complementos a 2), e incluso multiplicaciones básicas.

**Circuitos de Control y Procesamiento de Señales**: Los sumadores de 4 bits se utilizan en una variedad de circuitos digitales como temporizadores, contadores y controladores donde se necesita manipular o procesar números.

Operaciones de Incremento y Decremento: En contadores digitales, un sumador de 4 bits puede ser usado para incrementar o decrementar valores en pasos específicos.

**Diseño de Sistemas Digitales**: En sistemas más grandes, como los sumadores de 8, 16 o más bits, se pueden construir uniendo varios sumadores de 4 bits, lo que hace que estos sumadores sean bloques básicos de construcción.

**Funcionamiento Básico**:
Entradas: Dos números de 4 bits (A y B) y un bit de acarreo de entrada (Carry-in).
Salidas: Un número de 4 bits (Suma) y un bit de acarreo de salida (Carry-out).
Cada bit de los números de entrada se suma en un bloque de sumador llamado "full adder", que también maneja el acarreo de los bits anteriores, asegurando que el cálculo aritmético sea correcto.
