rtl8192c-common-objs :=		\
		main.o		\
		dm_common.o	\
		fw_common.o	\
		phy_common.o

obj-$(CONFIG_RTL8192C_COMMON) += rtl8192c-common.o

ccflags-y += -D__CHECK_ENDIAN__
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
