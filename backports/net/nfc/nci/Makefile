#
# Makefile for the Linux NFC NCI layer.
#

obj-$(CONFIG_BACKPORT_NFC_NCI) += nci.o

nci-objs := core.o data.o lib.o ntf.o rsp.o hci.o

nci-$(CONFIG_BACKPORT_NFC_NCI_SPI) += spi.o
