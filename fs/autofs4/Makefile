#
# Makefile for the linux autofs-filesystem routines.
#

obj-$(CONFIG_AUTOFS4_FS) += autofs4.o

autofs4-objs := init.o inode.o root.o symlink.o waitq.o expire.o dev-ioctl.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
