obj-$(CONFIG_FCOE) += fcoe.o
obj-$(CONFIG_LIBFCOE) += libfcoe.o

libfcoe-objs := fcoe_ctlr.o fcoe_transport.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
