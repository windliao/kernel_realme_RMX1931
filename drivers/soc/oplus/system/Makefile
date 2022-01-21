# SPDX-License-Identifier: GPL-2.0-only
# Copyright (C) 2018-2020 Oplus. All rights reserved.
#
# Makefile for the OPLUS Linux Kernel system team specific device drivers.
#

obj-y 	+= platform.o
obj-$(CONFIG_OPLUS_FEATURE_OPROJECT) 	+= oplus_project/

ifdef CONFIG_OPLUS_SYSTEM_KERNEL_QCOM
obj-$(CONFIG_OPLUS_FEATURE_PROJECTINFO)	+=  project_info/
endif

#ifdef OPLUS_FEATURE_MM_FEEDBACK
#Zhao.Pan@MULTIMEDIA.AUDIODRIVER.KERNEL, 2020/08/08, Add for multimedia kevent feedback driver
obj-$(CONFIG_OPLUS_FEATURE_MM_FEEDBACK)         += oplus_mm_fb/
#endif /* OPLUS_FEATURE_MM_FEEDBACK */

#ifdef OPLUS_FEATURE_THEIA
#yanggang@BSP.Kernel.Stability,2020/07/08, Add for theia
obj-$(CONFIG_OPLUS_FEATURE_THEIA)     += theia/
#endif /* OPLUS_FEATURE_THEIA */
