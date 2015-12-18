
obj-$(CONFIG_WIMAX_I2400M)	+= i2400m/

# (from Sam Ravnborg) force kbuild to create built-in.o
obj- := dummy.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
