CC = gcc
CFLAGS = -Wall -Wextra -std=c99

all: add2PB findPhone

add2PB: add2PB.c
	$(CC) $(CFLAGS) -o $@ $^

findPhone: findPhone.c
	$(CC) $(CFLAGS) -o $@ $^

clean:
	rm -f add2PB findPhone