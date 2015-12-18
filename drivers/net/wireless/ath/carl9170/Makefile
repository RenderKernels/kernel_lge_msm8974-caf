carl9170-objs := main.o usb.o cmd.o mac.o phy.o led.o fw.o tx.o rx.o
carl9170-$(CONFIG_CARL9170_DEBUGFS) += debug.o

obj-$(CONFIG_CARL9170) += carl9170.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
