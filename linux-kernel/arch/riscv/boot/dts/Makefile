# SPDX-License-Identifier: GPL-2.0
ifneq ($(CONFIG_BUILTIN_DTB_SOURCE),"")
obj-$(CONFIG_USE_BUILTIN_DTB) += $(patsubst "%",%,$(CONFIG_BUILTIN_DTB_SOURCE)).dtb.o
else
subdir-y += sifive
subdir-y += kendryte
endif
