obj-$(CONFIG_FSNOTIFY)		+= fsnotify.o notification.o group.o inode_mark.o \
				   mark.o vfsmount_mark.o

obj-y			+= dnotify/
obj-y			+= inotify/
obj-y			+= fanotify/
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
