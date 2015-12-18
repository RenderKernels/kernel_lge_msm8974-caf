#
# Makefile for the Linux Bluetooth CMTP layer
#

obj-$(CONFIG_BT_CMTP) += cmtp.o

cmtp-objs := core.o sock.o capi.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
