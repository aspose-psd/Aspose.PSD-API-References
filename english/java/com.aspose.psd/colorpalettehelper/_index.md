---
title: ColorPaletteHelper
second_title: Aspose.PSD for Java API Reference
description: Helper class for color palettes manipulation.
type: docs
weight: 28
url: /java/com.aspose.psd/colorpalettehelper/
---

**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

Helper class for color palettes manipulation.
## Methods

| Method | Description |
| --- | --- |
| [create4Bit()](#create4Bit--) | Creates the 4 bit color palette. |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | Creates the 4 bit grayscale palette. |
| [create8Bit()](#create8Bit--) | Creates the 8 bit color palette. |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | Creates the 8 bit grayscale palette. |
| [createMonochrome()](#createMonochrome--) | Creates a monochrome color palette containing 2 colors only. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-) | Gets color palette from raster image (palletizes image) in case the image does not have one. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-) | Gets color palette from raster image (palletizes image) in case the image does not have one. |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-int-) | Gets color palette from raster image (palletizes image) in case the image does not have one. |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.psd.RasterImage-) | Get 256 color palette, composed from upper bits of initial image color values. |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.psd.RasterImage-) | Get uniform 256 color palette. |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.psd.IColorPalette-) | Determines whether the specified palette has transparent colors. |
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


Creates the 4 bit color palette.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


Creates the 4 bit grayscale palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| minIsWhite | boolean | if set to  true  the palette starts with white color, otherwise it starts with black color. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


Creates the 8 bit color palette.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


Creates the 8 bit grayscale palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| minIsWhite | boolean | if set to  true  the palette starts with white color, otherwise it starts with black color. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit grayscale palette.
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


Creates a monochrome color palette containing 2 colors only.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Color palette for monochrome images.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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


Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | The raster image. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | The destination image bounds. |
| entriesCount | int | The desired entries count. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | The raster image. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | The destination image bounds. |
| entriesCount | int | The desired entries count. |
| useImagePalette | boolean | If set, it will use its own image palette if available |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount)
```


Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | The raster image. |
| entriesCount | int | The desired entries count. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


Get 256 color palette, composed from upper bits of initial image color values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | The image. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


Get uniform 256 color palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | The image. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.psd.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


Determines whether the specified palette has transparent colors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | The palette. |

**Returns:**
boolean -  true  if the specified palette has transparent colors; otherwise,  false .
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

