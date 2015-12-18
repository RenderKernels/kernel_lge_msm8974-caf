#
# Makefile for the linux BeOS filesystem routines.
#
 
obj-$(CONFIG_BEFS_FS) += befs.o

befs-objs := datastream.o btree.o super.o inode.o debug.o io.o linuxvfs.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
