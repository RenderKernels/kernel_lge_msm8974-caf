#
# Makefile for the NVIDIA network device drivers.
#

obj-$(CONFIG_FORCEDETH) += forcedeth.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
