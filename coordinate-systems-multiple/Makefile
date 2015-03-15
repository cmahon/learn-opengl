CC = g++
LIBS = -lglfw3 -lglew -lSOIL -framework OpenGL
CFLAGS =

coordsystems: coordsystems.o
	$(CC) $(CFLAGS) -o $@ $< $(LIBS)

%.o:%.cpp
	$(CC) $(CFLAGS) -c $<

clean: FORCE
	-rm -f *.o *~ coordsystems *core*

FORCE:
