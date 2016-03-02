SRC	= main.c statistics.c map.c
EXE	= main
CC	= gcc
CFLAGS	= -O0 -g -lm

all:	$(EXE)

$(EXE):	$(SRC)
	$(CC) $(CFLAGS) -o $(EXE) $(SRC)

clean:
	-rm $(EXE)
