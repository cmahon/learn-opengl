CC = g++
LIBS = -lglfw3 -lglew -framework OpenGL
CFLAGS =

hellotriangle: hellotriangle.o
	$(CC) $(CFLAGS) -o $@ $< $(LIBS)

%.o:%.cpp
	$(CC) $(CFLAGS) -c $<

clean: FORCE
	-rm -f *.o *~ hellotriangle *core*

FORCE:
