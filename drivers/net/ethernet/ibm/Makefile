#
# Makefile for th IBM network device drivers.
#

obj-$(CONFIG_IBMVETH) += ibmveth.o
obj-$(CONFIG_IBM_EMAC) += emac/
obj-$(CONFIG_EHEA) += ehea/
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
