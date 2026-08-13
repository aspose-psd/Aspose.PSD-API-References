---
title: "MotionWienerFilterOptions 类"
type: docs
weight: 90
url: /zh/python-net/aspose.psd.imagefilters.filteroptions/motionwienerfilteroptions/
---

**Summary:** Deconvolution filter options<br/>                deblur motion

**Module:** [aspose.psd.imagefilters.filteroptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/)

**Full Name:** aspose.psd.imagefilters.filteroptions.MotionWienerFilterOptions

**Inheritance:** DeconvolutionFilterOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MotionWienerFilterOptions(length, smooth, angle)](#MotionWienerFilterOptions_length_smooth_angle_1) | 初始化一个新的 [MotionWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/motionwienerfilteroptions/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| 角度 | double | 读/写 | 获取或设置以度为单位的角度。 |
| 亮度 | double | 读/写 | 获取或设置亮度。<br/>            推荐范围 1 - 1.5<br/>            默认值 = 1.15 |
| grayscale | bool | r/w | 获取或设置一个值，以指示此 [DeconvolutionFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions/) 是否为灰度。<br/>            返回灰度模式或 RGB 模式。 |
| is_partial_loaded | bool | r | 获取一个值，以指示此实例是否已部分加载。 |
| 长度 | int | 读/写 | 获取或设置长度。 |
| 平滑 | double | 读/写 | 获取或设置平滑。 |
| snr | double | 读/写 | 获取或设置 SNR（信噪比）<br/>            推荐范围 0.002 - 0.009，默认值 = 0.007 |


### Constructor: MotionWienerFilterOptions(length, smooth, angle) {#MotionWienerFilterOptions_length_smooth_angle_1}


```
 MotionWienerFilterOptions(length, smooth, angle) 
```

初始化一个新的 [MotionWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/motionwienerfilteroptions/) 类实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 长度 | int | 长度。 |
| 平滑 | double | 平滑。 |
| 角度 | double | 角度（以度为单位）。 |

