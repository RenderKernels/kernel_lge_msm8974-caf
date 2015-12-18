rtl8187-objs		:= dev.o rtl8225.o leds.o rfkill.o

obj-$(CONFIG_RTL8187)	+= rtl8187.o

ccflags-y += -Idrivers/net/wireless/rtl818x
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
