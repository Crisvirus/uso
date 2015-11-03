CC=gcc
SOURCE=han_solo.c
OBJ=han_solo.o chewie.o
EXE=chewbacca
build:$(EXE)
$(EXE):$(OBJ)
	$(CC) $^ -o $(EXE)
han_solo.o:$(SOURCE)
	$(CC) $< -c
run:$(EXE)
		./$<
clean:han_solo.o $(EXE)
	rm han_solo.o $(EXE)

