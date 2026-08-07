---
title: "ColorPaletteHelper"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Kelas bantu untuk manipulasi palet warna."
type: docs
weight: 28
url: /id/java/com.aspose.psd/colorpalettehelper/
---

**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

Kelas bantu untuk manipulasi palet warna.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [create4Bit()](#create4Bit--) | Membuat palet warna 4 bit. |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | Membuat palet skala abu-abu 4 bit. |
| [create8Bit()](#create8Bit--) | Membuat palet warna 8 bit. |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | Membuat palet skala abu-abu 8 bit. |
| [createMonochrome()](#createMonochrome--) | Membuat palet warna monokrom yang hanya berisi 2 warna. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-) | Mendapatkan palet warna dari gambar raster (mem-palletisasi gambar) jika gambar tidak memilikinya. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-) | Mendapatkan palet warna dari gambar raster (mem-palletisasi gambar) jika gambar tidak memilikinya. |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-int-) | Mendapatkan palet warna dari gambar raster (mem-palletisasi gambar) jika gambar tidak memilikinya. |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.psd.RasterImage-) | Dapatkan palet warna 256, yang disusun dari bit atas nilai warna gambar awal. |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.psd.RasterImage-) | Dapatkan palet warna 256 yang seragam. |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.psd.IColorPalette-) | Menentukan apakah palet yang ditentukan memiliki warna transparan. |
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


Membuat palet warna 4 bit.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


Membuat palet skala abu-abu 4 bit.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| minIsWhite | boolean | jika diatur ke  true  palet dimulai dengan warna putih, jika tidak dimulai dengan warna hitam. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


Membuat palet warna 8 bit.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


Membuat palet skala abu-abu 8 bit.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| minIsWhite | boolean | jika diatur ke  true  palet dimulai dengan warna putih, jika tidak dimulai dengan warna hitam. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit grayscale palette.
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


Membuat palet warna monokrom yang hanya berisi 2 warna.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Color palette for monochrome images.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Mendapatkan palet warna dari gambar raster (mem-palletisasi gambar) jika gambar tidak memilikinya. Jika palet ada, akan digunakan alih-alih melakukan perhitungan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Gambar raster. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | Batas gambar tujuan. |
| entriesCount | int | Jumlah entri yang diinginkan. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


Mendapatkan palet warna dari gambar raster (mem-palletisasi gambar) jika gambar tidak memilikinya. Jika palet ada, akan digunakan alih-alih melakukan perhitungan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Gambar raster. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | Batas gambar tujuan. |
| entriesCount | int | Jumlah entri yang diinginkan. |
| useImagePalette | boolean | Jika diatur, akan menggunakan palet gambar sendiri jika tersedia |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount)
```


Mendapatkan palet warna dari gambar raster (mem-palletisasi gambar) jika gambar tidak memilikinya. Jika palet ada, akan digunakan alih-alih melakukan perhitungan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Gambar raster. |
| entriesCount | int | Jumlah entri yang diinginkan. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


Dapatkan palet warna 256, yang disusun dari bit atas nilai warna gambar awal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Gambar. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


Dapatkan palet warna 256 yang seragam.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Gambar. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.psd.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


Menentukan apakah palet yang ditentukan memiliki warna transparan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Palet. |

**Returns:**
boolean -  true  jika palet yang ditentukan memiliki warna transparan; jika tidak,  false .
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

