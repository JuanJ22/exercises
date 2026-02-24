# ⚙️ Ejercicio Assembler: Arquitectura x86 (Irvine32)

Este ejercicio práctico se centra en el uso de la librería **Irvine32** para la manipulación de registros y visualización de datos en consola.

## 📝 Obtendrá 3 puntos si envia capturas de pantalla completas de la ejecución + código y 1.5 si envia unicámente código.
Escribe un programa en ensamblador que realice los siguientes:

1. Capturar desde teclado su nombre, apellido y su correo institucional.
2. Capturar desde teclado 2 valores enteros positivos.
3. Cargar el valor `primerValor` en el registro **EAX**.
4. Sumar `segundoValor` al registro **EAX**.
5. Restar `10h` al resultado.
6. Llamar al procedimiento `DumpRegs` para visualizar el estado final de los registros en la consola.
7. Para finalizar muestre los datos ingresados desde teclado, las operaciones aritméticas y el estado de los registros el formato debe ser el siguiente(Obligatorio):
   
   **Mi nombre es:** JUAN JOSE SANTOS
   
   **Mi correo institucional es:** juan.santos@mail.utec.edu.sv
   
   **El resultado de la suma es:**
   
   **El resultado de la resta es:**
   
   **El estado de los registros es:**   

## 💻 Estructura del Código
Copia esta estructura en tu archivo `.asm` de Notepad++:

```assembly
#Nombre de estudiante:
#Numero de carnet:
INCLUDE Irvine32.inc

.data
    ; (Define variables aquí si es necesario)

.code
main PROC
    ; --- Inicio de tu solución ---
    
    ; --- Fin de tu solución ---

    call DumpRegs ; Muestra los registros en pantalla
    exit
main ENDP
END main
