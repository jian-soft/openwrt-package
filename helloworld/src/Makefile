TARGET = helloworld
OBJS = helloworld.o

$(TARGET):$(OBJS)
	$(CC) $(LDFLAGS) -o $@ $^
			
%.o: %.c
	$(CC) $(CFLAGS) -c $< -o $@
			
.PHONY: clean
clean:
	rm -f $(TARGET) $(OBJS)
