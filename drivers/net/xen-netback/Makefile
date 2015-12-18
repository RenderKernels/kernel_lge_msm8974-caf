obj-$(CONFIG_XEN_NETDEV_BACKEND) := xen-netback.o

xen-netback-y := netback.o xenbus.o interface.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
