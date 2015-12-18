#
# Makefile for Jasmine adapter
#

obj-$(CONFIG_SERIAL_JSM) += jsm.o

jsm-objs :=    jsm_driver.o jsm_neo.o jsm_tty.o

ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
