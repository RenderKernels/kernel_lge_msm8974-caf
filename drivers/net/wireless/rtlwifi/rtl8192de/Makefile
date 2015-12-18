rtl8192de-objs :=		\
		dm.o		\
		fw.o		\
		hw.o		\
		led.o		\
		phy.o		\
		rf.o		\
		sw.o		\
		table.o		\
		trx.o

obj-$(CONFIG_RTL8192DE) += rtl8192de.o

ccflags-y += -D__CHECK_ENDIAN__
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
