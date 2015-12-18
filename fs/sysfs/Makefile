#
# Makefile for the sysfs virtual filesystem
#

obj-y		:= inode.o file.o dir.o symlink.o mount.o bin.o \
		   group.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
