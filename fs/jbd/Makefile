#
# Makefile for the linux journaling routines.
#

obj-$(CONFIG_JBD) += jbd.o

jbd-objs := transaction.o commit.o recovery.o checkpoint.o revoke.o journal.o
ifdef CONFIG_STRICT_ALIASING
CFLAGS_KERNEL += -fstrict-aliasing
endif
