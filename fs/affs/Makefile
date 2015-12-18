#
# Makefile for the Linux affs filesystem routines.
#

#ccflags-y := -DDEBUG=1

obj-$(CONFIG_AFFS_FS) += affs.o

affs-objs := super.o namei.o inode.o file.o dir.o amigaffs.o bitmap.o symlink.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
