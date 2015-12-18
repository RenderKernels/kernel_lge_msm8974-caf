#
# Makefile for the eHEA ethernet device driver for IBM eServer System p
#
ehea-y = ehea_main.o ehea_phyp.o ehea_qmr.o ehea_ethtool.o ehea_phyp.o
obj-$(CONFIG_EHEA) += ehea.o

ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
