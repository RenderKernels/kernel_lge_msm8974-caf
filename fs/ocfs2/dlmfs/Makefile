ccflags-y := -Ifs/ocfs2

obj-$(CONFIG_OCFS2_FS) += ocfs2_dlmfs.o

ocfs2_dlmfs-objs := userdlm.o dlmfs.o dlmfsver.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
