---
title: "ColorPalette"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mendefinisikan array warna yang membentuk palet warna."
type: docs
weight: 27
url: /id/java/com.aspose.psd/colorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

Mendefinisikan array warna yang membentuk palet warna. Warna-warna tersebut adalah warna ARGB 32-bit. Tidak dapat diwariskan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | Menginisialisasi instance baru dari kelas  ColorPalette  . |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | Menginisialisasi instance baru dari kelas  ColorPalette  dan IsCompactPalette bernilai false. |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.psd.Color---boolean-) | Menginisialisasi instance baru dari kelas  ColorPalette  . |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.psd.Color---) | Menginisialisasi instance baru dari kelas  ColorPalette  dan IsCompactPalette bernilai false. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | Menyalin palet. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | Menyalin palet. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Mendapatkan warna palet ARGB 32-bit berdasarkan indeks. |
| [getArgb32Entries()](#getArgb32Entries--) | Mendapatkan array struktur ARGB 32-bit. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | Mendapatkan warna palet berdasarkan indeks. |
| [getEntries()](#getEntries--) | Mendapatkan array struktur  com.aspose.psd.Color . |
| [getEntriesCount()](#getEntriesCount--) | Mendapatkan jumlah entri. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Mendapatkan indeks warna terdekat. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Mendapatkan indeks warna terdekat. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah palet kompak digunakan. |
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


Menginisialisasi instance baru dari kelas  ColorPalette  .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| argb32Entries | int[] | Entri palet warna ARGB 32-bit. |
| isCompactPalette | boolean | Menunjukkan apakah palet terkompaksi. |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


Menginisialisasi instance baru dari kelas  ColorPalette  dan IsCompactPalette bernilai false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| argb32Entries | int[] | Entri palet warna ARGB 32-bit. |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.psd.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


Menginisialisasi instance baru dari kelas  ColorPalette  .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | Entri palet warna. |
| isCompactPalette | boolean | Menunjukkan apakah palet terkompaksi. |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.psd.Color---}
```
public ColorPalette(Color[] entries)
```


Menginisialisasi instance baru dari kelas  ColorPalette  dan IsCompactPalette bernilai false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | Entri palet warna. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


Menyalin palet.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Palet warna. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Menyalin palet.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Palet warna. |
| useCompactPalette | boolean | Menunjukkan apakah palet terkompaksi. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
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
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public int getArgb32Color(int index)
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
public int[] getArgb32Entries()
```


Mendapatkan array struktur ARGB 32-bit.

**Returns:**
int[] - Entri. Array struktur ARGB 32-bit yang membentuk  Aspose.Imaging.ColorPalette .
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


Mendapatkan warna palet berdasarkan indeks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int | Indeks warna palet. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Mendapatkan array struktur  com.aspose.psd.Color .

**Returns:**
com.aspose.psd.Color[] - Entri. Array struktur  com.aspose.psd.Color  yang membentuk  Aspose.Imaging.ColorPalette .
### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Mendapatkan jumlah entri.

**Returns:**
int - Jumlah entri.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public int getNearestColorIndex(Color color)
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
public int getNearestColorIndex(int argb32Color)
```


Mendapatkan indeks warna terdekat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| argb32Color | int | Warna ARGB 32-bit. |

**Returns:**
int - Indeks warna terdekat.
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


Mendapatkan atau mengatur nilai yang menunjukkan apakah palet kompak digunakan.

**Returns:**
boolean -  true  jika palet kompak digunakan; jika tidak,  false .

Palet terkompak berarti gambar hanya akan berisi entri palet yang ditentukan jika memungkinkan, atau dengan kata lain gambar akan lebih kompak dan menempati ruang lebih sedikit; jika tidak, akan ada entri 2^BitsPerPixel dan gambar akan memesan lebih banyak ruang untuk semua entri palet yang mungkin. Menetapkan nilai ini ke true dan mengubah entri palet dapat menyebabkan penalti kinerja karena pergerakan data dapat terjadi, jadi gunakan dengan hati-hati.
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

