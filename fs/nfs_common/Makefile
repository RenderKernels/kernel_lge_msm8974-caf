#
# Makefile for Linux filesystem routines that are shared by client and server.
#

obj-$(CONFIG_NFS_ACL_SUPPORT) += nfs_acl.o

nfs_acl-objs := nfsacl.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
