
obj-$(CONFIG_OMFS_FS) += omfs.o

omfs-y := bitmap.o dir.o file.o inode.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
