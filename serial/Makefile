CPP=CC
CPPFLAGS= -Minfo=all -fast -mp

LD=$(CPP)
LFLAGS=$(CPPFLAGS)

.PHONY: clean

run:  main.o
	$(LD) main.o -o run $(LFLAGS)

main.o: main.cpp
	$(CPP) $(CPPFLAGS) -c main.cpp

clean:
	rm -f *.o run
