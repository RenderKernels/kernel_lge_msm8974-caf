#
# Makefile for the linux cramfs routines.
#

obj-$(CONFIG_CRAMFS) += cramfs.o

cramfs-objs := inode.o uncompress.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
