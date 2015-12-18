#
# Makefile for the QLogic network device drivers.
#

obj-$(CONFIG_QLA3XXX) += qla3xxx.o
obj-$(CONFIG_QLCNIC) += qlcnic/
obj-$(CONFIG_QLGE) += qlge/
obj-$(CONFIG_NETXEN_NIC) += netxen/
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
