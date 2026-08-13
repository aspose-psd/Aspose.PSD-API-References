---
title: "GaussWienerFilterOptions 类"
type: docs
weight: 60
url: /zh/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/
---

**Summary:** Gauss Wiener Filter Options<br/>            Deblur gauss

**Module:** [aspose.psd.imagefilters.filteroptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/)

**Full Name:** aspose.psd.imagefilters.filteroptions.GaussWienerFilterOptions

**Inheritance:** DeconvolutionFilterOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions__1) | 初始化一个新的 [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/) 类实例。<br/>            使用默认设置。 |
| [GaussWienerFilterOptions(radius, smooth)](#GaussWienerFilterOptions_radius_smooth_2) | 初始化一个新的 [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| 亮度 | double | 读/写 | 获取或设置亮度。<br/>            推荐范围 1 - 1.5<br/>            默认值 = 1.15 |
| grayscale | bool | r/w | 获取或设置一个值，以指示此 [DeconvolutionFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions/) 是否为灰度。<br/>            返回灰度模式或 RGB 模式。 |
| is_partial_loaded | bool | r | 获取一个值，以指示此实例是否已部分加载。 |
| 半径 | int | 读/写 | 获取或设置半径。 |
| 平滑 | double | 读/写 | 获取或设置平滑。 |
| snr | double | 读/写 | 获取或设置 SNR（信噪比）<br/>            推荐范围 0.002 - 0.009，默认值 = 0.007 |


### Constructor: GaussWienerFilterOptions() {#GaussWienerFilterOptions__1}


```
 GaussWienerFilterOptions() 
```

初始化一个新的 [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/) 类实例。<br/>            使用默认设置。

### Constructor: GaussWienerFilterOptions(radius, smooth) {#GaussWienerFilterOptions_radius_smooth_2}


```
 GaussWienerFilterOptions(radius, smooth) 
```

初始化一个新的 [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/) 类实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 半径 | int | 半径。 |
| 平滑 | double | 平滑。 |

