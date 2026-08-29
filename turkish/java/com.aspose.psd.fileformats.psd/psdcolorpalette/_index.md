---
title: "PsdColorPalette"
second_title: "Java için Aspose.PSD API Referansı"
description: "PSD renk paleti."
type: docs
weight: 13
url: /tr/java/com.aspose.psd.fileformats.psd/psdcolorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IPsdColorPalette](../../com.aspose.psd/ipsdcolorpalette)
```
public class PsdColorPalette implements IPsdColorPalette
```

PSD renk paleti.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PsdColorPalette(IColorPalette colorPalette)](#PsdColorPalette-com.aspose.psd.IColorPalette-) | Yeni bir [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) sınıfı örneği başlatır. |
| [PsdColorPalette(IColorPalette colorPalette, short transparentIndex)](#PsdColorPalette-com.aspose.psd.IColorPalette-short-) | Yeni bir [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) sınıfı örneği başlatır. |
| [PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)](#PsdColorPalette-byte---boolean-) | Yeni bir [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) sınıfı örneği başlatır. |
| [PsdColorPalette(byte[] rawEntriesData)](#PsdColorPalette-byte---) | Yeni bir [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) sınıfı örneği başlatır ve IsCompactPalette false değerindedir. |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-byte---short-boolean-) | Yeni bir [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) sınıfı örneği başlatır. |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex)](#PsdColorPalette-byte---short-) | Yeni bir [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) sınıfı örneği başlatır ve IsCompactPalette false değerindedir. |
| [PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)](#PsdColorPalette-int---boolean-) | Yeni bir [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) sınıfı örneği başlatır. |
| [PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---boolean-) | Yeni bir [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) sınıfı örneği başlatır. |
| [PsdColorPalette(Color[] colorPaletteEntries)](#PsdColorPalette-com.aspose.psd.Color---) | Yeni bir [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) sınıfı örneği başlatır ve IsCompactPalette false değerindedir. |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---short-boolean-) | Yeni bir [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) sınıfı örneği başlatır. |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)](#PsdColorPalette-com.aspose.psd.Color---short-) | Yeni bir [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) sınıfı örneği başlatır ve IsCompactPalette false değerindedir. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | Paleti kopyalar. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | Paleti kopyalar. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Dizine göre 32-bit ARGB palet rengini alır. |
| [getArgb32Entries()](#getArgb32Entries--) | 32-bit ARGB renklerinden oluşan bir dizi alır. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | Dizine göre palet rengini alır. |
| [getEntries()](#getEntries--) | Bir dizi [Color](../../com.aspose.psd/color) yapısı alır. |
| [getEntriesCount()](#getEntriesCount--) | Giriş sayısını alır. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | En yakın rengin dizinini alır. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | En yakın rengin dizinini alır. |
| [getRawEntries()](#getRawEntries--) | Ham renk paleti giriş verilerini alır. |
| [getRawEntriesCount()](#getRawEntriesCount--) | Ham renk paleti giriş sayısını alır. |
| [getTransparentColor()](#getTransparentColor--) | Şeffaf rengi alır. |
| [getTransparentIndex()](#getTransparentIndex--) | Şeffaf rengin dizinini alır. |
| [hasTransparentColor()](#hasTransparentColor--) | Şeffaf rengin mevcut olup olmadığını gösteren bir değer alır. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | Kompakt palet olup olmadığını gösteren bir değer alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdColorPalette(IColorPalette colorPalette) {#PsdColorPalette-com.aspose.psd.IColorPalette-}
```
public PsdColorPalette(IColorPalette colorPalette)
```


Yeni bir [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Renk paleti. |

### PsdColorPalette(IColorPalette colorPalette, short transparentIndex) {#PsdColorPalette-com.aspose.psd.IColorPalette-short-}
```
public PsdColorPalette(IColorPalette colorPalette, short transparentIndex)
```


Yeni bir [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Renk paleti. |
| transparentIndex | short | Şeffaf renk indeksi. |

### PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette) {#PsdColorPalette-byte---boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)
```


Yeni bir [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rawEntriesData | byte[] | Ham giriş verileri. |
| isCompactPalette | boolean | Kompakt palet olup olmadığını gösterir. |

### PsdColorPalette(byte[] rawEntriesData) {#PsdColorPalette-byte---}
```
public PsdColorPalette(byte[] rawEntriesData)
```


Yeni bir [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) sınıfı örneği başlatır ve IsCompactPalette false değerindedir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rawEntriesData | byte[] | Ham giriş verileri. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-byte---short-boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)
```


Yeni bir [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rawEntriesData | byte[] | Ham giriş verileri. |
| transparentIndex | short | Şeffaf renk indeksi. Not: indeks ham giriş indeksi değildir, bunun yerine dönüştürülmüş renk dizisi içindir. |
| useCompactPalette | boolean | Kompakt palet olup olmadığını gösterir. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex) {#PsdColorPalette-byte---short-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex)
```


Yeni bir [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) sınıfı örneği başlatır ve IsCompactPalette false değerindedir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rawEntriesData | byte[] | Ham giriş verileri. |
| transparentIndex | short | Şeffaf renk indeksi. Not: indeks ham giriş indeksi değildir, bunun yerine dönüştürülmüş renk dizisi içindir. |

### PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette) {#PsdColorPalette-int---boolean-}
```
public PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)
```


Yeni bir [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorPaletteArgb32Entries | int[] | Renk paleti 32-bit ARGB girişleri. |
| isCompactPalette | boolean | Kompakt palet olup olmadığını gösterir. |

### PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)
```


Yeni bir [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Renk paleti girişleri. |
| isCompactPalette | boolean | Kompakt palet olup olmadığını gösterir. |

### PsdColorPalette(Color[] colorPaletteEntries) {#PsdColorPalette-com.aspose.psd.Color---}
```
public PsdColorPalette(Color[] colorPaletteEntries)
```


Yeni bir [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) sınıfı örneği başlatır ve IsCompactPalette false değerindedir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Renk paleti girişleri. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---short-boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)
```


Yeni bir [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Renk paleti girişleri. |
| transparentIndex | short | Şeffaf renk indeksi. |
| useCompactPalette | boolean | Kompakt palet olup olmadığını gösterir. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex) {#PsdColorPalette-com.aspose.psd.Color---short-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)
```


Yeni bir [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) sınıfı örneği başlatır ve IsCompactPalette false değerindedir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Renk paleti girişleri. |
| transparentIndex | short | Şeffaf renk indeksi. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette)
```


Paleti kopyalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Renk paleti. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Paleti kopyalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Renk paleti. |
| useCompactPalette | boolean | Kompakt palet olup olmadığını gösterir. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
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
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public final int getArgb32Color(int index)
```


Dizine göre 32-bit ARGB palet rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeks | int | 32-bit ARGB palet renk indeksi. |

**Returns:**
int - Belirtilen indeks tarafından tanımlanan renk paleti girişi.
### getArgb32Entries() {#getArgb32Entries--}
```
public final int[] getArgb32Entries()
```


32-bit ARGB renklerinden oluşan bir dizi alır.

**Returns:**
int[] - Bu [ColorPalette](../../com.aspose.psd/colorpalette) öğesini oluşturan 32-bit ARGB yapısının dizisi. Değer: Girişler.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor(int index) {#getColor-int-}
```
public final Color getColor(int index)
```


Dizine göre palet rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeks | int | Palet renk indeksi. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public final Color[] getEntries()
```


Bir dizi [Color](../../com.aspose.psd/color) yapısı alır.

**Returns:**
com.aspose.psd.Color[] - Bu [ColorPalette](../../com.aspose.psd/colorpalette) öğesini oluşturan [Color](../../com.aspose.psd/color) yapısının dizisi. Değer: Girişler.
### getEntriesCount() {#getEntriesCount--}
```
public final int getEntriesCount()
```


Giriş sayısını alır.

Değer: Giriş sayısı.

**Returns:**
int
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public final int getNearestColorIndex(Color color)
```


En yakın rengin dizinini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Renk. |

**Returns:**
int - En yakın rengin indeksi.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public final int getNearestColorIndex(int argb32Color)
```


En yakın rengin dizinini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argb32Color | int | 32-bit ARGB renk. |

**Returns:**
int - En yakın rengin indeksi.
### getRawEntries() {#getRawEntries--}
```
public final byte[] getRawEntries()
```


Ham renk paleti giriş verilerini alır.

Değer: Ham renk paleti giriş verileri.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public final int getRawEntriesCount()
```


Ham renk paleti giriş sayısını alır.

Değer: Ham renk paleti giriş sayısı.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public final Color getTransparentColor()
```


Şeffaf rengi alır.

Değer: Şeffaf renk.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public final short getTransparentIndex()
```


Şeffaf rengin dizinini alır.

Değer: Şeffaf rengin indeksi.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public final boolean hasTransparentColor()
```


Şeffaf rengin mevcut olup olmadığını gösteren bir değer alır.

Değer:  true  eğer saydam renk mevcutsa; aksi takdirde,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompactPalette() {#isCompactPalette--}
```
public final boolean isCompactPalette()
```


Kompakt palet olup olmadığını gösteren bir değer alır.

Değer:  true  eğer palet sıkıştırılmışsa; aksi takdirde,  false .

--------------------

Sıkıştırılmış palet, mümkünse görüntünün yalnızca belirtilen palet girişlerini içereceği anlamına gelir; başka bir deyişle, görüntü daha sıkışık olur ve daha az yer kaplar; aksi takdirde 2^BitsPerPixel girişi olur ve görüntü tüm olası palet girişleri için daha fazla yer ayırır. Bu değeri true olarak ayarlamak ve palet girişlerini değiştirmek, veri hareketi olabileceği için performans cezasına yol açabilir; bu yüzden dikkatli kullanın.

**Returns:**
boolean
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

