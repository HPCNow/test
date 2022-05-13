
CC=gcc
OPTS=-fopenmp

APPS= hello factorial

all: $(APPS)

hello: hello.c
	$(CC) $(OPTS) -o $@ $<

factorial: factorial.c
	$(CC) $(OPTS) -o $@ $<

clean:
	rm -f $(APPS)
