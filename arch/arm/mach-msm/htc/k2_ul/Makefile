obj-$(CONFIG_MACH_K2_UL) += board-k2_ul.o
obj-$(CONFIG_MACH_K2_UL) += board-k2_ul-regulator.o
obj-$(CONFIG_MACH_K2_UL) += board-k2_ul-gpiomux.o
obj-$(CONFIG_MACH_K2_UL) += board-k2_ul-storage.o
obj-$(CONFIG_MACH_K2_UL) += board-k2_ul-mmc.o
obj-$(CONFIG_MACH_K2_UL) += board-k2_ul-rfkill.o
obj-$(CONFIG_MACH_K2_UL) += board-k2_ul-wifi.o
obj-$(CONFIG_MACH_K2_UL) += board-k2_ul-gpu.o
# obj-$(CONFIG_MACH_K2_UL) += board-k2_ul-audio.o
obj-$(CONFIG_MACH_K2_UL) += board-k2_ul-pmic.o
obj-$(CONFIG_MACH_K2_UL) += board-k2_ul-keypad.o
ifeq ($(CONFIG_MSM_CAMERA),y)
obj-$(CONFIG_MACH_K2_UL) += board-k2_ul-camera.o
endif
obj-$(CONFIG_MACH_K2_UL) += display/
CFLAGS_board-k2_ul-display.o += -Idrivers/video
