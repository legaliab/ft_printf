# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: alabdull <alabdull@student.42.fr>          +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2022/10/25 02:18:26 by alabdull          #+#    #+#              #
#    Updated: 2022/12/02 00:15:33 by alabdull         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

SRC =	ft_printf.c\
		print_char.c\
		print_uint.c\
		print_str.c\
		print_int.c\
		print_hex.c\
		print_pointer.c\
		ft_putstr.c\
		ft_putchar.c\
		ft_putnbr.c\

OBJ = $(SRC:.c=.o)

CC = gcc

NAME = libftprintf.a

CFLAGS = -Wall -Wextra -Werror

all: $(NAME)

$(NAME): $(OBJ)
	ar -rcs $(NAME) $(OBJ)

clean:
	rm -f $(OBJ)

fclean: clean
	rm -f $(NAME)

re: fclean all

.PHONY: clean fclean all re