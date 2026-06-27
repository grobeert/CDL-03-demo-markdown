CFLAGS = -Wall -Wextra 

.PHONY: all check test clean

all: helloword.c

helloword: helloword.c

check:
	cpplint helloword.c

clean:
	-rm -f helloword
	-rm -f *~

test: helloword
	./test.sh
