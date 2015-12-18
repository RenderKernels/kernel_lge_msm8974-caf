#
# Makefile for the IPWireless driver
#

obj-$(CONFIG_IPWIRELESS) += ipwireless.o

ipwireless-y := hardware.o main.o network.o tty.o

ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
