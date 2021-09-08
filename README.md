# C y C++

camando para cmake y visual studio 2017

    cmake -G "Visual Studio 15 2017" -S . -B build

para visual studio 2013

    cmake -G "Visual Studio 12 2013" -S . -B build


## Añadir MinGW al path

    setx /M path "%path%;C:\MinGW\bin;C:\MinGW\msys\1.0\bin;"
