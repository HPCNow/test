
CC=icc
OPTS=-qopenmp

APPS= hello factorial

all: $(APPS)

hello: hello.c
	$(CC) $(OPTS) -o $@ $<

factorial: factorial.c
	$(CC) $(OPTS) -o $@ $<

clean:
	rm -f $(APPS)
