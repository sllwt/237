# SPDX-License-Identifier: GPL-2.0-only
#
# Copyright (C) 2016 OpenWrt.org

include $(TOPDIR)/rules.mk

ARCH:=arc
CPU_TYPE:=archs
BOARD:=archs38
BOARDNAME:=Synopsys DesignWare ARC HS38
MAINTAINER:=Alexey Brodkin <abrodkin@synopsys.com>
SUBTARGETS:=generic

KERNEL_PATCHVER:=5.10

DEVICE_TYPE:=developerboard

define Target/Description
	Synopsys DesignWare boards
endef

include $(INCLUDE_DIR)/target.mk

$(eval $(call BuildTarget))
