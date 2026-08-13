---
title: "GlobalLayerMaskInfo 类"
type: docs
weight: 570
url: /zh/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/
---

**Summary:** The global layer mask section.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.GlobalLayerMaskInfo

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GlobalLayerMaskInfo()](#GlobalLayerMaskInfo__1) | 初始化 GlobalLayerMaskInfo 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alpha_mask | short | 读/写 | 获取或设置 alpha mask。 |
| blue_mask | short | 读/写 | 获取或设置 blue mask。 |
| green_mask | short | 读/写 | 获取或设置 green mask。 |
| kind | byte | 读/写 | 获取或设置 kind。<br/>            0 = 已选择颜色——即反转;<br/>            1 = 受保护颜色;<br/>            128 = 使用每层存储的值。此值为首选。<br/>            其他值用于与 beta 版本的向后兼容。 |
| 长度 | int | r | 获取全局图层蒙版段的字节长度。 |
| opacity | short | 读/写 | 获取或设置全局图层不透明度。0 = 透明，100 = 不透明。 |
| overlay_color_space | short | 读/写 | 获取或设置 overlay color space（未记录的值）。 |
| red_mask | short | 读/写 | 获取或设置 red mask。 |


### Constructor: GlobalLayerMaskInfo() {#GlobalLayerMaskInfo__1}


```
 GlobalLayerMaskInfo() 
```

初始化 GlobalLayerMaskInfo 类的新实例

