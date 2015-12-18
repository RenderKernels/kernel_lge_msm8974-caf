#
# Makefile for IUCV
#

obj-$(CONFIG_IUCV)	+= iucv.o
obj-$(CONFIG_AFIUCV)	+= af_iucv.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
