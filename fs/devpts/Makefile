#
# Makefile for the Linux /dev/pts virtual filesystem.
#

obj-$(CONFIG_UNIX98_PTYS)		+= devpts.o

devpts-$(CONFIG_UNIX98_PTYS)		:= inode.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
