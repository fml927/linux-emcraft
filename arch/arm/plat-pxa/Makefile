#
# Makefile for code common across different PXA processor families
#

obj-y	:= dma.o pmu.o

obj-$(CONFIG_GENERIC_GPIO)	+= gpio.o
obj-$(CONFIG_PXA3xx)		+= mfp.o
obj-$(CONFIG_ARCH_MMP)		+= mfp.o

obj-$(CONFIG_HAVE_PWM)		+= pwm.o
