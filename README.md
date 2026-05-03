# Solano-post1-u8

Este laboratorio implementa en lenguaje ensamblador NASM, bajo entorno DOSBox, tres operaciones fundamentales de procesamiento de cadenas en arquitectura x86 de 16 bits: copia de memoria con REP MOVSB/REP MOVSW, búsqueda de caracteres con REPNE SCASB y comparación de cadenas con REPE CMPSB.
Cada rutina demuestra el comportamiento de los registros implícitos SI, DI y CX, así como el flag de dirección DF, que controla si las operaciones avanzan de menor a mayor dirección (CLD) o al revés (STD).

**Programas**

- post1.asm: Copia de cadena con REP MOVSB
- post1b.asm: versión optimizada de pos1.asm con REP MOVSW
- post1c.asm: Búsqueda de carácter con REPNE SCASB
- post1d.asm: Comparación de cadenas con REPE CMPSB

**Compilación y ejecución**

- nasm -f bin post1.asm -o post1.com
- post1.com
- Reemplazar post1 por post1b, post1c, post1d según el programa a ejecutar.
