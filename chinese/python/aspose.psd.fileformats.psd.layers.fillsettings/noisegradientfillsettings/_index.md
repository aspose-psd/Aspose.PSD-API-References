---
title: "NoiseGradientFillSettings 类"
type: docs
weight: 120
url: /zh/python-net/aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings/
---

**Summary:** Noise gradient definition class.

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.NoiseGradientFillSettings

**Inheritance:** IFillSettings, IGradientFillSettings, BaseGradientFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [NoiseGradientFillSettings()](#NoiseGradientFillSettings__1) | 初始化一个新的 [NoiseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| align_with_layer | bool | 读/写 | 获取或设置一个值，指示是否 [align with layer]。 |
| 角度 | double | 读/写 | 获取或设置角度。 |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | 获取或设置颜色。 |
| color_model | [NoiseColorModel](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/noisecolormodel/) | r/w | 颜色模型 - RGB/HSB/LAB (3/4/6)。 |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | 获取或设置颜色点。 |
| dither | bool | r/w | 获取或设置一个值，指示此 [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) 是否抖动。 |
| expansion_count | short | 读/写 | 扩展计数 ( = 2 for Photoshop 6.0)。 |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | 填充类型。 |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r | 获取此渐变的模式。<br/>            确定 'Gradient Type' = 'Solid/Noise' (0/1)。 |
| gradient_name | 字符串 | 读/写 | 获取或设置渐变的名称。 |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype) | r/w | 获取或设置渐变的类型。 |
| horizontal_offset | double | 读/写 | 获取或设置水平偏移（百分比）。 |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | PixelDataFormat 的最大颜色。 |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | PixelDataFormat 的最小颜色。 |
| reverse | bool | r/w | 获取或设置一个值，指示此 [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) 是否反向。 |
| rnd_number_seed | int | 读/写 | 用于为噪声渐变生成颜色的随机数种子 |
| roughness | int | 读/写 | 粗糙度因子。 |
| scale | int | 读/写 | 获取或设置比例。 |
| show_transparency | bool | 读/写 | 显示透明度的标志。 |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | r/w | 获取或设置透明度点。 |
| use_vector_color | bool | 读/写 | 使用矢量颜色的标志。 |
| vertical_offset | double | 读/写 | 获取或设置垂直偏移（百分比）。 |


### Constructor: NoiseGradientFillSettings() {#NoiseGradientFillSettings__1}


```
 NoiseGradientFillSettings() 
```

初始化一个新的 [NoiseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings/) 类实例。

