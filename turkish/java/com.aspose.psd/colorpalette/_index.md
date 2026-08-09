---
title: "ColorPalette"
second_title: "Java için Aspose.PSD API Referansı"
description: "Bir renk paletini oluşturan renk dizisini tanımlar."
type: docs
weight: 27
url: /tr/java/com.aspose.psd/colorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

Bir renk paletini oluşturan renklerin bir dizisini tanımlar. Renkler 32-bit ARGB renkleridir. Kalıtılamaz.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | ColorPalette sınıfının yeni bir örneğini başlatır. |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | ColorPalette sınıfının yeni bir örneğini başlatır ve IsCompactPalette false'tur. |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.psd.Color---boolean-) | ColorPalette sınıfının yeni bir örneğini başlatır. |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.psd.Color---) | ColorPalette sınıfının yeni bir örneğini başlatır ve IsCompactPalette false'tur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | Paleti kopyalar. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | Paleti kopyalar. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Dizine göre 32-bit ARGB palet rengini alır. |
| [getArgb32Entries()](#getArgb32Entries--) | 32-bit ARGB yapılarının bir dizisini alır. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | Dizine göre palet rengini alır. |
| [getEntries()](#getEntries--) | com.aspose.psd.Color yapıların bir dizisini alır. |
| [getEntriesCount()](#getEntriesCount--) | Giriş sayısını alır. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | En yakın rengin dizinini alır. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | En yakın rengin dizinini alır. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | Kompakt paletin kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorPalette(int[] argb32Entries, boolean isCompactPalette) {#ColorPalette-int---boolean-}
```
public ColorPalette(int[] argb32Entries, boolean isCompactPalette)
```


ColorPalette sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argb32Entries | int[] | 32-bit ARGB renk paleti girişleri. |
| isCompactPalette | boolean | Kompakt palet olup olmadığını gösterir. |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


ColorPalette sınıfının yeni bir örneğini başlatır ve IsCompactPalette false'tur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argb32Entries | int[] | 32-bit ARGB renk paleti girişleri. |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.psd.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


ColorPalette sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | Renk paleti girişleri. |
| isCompactPalette | boolean | Kompakt palet olup olmadığını gösterir. |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.psd.Color---}
```
public ColorPalette(Color[] entries)
```


ColorPalette sınıfının yeni bir örneğini başlatır ve IsCompactPalette false'tur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | Renk paleti girişleri. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


Paleti kopyalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Renk paleti. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Paleti kopyalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Renk paleti. |
| useCompactPalette | boolean | Kompakt palet olup olmadığını gösterir. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
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
public int getArgb32Color(int index)
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
public int[] getArgb32Entries()
```


32-bit ARGB yapılarının bir dizisini alır.

**Returns:**
int[] - Girişler. Bu Aspose.Imaging.ColorPalette'i oluşturan 32-bit ARGB yapıların dizisi.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor(int index) {#getColor-int-}
```
public Color getColor(int index)
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
public Color[] getEntries()
```


com.aspose.psd.Color yapıların bir dizisini alır.

**Returns:**
com.aspose.psd.Color[] - Girişler. Bu Aspose.Imaging.ColorPalette'i oluşturan com.aspose.psd.Color yapısının dizisi.
### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Giriş sayısını alır.

**Returns:**
int - Giriş sayısı.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public int getNearestColorIndex(Color color)
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
public int getNearestColorIndex(int argb32Color)
```


En yakın rengin dizinini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argb32Color | int | 32-bit ARGB renk. |

**Returns:**
int - En yakın rengin indeksi.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


Kompakt paletin kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean -  true  eğer sıkıştırılmış palet kullanılırsa; aksi takdirde,  false .

Sıkıştırılmış palet, mümkünse görüntünün yalnızca belirtilen palet girişlerini içereceği anlamına gelir; başka bir deyişle, görüntü daha sıkışık olur ve daha az yer kaplar; aksi takdirde 2^BitsPerPixel girişi olur ve görüntü tüm olası palet girişleri için daha fazla yer ayırır. Bu değeri true olarak ayarlamak ve palet girişlerini değiştirmek, veri hareketi olabileceği için performans cezasına yol açabilir; bu yüzden dikkatli kullanın.
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

