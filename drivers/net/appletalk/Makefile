#
# Makefile for drivers/net/appletalk
#

obj-$(CONFIG_IPDDP) += ipddp.o
obj-$(CONFIG_COPS) += cops.o
obj-$(CONFIG_LTPC) += ltpc.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
