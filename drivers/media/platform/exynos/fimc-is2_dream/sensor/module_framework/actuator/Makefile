obj-$(CONFIG_CAMERA_ACT_SELECT) += fimc-is-helper-actuator-i2c.o
obj-$(CONFIG_CAMERA_ACT_AK7348_OBJ) += fimc-is-actuator-ak7348.o
obj-$(CONFIG_CAMERA_ACT_AK7345_OBJ) += fimc-is-actuator-ak7345.o
obj-$(CONFIG_CAMERA_ACT_AK7371_OBJ) += fimc-is-actuator-ak7371.o
obj-$(CONFIG_CAMERA_ACT_AK7372_OBJ) += fimc-is-actuator-ak7372.o
obj-$(CONFIG_CAMERA_ACT_DW9714_OBJ) += fimc-is-actuator-dw9714.o
obj-$(CONFIG_CAMERA_ACT_DW9804_OBJ) += fimc-is-actuator-dw9804.o
obj-$(CONFIG_CAMERA_ACT_DW9807_OBJ) += fimc-is-actuator-dw9807.o

EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2_dream
EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2_dream/include
EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2_dream/vendor
EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2_dream/hardware/api
EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2_dream/sensor
EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2_dream/sensor/module_framework
ifeq ($(CONFIG_COMPANION_DIRECT_USE),y)
EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2_dream/vendor/mcd/preprocessor
endif
