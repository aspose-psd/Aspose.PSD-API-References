---
title: "IPartialArgb32PixelLoader 类"
type: docs
weight: 1910
url: /zh/python-net/aspose.psd/ipartialargb32pixelloader/
---

**Summary:** Conforms to the 32-bit ARGB pixels loaded partially.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IPartialArgb32PixelLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [process(pixels_rectangle, pixels, start, end)](#process_pixels_rectangle_pixels_start_end_1) | 处理已加载的像素。 |


### Method: process(pixels_rectangle, pixels, start, end) {#process_pixels_rectangle_pixels_start_end_1}


```
 process(pixels_rectangle, pixels, start, end) 
```

处理已加载的像素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pixels_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 像素矩形。 |
| pixels | int | 32 位 ARGB 像素。 |
| start | [Point](/psd/python-net/aspose.psd/point) | 起始像素点。如果不等于 (left,top)，则表示我们拥有的不是完整矩形。 |
| end | [Point](/psd/python-net/aspose.psd/point) | 结束像素点。如果不等于 (right,bottom)，则表示我们拥有的不是完整矩形。 |

