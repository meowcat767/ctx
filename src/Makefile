CC ?= cc
CFLAGS ?= -Wall -Wextra -pedantic -std=c99

TARGET := ctx
SRC := ctx.c

.PHONY: all clean

all: $(TARGET)

$(TARGET): $(SRC)
	$(CC) $(CFLAGS) $< -o $@

clean:
	rm -f $(TARGET)
