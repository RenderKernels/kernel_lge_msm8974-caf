rtl8192cu-objs :=		\
		dm.o		\
		hw.o		\
		led.o		\
		mac.o		\
		phy.o		\
		rf.o		\
		sw.o		\
		table.o		\
		trx.o

obj-$(CONFIG_RTL8192CU) += rtl8192cu.o

ccflags-y += -D__CHECK_ENDIAN__
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
