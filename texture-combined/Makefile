CC = g++
LIBS = -lglfw3 -lglew -lSOIL -framework OpenGL
CFLAGS =

texture: texture.o
	$(CC) $(CFLAGS) -o $@ $< $(LIBS)

%.o:%.cpp
	$(CC) $(CFLAGS) -c $<

clean: FORCE
	-rm -f *.o *~ texture *core*

FORCE:
