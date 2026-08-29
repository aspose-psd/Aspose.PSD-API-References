---
title: "IColorPalette"
second_title: "Java için Aspose.PSD API Referansı"
description: "Renk paleti arayüzü."
type: docs
weight: 117
url: /tr/java/com.aspose.psd/icolorpalette/
---
```
public interface IColorPalette
```

Renk paleti arayüzü.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Dizine göre 32-bit ARGB palet rengini alır. |
| [getArgb32Entries()](#getArgb32Entries--) | 32-bit ARGB yapılarının bir dizisini alır. |
| [getColor(int index)](#getColor-int-) | Dizine göre palet rengini alır. |
| [getEntries()](#getEntries--) | com.aspose.psd.Color yapıların bir dizisini alır. |
| [getEntriesCount()](#getEntriesCount--) | Giriş sayısını alır. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | En yakın rengin dizinini alır. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | En yakın 32-bit ARGB renginin dizinini alır. |
| [isCompactPalette()](#isCompactPalette--) | Kompakt paletin kullanılıp kullanılmadığını gösteren bir değer alır. |
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public abstract int getArgb32Color(int index)
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
public abstract int[] getArgb32Entries()
```


32-bit ARGB yapılarının bir dizisini alır.

**Returns:**
int[] - 32-bit ARGB girişleri. Bu com.aspose.psd.ColorPalette'ı oluşturan 32-bit ARGB yapısının dizisi.
### getColor(int index) {#getColor-int-}
```
public abstract Color getColor(int index)
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
public abstract Color[] getEntries()
```


com.aspose.psd.Color yapıların bir dizisini alır.

**Returns:**
com.aspose.psd.Color[] - Girişler. Bu com.aspose.psd.ColorPalette'ı oluşturan com.aspose.psd.Color yapısının dizisi.
### getEntriesCount() {#getEntriesCount--}
```
public abstract int getEntriesCount()
```


Giriş sayısını alır.

**Returns:**
int - Giriş sayısı.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public abstract int getNearestColorIndex(Color color)
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
public abstract int getNearestColorIndex(int argb32Color)
```


En yakın 32-bit ARGB renginin dizinini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argb32Color | int | 32-bit ARGB renk. |

**Returns:**
int - En yakın rengin indeksi.
### isCompactPalette() {#isCompactPalette--}
```
public abstract boolean isCompactPalette()
```


Kompakt paletin kullanılıp kullanılmadığını gösteren bir değer alır.

Sıkıştırılmış palet, mümkünse görüntünün yalnızca belirtilen palet girişlerini içereceği anlamına gelir; başka bir deyişle, görüntü daha sıkışık olur ve daha az yer kaplar; aksi takdirde 2^BitsPerPixel girişi olur ve görüntü tüm olası palet girişleri için daha fazla yer ayırır. Bu değeri true olarak ayarlamak ve palet girişlerini değiştirmek, veri hareketi olabileceği için performans cezasına yol açabilir; bu yüzden dikkatli kullanın.

**Returns:**
boolean -  true  eğer sıkıştırılmış palet kullanılırsa; aksi takdirde,  false .
