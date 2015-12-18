#
# Makefile for the Linux Sun Openprom filesystem routines.
#

obj-$(CONFIG_SUN_OPENPROMFS) += openpromfs.o

openpromfs-objs := inode.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
