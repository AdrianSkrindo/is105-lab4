# is105-lab4
For å kompilere
```
gcc readfile.c -o readfile
```
Filene vil ikke kompilere på alle platformer. Dere må legge inn henvisning til kodebiblioteker som inneholder kildekode for systemkallene, for eksempel
```
#include <stdio.h>
#include <stdlib.h>
#include <unistd.h>
#include <fcntl.h>
```
