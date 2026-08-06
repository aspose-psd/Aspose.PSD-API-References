---
title: "ColorPaletteHelper"
second_title: "Aspose.PSD 的 Java API 参考"
description: "用于颜色调色板操作的辅助类。"
type: docs
weight: 28
url: /zh/java/com.aspose.psd/colorpalettehelper/
---

**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

用于颜色调色板操作的辅助类。
## Methods

| Method | 描述 |
| --- | --- |
| [create4Bit()](#create4Bit--) | 创建 4 位颜色调色板。 |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | 创建 4 位灰度调色板。 |
| [create8Bit()](#create8Bit--) | 创建 8 位颜色调色板。 |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | 创建 8 位灰度调色板。 |
| [createMonochrome()](#createMonochrome--) | 创建仅包含 2 种颜色的单色颜色调色板。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-) | 在图像没有调色板的情况下，从栅格图像获取颜色调色板（对图像进行调色）。 |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-) | 在图像没有调色板的情况下，从栅格图像获取颜色调色板（对图像进行调色）。 |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-int-) | 在图像没有调色板的情况下，从栅格图像获取颜色调色板（对图像进行调色）。 |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.psd.RasterImage-) | 获取 256 色调色板，由初始图像颜色值的高位组成。 |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.psd.RasterImage-) | 获取均匀的 256 色调色板。 |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.psd.IColorPalette-) | 确定指定的调色板是否具有透明颜色。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create4Bit() {#create4Bit--}
```
public static IColorPalette create4Bit()
```


创建 4 位颜色调色板。

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


创建 4 位灰度调色板。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| minIsWhite | boolean | 如果设置为 true，调色板以白色开始；否则以黑色开始。 |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


创建 8 位颜色调色板。

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


创建 8 位灰度调色板。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| minIsWhite | boolean | 如果设置为 true，调色板以白色开始；否则以黑色开始。 |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit grayscale palette.
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


创建仅包含 2 种颜色的单色颜色调色板。

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Color palette for monochrome images.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)
```


在图像没有调色板的情况下，从栅格图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则直接使用它，而不进行计算。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | 光栅图像。 |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | 目标图像的边界。 |
| entriesCount | int | 所需的条目计数。 |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


在图像没有调色板的情况下，从栅格图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则直接使用它，而不进行计算。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | 光栅图像。 |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | 目标图像的边界。 |
| entriesCount | int | 所需的条目计数。 |
| useImagePalette | boolean | 如果设置，它将在可用时使用自己的图像调色板 |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount)
```


在图像没有调色板的情况下，从栅格图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则直接使用它，而不进行计算。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | 光栅图像。 |
| entriesCount | int | 所需的条目计数。 |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


获取 256 色调色板，由初始图像颜色值的高位组成。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | 图像。 |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


获取均匀的 256 色调色板。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | 图像。 |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.psd.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


确定指定的调色板是否具有透明颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 调色板。 |

**Returns:**
布尔型 -  true  如果指定的调色板具有透明颜色；否则，  false 。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

