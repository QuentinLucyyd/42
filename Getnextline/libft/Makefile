#******************************************************************************#
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: sboudouk <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2014/11/10 16:36:53 by sboudouk          #+#    #+#              #
#    Updated: 2014/11/23 20:02:02 by sboudouk         ###   ########.fr        #
#                                                                              #
#******************************************************************************#

NAME = libft.a
CC = gcc
RM = rm -f
CFLAGS = -Wall -Werror -Wextra
DIRSRC = ./
INCLUDES = ./includes/
OBJ = $(SRC:.c=.o)
SRC =	$(DIRSRC)ft_putnbr_fd.c \
		$(DIRSRC)ft_striteri.c \
		$(DIRSRC)ft_strtrim.c \
		$(DIRSRC)ft_strmap.c \
		$(DIRSRC)ft_strmapi.c \
		$(DIRSRC)ft_striter.c \
		$(DIRSRC)ft_memcpy.c \
		$(DIRSRC)ft_putendl_fd.c \
		$(DIRSRC)ft_putstr_fd.c \
		$(DIRSRC)ft_putchar_fd.c \
		$(DIRSRC)ft_itoa.c \
		$(DIRSRC)ft_putnbr.c \
		$(DIRSRC)ft_strnequ.c \
		$(DIRSRC)ft_strequ.c \
		$(DIRSRC)ft_putchar.c \
		$(DIRSRC)ft_putstr.c \
		$(DIRSRC)ft_strlen.c \
		$(DIRSRC)ft_atoi.c \
		$(DIRSRC)ft_strcat.c \
		$(DIRSRC)ft_strncat.c \
		$(DIRSRC)ft_strlcat.c \
		$(DIRSRC)ft_strcmp.c \
		$(DIRSRC)ft_strncmp.c \
		$(DIRSRC)ft_strcpy.c \
		$(DIRSRC)ft_strncpy.c \
		$(DIRSRC)ft_strrchr.c \
		$(DIRSRC)ft_strchr.c \
		$(DIRSRC)ft_strstr.c \
		$(DIRSRC)ft_strnstr.c \
		$(DIRSRC)ft_memset.c \
		$(DIRSRC)ft_memmove.c \
		$(DIRSRC)ft_memccpy.c \
		$(DIRSRC)ft_memchr.c \
		$(DIRSRC)ft_memcmp.c \
		$(DIRSRC)ft_strdup.c \
		$(DIRSRC)ft_bzero.c \
		$(DIRSRC)ft_isalpha.c \
		$(DIRSRC)ft_isdigit.c \
		$(DIRSRC)ft_isalnum.c \
		$(DIRSRC)ft_isascii.c \
		$(DIRSRC)ft_strdel.c \
		$(DIRSRC)ft_isprint.c \
		$(DIRSRC)ft_isspace.c \
		$(DIRSRC)ft_toupper.c \
		$(DIRSRC)ft_tolower.c \
		$(DIRSRC)ft_strnew.c \
		$(DIRSRC)ft_memalloc.c \
		$(DIRSRC)ft_putendl.c \
		$(DIRSRC)ft_memdel.c \
		$(DIRSRC)ft_strclr.c \
		$(DIRSRC)ft_strjoin.c \
		$(DIRSRC)ft_strsplit.c \
		$(DIRSRC)ft_strsub.c

all: $(NAME)

$(NAME): $(OBJ)
	ar rc $(NAME) $(OBJ)
	ranlib $(NAME)

%.o: %.c
	$(CC) -o $@ -c $< $(CFLAGS) -I $(INCLUDES)

clean:
	$(RM) $(OBJ)

fclean: clean
	$(RM) $(NAME)

re: fclean all

.PHONY: re fclean clean all
