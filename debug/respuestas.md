## Respuestas Ompre


# varios bugs.
1. No, no me da toda la informacion si lo corro sin flags 
2. Si pongo -g el compilador da informacion para que el debbuger sepa en que linea paso el error. si pongo -o0 el compilador no realiza ninguna optimización.
3. Si, ‘a’ may be used uninitialized in this function [-Wmaybe-uninitialized]
     a[i] = i;
a podria no esatr inicializada 

# Floating point exception
1. la funcion que requiere el flag -DTRAPFPE es la set_fpe_x87_sse(). podriamos hacer que el programa linkee adecuadamente la square_root.c agregando el flag -lm e incluyendo la libreria math.h dentro del codigo 
2. 

