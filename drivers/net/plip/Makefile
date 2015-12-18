#
# Makefile for the PLIP network device drivers.
#

obj-$(CONFIG_PLIP) += plip.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
