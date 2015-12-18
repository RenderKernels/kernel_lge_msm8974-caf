obj-$(CONFIG_SCSI_IBMVSCSI)	+= ibmvscsic.o

ibmvscsic-y			+= ibmvscsi.o
ibmvscsic-$(CONFIG_PPC_PSERIES)	+= rpa_vscsi.o 

obj-$(CONFIG_SCSI_IBMVSCSIS)	+= ibmvstgt.o
obj-$(CONFIG_SCSI_IBMVFC)	+= ibmvfc.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
