#
# Makefile for the Exar network device drivers.
#

obj-$(CONFIG_S2IO) += s2io.o
obj-$(CONFIG_VXGE) += vxge/
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
