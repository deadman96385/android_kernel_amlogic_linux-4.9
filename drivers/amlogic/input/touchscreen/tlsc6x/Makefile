#
# Makefile for the input core drivers.
#

# Each configuration option enables a list of files.
KBUILD_CFLAGS += -Wlarger-than=36000
obj-$(CONFIG_AMLOGIC_TOUCHSCREEN_TLSC6X)  += tlsc6x_ts.o
tlsc6x_ts-objs := tlsc6x_main.o
tlsc6x_ts-objs += tlsc6x_comp.o

