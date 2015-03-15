CC = g++
LIBS = -lglfw3 -lglew -lSOIL -framework OpenGL
CFLAGS =

transformation: transformation.o
	$(CC) $(CFLAGS) -o $@ $< $(LIBS)

%.o:%.cpp
	$(CC) $(CFLAGS) -c $<

clean: FORCE
	-rm -f *.o *~ transformation *core*

FORCE:
