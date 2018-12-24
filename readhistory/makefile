TARGET  := readhistory.exe
INCS = -I ../network -I ../utils
LIBS = -L ../utils -lutils -L ../network -lnetwork -Wl,-Bstatic -ljansson -lmpdec -lz -lhiredis -Wl,-Bdynamic -lm -lpthread -ldl -lev -lmysqlclient
include ../makefile.inc
