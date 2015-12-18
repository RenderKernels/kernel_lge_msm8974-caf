#
# Makefile for the linux efs-filesystem routines.
#

obj-$(CONFIG_EFS_FS) += efs.o

efs-objs := super.o inode.o namei.o dir.o file.o symlink.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
