CC = g++
LIBS = -lglfw3 -lglew -lSOIL -framework OpenGL
CFLAGS =

camera: camera.o
	$(CC) $(CFLAGS) -o $@ $< $(LIBS)

%.o:%.cpp
	$(CC) $(CFLAGS) -c $<

clean: FORCE
	-rm -f *.o *~ camera *core*

FORCE:
