#
# Makefile for the filesystem export support routines.

obj-$(CONFIG_EXPORTFS) += exportfs.o

exportfs-objs := expfs.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
