#
#Makefile for oppo project info
#
# include $(srctree)/drivers/misc/mediatek/Makefile.custom
#ifdef OPLUS_BUG_STABILITY
#wen.luo@BSP.Kernel.Stability, 2018/12/24,  for enable KASAN, use GCC complile tool, add flag -Wno-misleading-indentation
ifeq ($(CONFIG_KASAN),y)
subdir-ccflags-y += -Wno-format
endif
#endif /*OPLUS_BUG_STABILITY*/

obj-$(CONFIG_OPLUS_FEATURE_OPROJECT) 	+= qcom/oplus_project.o
