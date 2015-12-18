#
# Makefile for the Linux WAN router layer.
#

obj-$(CONFIG_WAN_ROUTER) += wanrouter.o

wanrouter-y :=  wanproc.o wanmain.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
