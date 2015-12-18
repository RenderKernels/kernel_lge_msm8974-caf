debugfs-objs	:= inode.o file.o

obj-$(CONFIG_DEBUG_FS)	+= debugfs.o

ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
