#
# Makefile for the Aeroflex Gaisler network device drivers.
#

obj-$(CONFIG_GRETH) += greth.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
