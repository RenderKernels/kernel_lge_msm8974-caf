obj-$(CONFIG_HYPERV_NET) += hv_netvsc.o

hv_netvsc-y := netvsc_drv.o netvsc.o rndis_filter.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
