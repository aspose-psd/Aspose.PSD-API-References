---
title: "ColorPaletteHelper"
second_title: "Java için Aspose.PSD API Referansı"
description: "Renk paletleri manipülasyonu için yardımcı sınıf."
type: docs
weight: 28
url: /tr/java/com.aspose.psd/colorpalettehelper/
---

**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

Renk paletleri manipülasyonu için yardımcı sınıf.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [create4Bit()](#create4Bit--) | 4 bit renk paletini oluşturur. |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | 4 bit gri tonlamalı paleti oluşturur. |
| [create8Bit()](#create8Bit--) | 8 bit renk paletini oluşturur. |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | 8 bit gri tonlamalı paleti oluşturur. |
| [createMonochrome()](#createMonochrome--) | Sadece 2 renk içeren tek renkli bir renk paleti oluşturur. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-) | Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-) | Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-int-) | Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.psd.RasterImage-) | İlk görüntü renk değerlerinin üst bitlerinden oluşan 256 renkli paleti al. |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.psd.RasterImage-) | Tekdüze 256 renkli paleti al. |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.psd.IColorPalette-) | Belirtilen paletin şeffaf renkleri olup olmadığını belirler. |
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


4 bit renk paletini oluşturur.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


4 bit gri tonlamalı paleti oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| minIsWhite | boolean | true olarak ayarlanırsa palet beyaz renk ile başlar, aksi takdirde siyah renk ile başlar. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


8 bit renk paletini oluşturur.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


8 bit gri tonlamalı paleti oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| minIsWhite | boolean | true olarak ayarlanırsa palet beyaz renk ile başlar, aksi takdirde siyah renk ile başlar. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit grayscale palette.
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


Sadece 2 renk içeren tek renkli bir renk paleti oluşturur.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Color palette for monochrome images.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). Palet mevcutsa, hesaplamalar yerine bu palet kullanılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Raster görüntüsü. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | Hedef görüntü sınırları. |
| entriesCount | int | İstenen giriş sayısı. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). Palet mevcutsa, hesaplamalar yerine bu palet kullanılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Raster görüntüsü. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | Hedef görüntü sınırları. |
| entriesCount | int | İstenen giriş sayısı. |
| useImagePalette | boolean | Ayarlanırsa, mevcut olduğunda kendi görüntü paletini kullanacaktır. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount)
```


Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). Palet mevcutsa, hesaplamalar yerine bu palet kullanılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Raster görüntüsü. |
| entriesCount | int | İstenen giriş sayısı. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


İlk görüntü renk değerlerinin üst bitlerinden oluşan 256 renkli paleti al.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Görüntü. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


Tekdüze 256 renkli paleti al.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Görüntü. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.psd.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


Belirtilen paletin şeffaf renkleri olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Palet. |

**Returns:**
boolean -  true  eğer belirtilen palet şeffaf renkler içeriyorsa; aksi takdirde,  false .
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

