obj-$(CONFIG_CAMERA_FLASH_LM3560_OBJ) += fimc-is-flash-lm3560.o
obj-$(CONFIG_CAMERA_FLASH_RT5033_OBJ) += fimc-is-flash-rt5033.o
obj-$(CONFIG_CAMERA_FLASH_S2MPB02_OBJ) += fimc-is-flash-s2mpb02.o
obj-$(CONFIG_CAMERA_FLASH_GPIO_OBJ) += fimc-is-flash-gpio.o
obj-$(CONFIG_CAMERA_FLASH_I2C_OBJ) += fimc-is-helper-flash-i2c.o \
				      fimc-is-flash-i2c.o

EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2_dream
EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2_dream/include
EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2_dream/vendor
EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2_dream/hardware/api
EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2_dream/sensor/module_framework
EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2_dream/sensor
ifeq ($(CONFIG_COMPANION_DIRECT_USE),y)
EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2_dream/vendor/mcd/preprocessor
endif
