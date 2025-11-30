# Procesador MIPS Pipelined de 5 Etapas con Cifrado César

Este repositorio contiene la implementación de un procesador MIPS (Microprocessor without Interlocked Pipelined Stages) de 32 bits con **pipeline de 5 etapas** (IF, ID, EX, MEM, WB), desarrollado en Verilog.

El proyecto no solo simula la arquitectura MIPS, sino que también implementa una funcionalidad práctica: el **cifrado César**, controlado mediante instrucciones MIPS específicas y gestionado a través de una interfaz gráfica de usuario (GUI) en Python.

## 📖 Descripción del Proyecto

El objetivo principal es doble:

1.  **Simulación Arquitectónica:** Simular el funcionamiento de un procesador RISC segmentado, manejando eficientemente los riesgos de datos (*data hazards* mediante *forwarding*) y riesgos de control (*control hazards*).
2.  **Aplicación Práctica:** Utilizar el procesador para ejecutar una rutina de cifrado César. Las instrucciones se cargan en la memoria de instrucciones del MIPS, y un *frontend* de Python facilita la interacción con el usuario.

## ⚙️ Tecnologías Utilizadas

*   **Lenguaje de Descripción de Hardware:** Verilog
*   **Software de Simulación/Implementación:** [ModelSim] (
*   **Interfaz de Usuario para el decodificador (GUI):** Python 3 con la librería [Tkinter](docs.python.org)

### Instalación

1.  Clona el repositorio en tu máquina local:
    ```bash
    git clone github.com
    ```
Base MIPS assembly script ([ASSEMBLY_SCRIPT] branch) -> Descodificador del conjunto de instrucciones ([MIPS_DECODER] branch) -> Implementación del procesador ([MIPS_PROJECT] branch)
