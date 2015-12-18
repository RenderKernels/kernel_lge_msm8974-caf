
# Makefile for WCNSS triple-play driver

wcnsscore-objs += wcnss_wlan.o qcomwlan_secif.o wcnss_vreg.o

obj-$(CONFIG_WCNSS_CORE) += wcnsscore.o
obj-$(CONFIG_WCNSS_MEM_PRE_ALLOC) += wcnss_prealloc.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
