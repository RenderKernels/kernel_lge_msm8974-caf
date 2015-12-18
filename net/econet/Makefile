#
# Makefile for Econet support code.
#

obj-$(CONFIG_ECONET) += econet.o

econet-y := af_econet.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
