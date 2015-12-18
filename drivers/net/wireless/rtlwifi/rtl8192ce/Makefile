rtl8192ce-objs :=		\
		dm.o		\
		hw.o		\
		led.o		\
		phy.o		\
		rf.o		\
		sw.o		\
		table.o		\
		trx.o

obj-$(CONFIG_RTL8192CE) += rtl8192ce.o

ccflags-y += -D__CHECK_ENDIAN__
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
