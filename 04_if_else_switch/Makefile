CFLAGS = -Wall -Wextra -pedantic -Werror -std=c99 -O2 \
         -Wno-unused-variable -Wno-unused-but-set-variable

.PHONY: all
all: if_else switch

.PHONY: clean
clean:
	$(RM) if_else switch

# `make` has a collection of implicit rules already embedded. One of these
# rules is the same as we have been using in the previous Makefile. Hence we
# can just drop it from this Makefile and rely on the implicit one.
#
# See the manual for a list of implicit rules.
