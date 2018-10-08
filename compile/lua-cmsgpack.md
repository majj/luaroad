git clone https://github.com/antirez/lua-cmsgpack.git

cd lua-cmsgpack

gcc -c lua_cmsgpack.c

gcc -o cmsgpack.dll lua_cmsgpack.o  -Wall -O2 -shared lua53.dll

gcc -o cmsgpack.dll lua_cmsgpack.o  -Wall -O2 -shared lua53x64.dll