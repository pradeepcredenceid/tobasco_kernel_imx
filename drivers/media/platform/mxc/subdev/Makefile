#Makefile for mxc csi driver

obj-$(CONFIG_VIDEO_MXC_CSI_CAMERA)	+= mx6s_capture.o
obj-$(CONFIG_MXC_MIPI_CSI) += mxc_mipi_csi.o

ov5640_subdev_camera-objs := ov5640.o
obj-$(CONFIG_MXC_CAMERA_SUBDEV_OV5640) += ov5640_subdev_camera.o

ov5640_subdev_camera_mipi-objs := ov5640_mipi.o
obj-$(CONFIG_MXC_CAMERA_SUBDEV_OV5640_MIPI) += ov5640_subdev_camera_mipi.o

ov5642_subdev_camera-objs := ov5642.o
obj-$(CONFIG_MXC_CAMERA_SUBDEV_OV5642) += ov5642_subdev_camera.o

ov5647_subdev_camera_mipi-objs := ov5647_mipi.o
obj-$(CONFIG_MXC_CAMERA_SUBDEV_OV5647_MIPI) += ov5647_subdev_camera_mipi.o

obj-$(CONFIG_MXC_VADC) += mxc_vadc.o
