TARGET  := el_http.exe
INCS = -I ../network -I ../utils
LIBS = -L ../utils -lutils -L ../network -lnetwork -Wl,-Bstatic -lev -ljansson -lmpdec -lrdkafka -lz -lssl -lcrypto -Wl,-Bdynamic -lm -lpthread -ldl
include ../makefile.inc
