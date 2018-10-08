
gcc -c lpvm.c lptree.c lpprint.c lpcode.c lpcap.c

gcc -o lpeg.dll lpvm.o lptree.o lpprint.o lpcode.o lpcap.o -Wall -O2 -shared lua53.dll

gcc -o lpeg.dll lpvm.o lptree.o lpprint.o lpcode.o lpcap.o -Wall -O2 -shared lua53x64.dll