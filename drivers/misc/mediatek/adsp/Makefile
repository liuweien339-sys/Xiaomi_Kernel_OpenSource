# SPDX-License-Identifier: GPL-2.0

subdir-ccflags-y += -Wformat

MTK_PLATFORM := mt6873

obj-y += $(MTK_PLATFORM)/

ifeq ($(CONFIG_MACH_MT6785), y)
MTK_ADSP_HW_VER := 0
else ifeq ($(CONFIG_MACH_MT6781), y)
MTK_ADSP_HW_VER := 0
else
MTK_ADSP_HW_VER := 1
endif
subdir-ccflags-y += -DMTK_ADSP_HW_VER=$(MTK_ADSP_HW_VER)

