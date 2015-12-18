#
# Makefile for the Microchip network device drivers.
#

obj-$(CONFIG_ENC28J60) += enc28j60.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
