CC = gcc
CFLAG = -Wall -Wextra -Werror
NAME = linkedstack

SRCS = linkedstack_main.c linkedstack.c
OBJS = $(SRCS:.c=.o)

$(NAME) : $(OBJS)
	$(CC) $(CFLAG) $(OBJS) -o $(NAME)

clean :
	rm -rf *.o
	rm -rf $(NAME)

