NAME = libft.a
SRC = ft_atoi.c ft_isprint.c ft_memalloc.c ft_putchar.c ft_strchr.c\
ft_strjoin.c ft_strnew.c ft_bzero.c ft_itoa.c ft_memccpy.c ft_putchar_fd.c\
ft_strclr.c ft_strlcat.c ft_strnstr.c ft_countwords.c ft_longlen.c ft_memchr.c\
ft_putendl.c ft_strcmp.c ft_strlen.c ft_strrchr.c ft_del.c ft_lstadd.c\
ft_memcmp.c ft_putendl_fd.c ft_strcpy.c ft_strmap.c ft_strsplit.c\
ft_free_arr.c ft_lstdel.c ft_memcpy.c ft_putnbr.c ft_strdel.c ft_strmapi.c\
ft_strstr.c ft_isalnum.c ft_lstdelone.c ft_memdel.c ft_putnbr_fd.c ft_strdup.c\
ft_strncat.c ft_strsub.c ft_isalpha.c ft_lstiter.c ft_memmove.c ft_putstr.c\
ft_strequ.c ft_strncmp.c ft_strtrim.c ft_isascii.c ft_lstmap.c ft_memset.c\
ft_putstr_fd.c ft_striter.c ft_strncpy.c ft_tolower.c ft_isdigit.c ft_lstnew.c\
ft_primenbr.c ft_strcat.c ft_striteri.c ft_strnequ.c ft_toupper.c
WRNG = -Wall -Werror -Wextra

.PHONY: all clean fclean re

all: $(NAME)

$(NAME):
	gcc $(WRNG) -c $(SRC)
	ar rc $(NAME) *.o
	ranlib $(NAME)

clean:
	/bin/rm -f *.o

fclean: clean
	/bin/rm -f $(NAME)

re: fclean all
