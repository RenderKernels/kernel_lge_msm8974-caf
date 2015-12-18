obj-$(CONFIG_OCFS2_FS) += ocfs2_nodemanager.o

ocfs2_nodemanager-objs := heartbeat.o masklog.o sys.o nodemanager.o \
	quorum.o tcp.o netdebug.o ver.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
