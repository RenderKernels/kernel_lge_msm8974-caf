#
# Makefile for the Linux FDDI network device drivers.
#

obj-$(CONFIG_DEFXX) += defxx.o
obj-$(CONFIG_SKFP) += skfp/
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
