## Requisitos

 * OpenCV 2.4
 * Boost C++

## Compilación

Para compilar el programa en necesario tener instalado el SDK de Blackmagic
DeckLink. El proyecto de Eclipse espera que la ruta del SDK sea:

    /opt/Blackmagic\ DeckLink\ SDK\ 9.7.1
    
por lo que puede ser necesario reconfigurar la ruta del compilador de C++ a
los ficheros de cabecera si el SDK ha sido instalado en un directorio
diferente.

Además el proyecto incluye una referencia al recurso externo
`DeckLinkAPIDispatch.cpp` que debe haber sido instalado en el mismo directorio
que los archivos de cabecera del SDK. Obviamente si el SDK se ha instalado en
una ubicación diferente, la ruta de dicho recurso externo debe ser actualizada.

-- Jesús Torres <jmtorres@ull.es> 