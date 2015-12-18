#
# Makefile for the pNFS block layout driver kernel module
#
obj-$(CONFIG_PNFS_BLOCK) += blocklayoutdriver.o
blocklayoutdriver-objs := blocklayout.o extents.o blocklayoutdev.o blocklayoutdm.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
