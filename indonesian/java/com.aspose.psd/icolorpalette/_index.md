---
title: "IColorPalette"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Antarmuka palet warna."
type: docs
weight: 117
url: /id/java/com.aspose.psd/icolorpalette/
---
```
public interface IColorPalette
```

Antarmuka palet warna.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Mendapatkan warna palet ARGB 32-bit berdasarkan indeks. |
| [getArgb32Entries()](#getArgb32Entries--) | Mendapatkan array struktur ARGB 32-bit. |
| [getColor(int index)](#getColor-int-) | Mendapatkan warna palet berdasarkan indeks. |
| [getEntries()](#getEntries--) | Mendapatkan array struktur  com.aspose.psd.Color . |
| [getEntriesCount()](#getEntriesCount--) | Mendapatkan jumlah entri. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Mendapatkan indeks warna terdekat. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Mendapatkan indeks warna ARGB 32-bit terdekat. |
| [isCompactPalette()](#isCompactPalette--) | Mendapatkan nilai yang menunjukkan apakah palet kompak digunakan. |
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public abstract int getArgb32Color(int index)
```


Mendapatkan warna palet ARGB 32-bit berdasarkan indeks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int | Indeks warna palet ARGB 32-bit. |

**Returns:**
int - Entri palet warna yang ditentukan oleh indeks.
### getArgb32Entries() {#getArgb32Entries--}
```
public abstract int[] getArgb32Entries()
```


Mendapatkan array struktur ARGB 32-bit.

**Returns:**
int[] - Entri ARGB 32-bit. Array struktur ARGB 32-bit yang membentuk com.aspose.psd.ColorPalette ini.
### getColor(int index) {#getColor-int-}
```
public abstract Color getColor(int index)
```


Mendapatkan warna palet berdasarkan indeks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int | Indeks warna palet. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public abstract Color[] getEntries()
```


Mendapatkan array struktur  com.aspose.psd.Color .

**Returns:**
com.aspose.psd.Color[] - Entri. Array struktur com.aspose.psd.Color yang membentuk com.aspose.psd.ColorPalette ini.
### getEntriesCount() {#getEntriesCount--}
```
public abstract int getEntriesCount()
```


Mendapatkan jumlah entri.

**Returns:**
int - Jumlah entri.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public abstract int getNearestColorIndex(Color color)
```


Mendapatkan indeks warna terdekat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Warna. |

**Returns:**
int - Indeks warna terdekat.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public abstract int getNearestColorIndex(int argb32Color)
```


Mendapatkan indeks warna ARGB 32-bit terdekat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| argb32Color | int | Warna ARGB 32-bit. |

**Returns:**
int - Indeks warna terdekat.
### isCompactPalette() {#isCompactPalette--}
```
public abstract boolean isCompactPalette()
```


Mendapatkan nilai yang menunjukkan apakah palet kompak digunakan.

Palet terkompak berarti gambar hanya akan berisi entri palet yang ditentukan jika memungkinkan, atau dengan kata lain gambar akan lebih kompak dan menempati ruang lebih sedikit; jika tidak, akan ada entri 2^BitsPerPixel dan gambar akan memesan lebih banyak ruang untuk semua entri palet yang mungkin. Menetapkan nilai ini ke true dan mengubah entri palet dapat menyebabkan penalti kinerja karena pergerakan data dapat terjadi, jadi gunakan dengan hati-hati.

**Returns:**
boolean -  true  jika palet kompak digunakan; jika tidak,  false .
