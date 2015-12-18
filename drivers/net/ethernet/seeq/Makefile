#
# Makefile for the SEEQ network device drivers
#

obj-$(CONFIG_ARM_ETHER3) += ether3.o
obj-$(CONFIG_SEEQ8005) += seeq8005.o
obj-$(CONFIG_SGISEEQ) += sgiseeq.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
