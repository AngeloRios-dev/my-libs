CC = gcc
CFLAGS = -Wall -Wextra -Werror
LIB = ../libft.a
HEADER = ../libft.h
TESTS = test_ft_isalpha.c \
	test_ft_isdigit.c \
	test_ft_isalnum.c \
	test_ft_isascii.c \
	test_ft_isprint.c \
	test_ft_strlen.c \
	test_ft_memset.c \
	test_ft_bzero.c \
	test_ft_memcpy.c
MAIN = main.c
NAME = test_runner.out

all: $(NAME)

$(NAME): $(MAIN) $(TESTS)
	$(CC) $(CFLAGS) $(MAIN) $(TESTS) $(LIB) -I.. -o $(NAME)

clean:
	rm -f $(NAME)

re: clean all