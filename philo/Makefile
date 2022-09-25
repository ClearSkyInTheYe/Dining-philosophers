# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: chfederi <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2022/06/11 22:21:05 by chfederi          #+#    #+#              #
#    Updated: 2022/06/11 22:21:07 by chfederi         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = philo

SRCS = init.c philo.c run.c utils.c utils1.c

OBJS =  $(SRCS:.c=.o)

HEADER = philo.h

CFLAGS = -Wall -Wextra -Werror

CC = cc

all: $(NAME)

 $(NAME): $(OBJS)
	$(CC) $(CFLAGS) $(OBJS) -o $(NAME)

$(OBJS): philo.h Makefile

clean:
	rm -f $(OBJS)

fclean: clean
	rm -f $(NAME)

re: fclean all
