CC			:= gcc
CFLAGS		:= -g -O2 -Wall -Werror -Wextra
FILES		:= crc.c
OUTPUT		:= $(notdir $(CURDIR))

all:
	$(CC) $(CFLAGS) -o $(OUTPUT) $(FILES)

clean:
	rm -f $(OUTPUT)
