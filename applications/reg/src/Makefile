EXEC = reg
OBJS = reg.o

all: $(EXEC)

$(EXEC): $(OBJS)
	$(CC) $(LDFLAGS) -o $@ $(OBJS)

clean:
	-rm -f $(EXEC) *.elf *.gdb *.o

