# Copyright (c) 2013 The Linux Foundation. All rights reserved.
#
include $(TOPDIR)/rules.mk

ARCH:=arm
BOARD:=ipq806x
BOARDNAME:=Qualcomm Atheros IPQ806X
FEATURES:=squashfs
CPU_TYPE:=cortex-a7
MAINTAINER:=John Crispin <blogic@openwrt.org>

KERNEL_PATCHVER:=3.4

KERNELNAME:=zImage Image uImage

include $(INCLUDE_DIR)/target.mk
DEFAULT_PACKAGES += \
	kmod-leds-gpio kmod-gpio-button-hotplug swconfig \
	kmod-ata-core kmod-ata-ahci kmod-ata-ahci-platform kmod-ata-ahci-msm


$(eval $(call BuildTarget))
