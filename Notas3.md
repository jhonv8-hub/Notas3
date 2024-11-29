# 1. ¿Qué es un microprocesador?
Un microprocesador es un circuito integrado que actúa como la unidad central de procesamiento (CPU) de un sistema electrónico. Su función principal es interpretar y ejecutar instrucciones de programas almacenados en la memoria. Es el cerebro del sistema, encargado de realizar cálculos, tomar decisiones lógicas y gestionar el flujo de datos.
## 2. Evolución de los Microprocesadores.

### 2.1 Primera Generación (1971-1975): Microprocesadores de 4 y 8 bit.

>🔑*Definición*: Intel 4004 (1971): Primer microprocesador comercial, con una arquitectura de 4 bits y capaz de ejecutar 92,000 instrucciones por segundo. 
![Intel 4004(1971)](https://th.bing.com/th/id/R.d6128581102d4ed751f3c51f04bc96f7?rik=sDdAlpEVCYQG5A&pid=ImgRaw&r=0)

Figura 1. Intel 4004(1971).

#### 2.1.1 Características.
    -Tecnología: PMOS de 10 micrómetros.
    -Velocidad: 740 kHz.
    -Uso: Calculadoras.
### 2.2  Segunda Generación (1976-1980): Microprocesadores de 8 y 16 bits.

>🔑*Definición*: Intel 8080 y Zilog Z80: Usados en los primeros microcomputadores, Motorola 6800: Competidor directo, con mejor capacidad de direccionamiento.

![Intel8080](https://th.bing.com/th/id/R.5732aa9ca7b8d01d14fa0286f65f99d2?rik=c%2b948IkGdvaC4w&pid=ImgRaw&r=0)
Figura 2. Intel8080.
![Zilog Z80](https://th.bing.com/th/id/R.5732aa9ca7b8d01d14fa0286f65f99d2?rik=c%2b948IkGdvaC4w&pid=ImgRaw&r=0)
Figura 3. Zilog Z80.

#### 2.2.1 Características.
    -Tecnología: NMOS de 6 micrómetros.
    -Velocidad: Hasta 2 MHz.
    -Uso: Computadoras personales como el Altair 8800.

### 2.3 Tercera Generación (1981-1990): Microprocesadores de 16 y 32 bits.

>🔑*Definición*: Intel 80286 (1982): Introducción de modos protegidos para multitarea, Intel 80386 (1985): Primer microprocesador de 32 bits.

#### 2.3.1 Características.

    -Soporte para más memoria y multitarea.
    -Tecnología: CMOS de 1.5 micrómetros.
    -Velocidad: Hasta 33 MHz.
    -Uso: Computadoras IBM compatibles.

![Intel 80286](https://th.bing.com/th/id/OIP.JYEyZECO6AOqBNUkMxXQUQHaGn?rs=1&pid=ImgDetMain)

Figura 4. Intel 80286.

### 2.4  Cuarta Generación (1991-2000): Microprocesadores RISC y CISC.

>🔑*Definición*: Intel Pentium (1993): Arquitectura superscalar que permite ejecutar varias instrucciones simultáneamente, Procesadores RISC (Reduced Instruction Set Computing): Menos instrucciones pero más rápidas (ARM, PowerPC).

#### 2.4.1 Características.

    -Tecnología: Submicrón (<1 micrómetro).
    -Velocidad: Hasta 1 GHz.
    -Uso: Computadoras personales y servidores.

![Intel Pentium (1993)](https://th.bing.com/th/id/OIP.Jxqyt3kRUqacwSfN8DE_PgAAAA?rs=1&pid=ImgDetMain)

Figura 5. Intel Pentium (1993).

### 2.5  Quinta Generación (2001-2010): Procesadores Multinúcleo.

>🔑*Definición*: Intel Core 2 Duo, AMD Athlon X2: Primeros procesadores con múltiples núcleos.

#### 2.5.1 Características.

    -Arquitectura de 64 bits.
    -Enfoque en eficiencia energética.
    -Uso: Computadoras portátiles y de escritorio, servidores.
    -Velocidad: Hasta 3 GHz.

![Intel Pentium (1993)](https://th.bing.com/th/id/OIP.Jxqyt3kRUqacwSfN8DE_PgAAAA?rs=1&pid=ImgDetMain)

Figura 6. Intel Pentium (1993).

### 2.6  Sexta Generación (2011-Presente): Procesadores Híbridos y de Alto Rendimiento.

>🔑*Definición*: Intel Core i-Series, AMD Ryzen: Microprocesadores con arquitectura multinúcleo y soporte para virtualización, Procesadores ARM: Dominan en dispositivos móviles y sistemas embebidos.

#### 2.6.1 Características.

    -Tecnologías como Hyper-Threading y Turbo Boost.
    -Fabricación en procesos de 5 nm y menores.
    -Velocidad: >4 GHz y con múltiples núcleos.
    -Uso: Inteligencia artificial, realidad virtual, servidores en la nube.

![Intel core i9 14900k](https://th.bing.com/th/id/OIP.HRzppnLDWPX3LsiNOJI1gQHaFj?rs=1&pid=ImgDetMain)

Figura 6. Intel core i9 14900k.





## 3. Componentes Principales de un Microprocesador.

>🔑*Definición*: Un microprocesador está compuesto por diversos bloques que trabajan en conjunto para ejecutar instrucciones. Cada componente tiene un papel específico en el procesamiento de datos. A continuación, se detallan los componentes esenciales:

### 3.1 Unidad de Control (CU, Control Unit).

#### 3.1.1 Función.

Coordina y dirige todas las operaciones dentro del microprocesador. Interpreta las instrucciones del programa y controla el flujo de datos entre los diferentes componentes.

#### 3.1.2 Tareas.

    -Genera señales de control para activar los circuitos adecuados.
    -Maneja el ciclo de instrucción (fetch, decode, execute).


### 3.2 Unidad Aritmético-Lógica (ALU, Arithmetic Logic Unit).

#### 3.2.1 Función.

Realiza operaciones matemáticas (suma, resta, multiplicación, etc.) y lógicas (AND, OR, NOT, comparaciones).

#### 3.2.2 Tipos de operaciones.

    -Aritméticas: Suma, resta, multiplicación, división.
    -Lógicas: Comparaciones, operaciones bit a bit.

### 3.3 Registros.

#### 3.3.1 Función.

Almacenan temporalmente datos e instrucciones durante el procesamiento. Son memorias pequeñas y rápidas dentro del microprocesador.

#### 3.3.2 Tipos de registros

    -Registro de Instrucción (IR): Guarda la instrucción que se está ejecutando.
    -Contador de Programa (PC): Lleva el control de la dirección de la próxima instrucción.
    -Acumulador (ACC): Almacena resultados intermedios de operaciones realizadas por la ALU.
    -Registros de propósito general: Usados para almacenamiento temporal de datos.

### 3.4 Bus de Datos, Direcciones y Control.

    -Bus de datos: Transfiere los datos entre el microprocesador y otros componentes.
    -Bus de direcciones: Indica la ubicación en la memoria donde se deben leer o escribir datos.
    -Bus de control: Transporta señales de control para coordinar las operaciones.

### 3.5 Memoria Caché.
        
#### 3.5.1 Función.

Almacena datos e instrucciones de uso frecuente para acelerar el acceso y reducir el tiempo de espera.

#### 3.5.2 Tipos.

    -Caché L1: Integrada en el microprocesador, muy rápida y pequeña.
    -Caché L2 y L3: Más grandes, pero ligeramente más lentas.

### 3.6 Unidad de Punto Flotante (FPU, Floating Point Unit).

#### 3.6.1 Función.

Realiza operaciones matemáticas de punto flotante (decimales), esenciales en cálculos complejos como gráficos y simulaciones científicas.

### 3.7 Unidad de Gestión de Memoria (MMU, Memory Management Unit).

#### 3.7.1 Función.

Traduce direcciones virtuales a físicas y controla el acceso a la memoria. Es fundamental en sistemas con memoria virtual.

### 3.8 Reloj del Sistema (Clock).

#### 3.8.1 Función.

Proporciona una señal de sincronización que marca el ritmo de ejecución de las instrucciones. Se mide en hercios (Hz).

### 3.9 Unidades de Entrada/Salida (I/O).

#### 3.9.1 Función.

Gestionan la comunicación entre el microprocesador y los dispositivos periféricos, como discos, pantallas y teclados.

### 3.10 Coprocesadores y Unidades Especializadas.

#### 3.10.1 Función.

Algunos microprocesadores incluyen unidades dedicadas a tareas específicas, como la gestión de gráficos (GPU) o procesamiento de IA.


# 4. Set de instrucciones 

## 4.1 CISC.

>🔑*Definición*: CISC se concibe como una arquitectura que utiliza instrucciones complejas para realizar operaciones en un solo comando. Estas instrucciones pueden realizar varias tareas, como cargar datos, realizar cálculos y almacenarlos en memoria, todo en una sola operación. Esto permite escribir programas más compactos, pero hace que el procesador sea más complejo y consuma más energía. Es común en computadoras de escritorio y servidores.

## 4.2 RISC.

>🔑*Definición*: Por otro lado, RISC es una arquitectura que utiliza un conjunto reducido de instrucciones simples, diseñadas para ejecutarse en un solo ciclo de reloj. Cada instrucción realiza una sola operación básica, como mover datos o realizar cálculos. Esto simplifica el diseño del procesador, haciéndolo más rápido y eficiente en términos de energía. Es común en dispositivos móviles, sistemas embebidos y aplicaciones donde se requiere alta eficiencia energética.

![CISC-RISC](https://www.ahirlabs.com/wp-content/uploads/2018/07/cisc-vs-risc.png)

Figura 7. CISC-RISC.


# 5. Arquitecturas.

## 5.1 Von Neumann.

>🔑*Definición*: La arquitectura de Von Neumann es un modelo de diseño de computadoras donde datos e instrucciones se almacenan en la misma memoria, accediendo a ellos de manera secuencial. Su simplicidad facilita el diseño y la flexibilidad del hardware, permitiendo ejecutar diferentes programas en un mismo sistema. Sin embargo, este enfoque genera un cuello de botella, ya que la CPU y la memoria comparten el mismo bus, lo que limita la velocidad de procesamiento. Es ampliamente usada en computadoras y microprocesadores modernos.

![Von Neumann](https://static.wixstatic.com/media/b9e9b2_95ee7bf623454081859f359ae70676d9.jpg/v1/fill/w_650,h_494,al_c,q_90/b9e9b2_95ee7bf623454081859f359ae70676d9.jpg)

Figura 8. Arquitectura de Von Neumann.


## 5.2 Harvard.

>🔑*Definición*: Es un modelo de diseño de computadoras en el que se separan físicamente las memorias de datos e instrucciones, lo que permite que la CPU acceda a ambas de manera simultánea y sin interferencias. Esto mejora el rendimiento al evitar el cuello de botella de Von Neumann, ya que los buses de datos y de instrucciones son independientes. Esta arquitectura se utiliza comúnmente en sistemas embebidos y dispositivos de alta eficiencia, como microcontroladores, ya que permite un procesamiento más rápido y eficiente.

![Harvard](https://1.bp.blogspot.com/-8R_6HuzelZA/WrVwc88DCLI/AAAAAAAADts/iw1l28xzGgMzZdgpZzjw-2x7xGjMdBTBQCLcBGAs/s1600/arquitectura%252BHarvard.jpg)

Figura 9. Arquitectura de Harvard.

# 6. Memoria. 

## 6.1 Memoria volátil.
### 6.1.1 RAM.
>🔑*Definición*:Almacena datos temporales mientras el sistema está en funcionamiento. Se borra al apagar la computadora.
#### 6.1.1.1 DRAM.
>🔑*Definición*:Más lenta y necesita refrescarse constantemente.
#### 6.1.1.2 SRAM. 
>🔑*Definición*:Más rápida y no necesita refresco, pero es más cara.
## 6.2 Memoria no volátil.
### 6.2.1 ROM.
>🔑*Definición*:Almacena datos permanentes que no se pueden modificar, como el firmware del sistema.
### 6.2.2 PROM.
>🔑*Definición*:Es una memoria de solo lectura que se puede programar una sola vez después de su fabricación, y sus datos no se pueden modificar una vez escritos. Se usa para almacenar información permanente.
### 6.2.3 EPROM.
>🔑*Definición*:Puede borrarse y reprogramarse mediante exposición a luz ultravioleta..
### 6.2.4 EEPROM.
>🔑*Definición*:Puede borrarse y reprogramarse eléctricamente.
### 6.2.5 Flash.
>🔑*Definición*:Usada en dispositivos como USBs, tarjetas SD, y SSDs; rápida y no volátil.
### 6.2.6 NVRAM.
>🔑*Definición*:Es una memoria que conserva los datos incluso cuando se apaga el sistema, combinando la rapidez de la RAM con la persistencia de la memoria no volátil.   

![Memorias](https://4.bp.blogspot.com/-UDHxZGneCHA/V3NJbyVbu0I/AAAAAAAAABs/mn-1QyCzbL4auUu3PLHaXaEF67Llq3_gwCLcB/s1600/MEMO%2B1.jpg)

Figura 10. Memorias.














