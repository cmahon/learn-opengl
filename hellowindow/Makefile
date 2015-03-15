CC = g++
LIBS = -lglfw3 -lglew -framework OpenGL
CFLAGS =

hellowindow: hellowindow.o
	$(CC) $(CFLAGS) -o $@ $< $(LIBS)

%.o:%.cpp
	$(CC) $(CFLAGS) -c $<

clean: FORCE
	-rm -f *.o *~ hellowindow *core*

FORCE:
