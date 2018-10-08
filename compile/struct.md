
gcc -c struct.c

gcc -o struct.dll struct.o -Wall -O2 -shared lua53.dll

gcc -o sttuct.dll struct.o -Wall -O2 -shared lua53x64.dll