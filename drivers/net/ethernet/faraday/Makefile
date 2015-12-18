#
# Makefile for the Faraday device drivers.
#

obj-$(CONFIG_FTGMAC100) += ftgmac100.o
obj-$(CONFIG_FTMAC100) += ftmac100.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
