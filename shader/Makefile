CC = g++
LIBS = -lglfw3 -lglew -framework OpenGL
CFLAGS =

shader: shader.o
	$(CC) $(CFLAGS) -o $@ $< $(LIBS)

%.o:%.cpp
	$(CC) $(CFLAGS) -c $<

clean: FORCE
	-rm -f *.o *~ shader *core*

FORCE:
