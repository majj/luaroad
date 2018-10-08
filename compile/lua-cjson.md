## cjson

git clone https://github.com/mpx/lua-cjson.git

cd lua-cjson

gcc -c fpconv.c strbuf.c lua_cjson.c

gcc -o cjson.dll lua_cjson.o fpconv.o strbuf.o -Wall -O2 -shared lua53.dll

gcc -o cjson.dll lua_cjson.o fpconv.o strbuf.o -Wall -O2 -shared lua53x64.dll