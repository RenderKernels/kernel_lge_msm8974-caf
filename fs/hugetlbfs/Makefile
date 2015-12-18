#
# Makefile for the linux ramfs routines.
#

obj-$(CONFIG_HUGETLBFS) += hugetlbfs.o

hugetlbfs-objs := inode.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
