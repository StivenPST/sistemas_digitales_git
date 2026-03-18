# SISTEMAS DIGITALES - ARDUINO (HISTORIA, ARQUITECTURA, PERIFICRICOS, ETC.)
## 👨‍💻 Autores
* **Nombres:** Edwin Stiven Pasto Arévalo / Julian Felipe Romero Bocanegra
* **Carrera:** Ingeniería de Sistemas
* **Docente:** Diego Alejandro Barragan Vargas
* **Año:** 2026

## Historia de Arduino
El arduino nacio en el Instituto Interaction Design Institute Ivrea en el año 2005 por un equipo investigativo liberado por Massimo Banzi.

El objetivo era crear una herramienta de bajo costo y de hardware abierto (Open source) para el uso de los estudiante, con el fin de poder manipular dispositivos electronicos, sin necesidad de tener conocimiento de progrmacion compleja.

## Arquitectura, ventajas y funcionalidad.
Es una plataforma basada en un microcontorlador de arquitectuta Harvard, donde la memoria se programa y la memoria de datos tambien se encuentran separada:

## Cerebro (MCU)
El modelo estandar del arduino uno integra ATMEGA328P, es un chip de 8 bits basado en la arquitectura RISC avanzado de AVR.

## Velocidad de reloj

Opera con una frecuencia 16 MHZ, por su diseño puedo ejecutar cerca de 16 MIPS, lo que permite obtener una respuesta de manera inmediata en tiempo real.

## Gestion de memoria
### Flash
Cuenta con una memoria de 32 KB, es una memoria no volatil donde se almacena el codigo del programa sketch 
### SRAM
Cuenta con una memoria de 2KB, es una memoria volatil de acceso rapido donde se guardan las variables y datos temporales del programa en ejecucción.
### EEPROM
Cuenta con una memoria de 1 KB, es la memoria no volatil de lectura/escritura lenta, guarda configuraciones que deben persistir incluso si se desconecta la alimentación.

## Periféricos de Arduino y su uso

### UART (Universal Asynchronous Receiver-Transmitter)
Utiliza los pines 0 (RX) y 1 (TX) es la comunicación de serie basica para cargar codigo desde la PC y el monitor en serie.
### I2C (Inter-Integrated Circuit)
Se encuentra localizado en los pines A4 (SDA) y A5 (SCL), permite conectar hasta 128 dispositivos, usando solo 2 cables de direccionamiento
### SPI (Serial Peripheral Interface)
Ubicado en los pines 10 (SS), 11 (MOSI), 12 (MISO) y 13 (SCK), es un protocolo de velocidad ideal para tarjetas SD, pantallas rápidas o modulos de comunicación inalambrica.

## Ficha técnica, pines de conexión
1. Entrada (Sensores)
Detecta señales del entorno físico.

Digitales: Estados binarios (encendido/apagado), como un pulsador o un sensor PIR.

Analógicas: Valores continuos (0 a 1023), como un potenciómetro o un sensor de temperatura LM35.

2. Procesamiento (Lógica)
El código cargado interpreta las entradas. Utiliza estructuras condicionales (if, switch) y bucles (for, while) para decidir qué acción tomar según los parámetros programados.

3. Salida (Actuadores)
Genera una respuesta física.

Control ON/OFF: Encender luces, activar relés.

Modulación PWM: Controlar la intensidad de un LED o la posición de un servomotor simulando voltajes variables.



---

## 📚 Referencias y Atribuciones
* **Simulación:** 
* **Asistencia Técnica:** La estructura de la documentación y organización del repositorio contó con el apoyo de **Gemini (IA de Google)** para asegurar estándares de documentación profesional.
* **Licencia:** Este proyecto se distribuye bajo fines académicos para la Universidad Compensar.
