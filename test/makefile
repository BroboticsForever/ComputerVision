CFLAGS = $SHELL(pkg-config --cflags opencv)
LIBS = $SHELL(pkg-config --libs opencv)

displayimage : displayimage.cpp
    g++ $(CFLAGS) $(LIBS) -o $@ $<
