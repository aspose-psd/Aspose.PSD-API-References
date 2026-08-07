---
title: "PsdColorPalette"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Palet warna PSD."
type: docs
weight: 13
url: /id/java/com.aspose.psd.fileformats.psd/psdcolorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IPsdColorPalette](../../com.aspose.psd/ipsdcolorpalette)
```
public class PsdColorPalette implements IPsdColorPalette
```

Palet warna PSD.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PsdColorPalette(IColorPalette colorPalette)](#PsdColorPalette-com.aspose.psd.IColorPalette-) | Menginisialisasi instance baru dari kelas [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(IColorPalette colorPalette, short transparentIndex)](#PsdColorPalette-com.aspose.psd.IColorPalette-short-) | Menginisialisasi instance baru dari kelas [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)](#PsdColorPalette-byte---boolean-) | Menginisialisasi instance baru dari kelas [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData)](#PsdColorPalette-byte---) | Menginisialisasi instance baru dari kelas [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) dan IsCompactPalette bernilai false. |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-byte---short-boolean-) | Menginisialisasi instance baru dari kelas [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex)](#PsdColorPalette-byte---short-) | Menginisialisasi instance baru dari kelas [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) dan IsCompactPalette bernilai false. |
| [PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)](#PsdColorPalette-int---boolean-) | Menginisialisasi instance baru dari kelas [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---boolean-) | Menginisialisasi instance baru dari kelas [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries)](#PsdColorPalette-com.aspose.psd.Color---) | Menginisialisasi instance baru dari kelas [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) dan IsCompactPalette bernilai false. |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---short-boolean-) | Menginisialisasi instance baru dari kelas [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)](#PsdColorPalette-com.aspose.psd.Color---short-) | Menginisialisasi instance baru dari kelas [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) dan IsCompactPalette bernilai false. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | Menyalin palet. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | Menyalin palet. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Mendapatkan warna palet ARGB 32-bit berdasarkan indeks. |
| [getArgb32Entries()](#getArgb32Entries--) | Mendapatkan array warna ARGB 32-bit. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | Mendapatkan warna palet berdasarkan indeks. |
| [getEntries()](#getEntries--) | Mendapatkan array struktur [Color](../../com.aspose.psd/color). |
| [getEntriesCount()](#getEntriesCount--) | Mendapatkan jumlah entri. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Mendapatkan indeks warna terdekat. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Mendapatkan indeks warna terdekat. |
| [getRawEntries()](#getRawEntries--) | Mendapatkan data entri palet warna mentah. |
| [getRawEntriesCount()](#getRawEntriesCount--) | Mendapatkan jumlah entri palet warna mentah. |
| [getTransparentColor()](#getTransparentColor--) | Mendapatkan warna transparan. |
| [getTransparentIndex()](#getTransparentIndex--) | Mendapatkan indeks warna transparan. |
| [hasTransparentColor()](#hasTransparentColor--) | Mendapatkan nilai yang menunjukkan apakah warna transparan ada. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | Mendapatkan nilai yang menunjukkan apakah palet terkompaksi. |
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


Menginisialisasi instance baru dari kelas [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Palet warna. |

### PsdColorPalette(IColorPalette colorPalette, short transparentIndex) {#PsdColorPalette-com.aspose.psd.IColorPalette-short-}
```
public PsdColorPalette(IColorPalette colorPalette, short transparentIndex)
```


Menginisialisasi instance baru dari kelas [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Palet warna. |
| transparentIndex | short | Indeks warna transparan. |

### PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette) {#PsdColorPalette-byte---boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)
```


Menginisialisasi instance baru dari kelas [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rawEntriesData | byte[] | Data entri mentah. |
| isCompactPalette | boolean | Menunjukkan apakah palet terkompaksi. |

### PsdColorPalette(byte[] rawEntriesData) {#PsdColorPalette-byte---}
```
public PsdColorPalette(byte[] rawEntriesData)
```


Menginisialisasi instance baru dari kelas [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) dan IsCompactPalette bernilai false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rawEntriesData | byte[] | Data entri mentah. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-byte---short-boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)
```


Menginisialisasi instance baru dari kelas [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rawEntriesData | byte[] | Data entri mentah. |
| transparentIndex | short | Indeks warna transparan. Catatan: indeks bukan indeks entri mentah, melainkan untuk array warna yang dikonversi. |
| useCompactPalette | boolean | Menunjukkan apakah palet terkompaksi. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex) {#PsdColorPalette-byte---short-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex)
```


Menginisialisasi instance baru dari kelas [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) dan IsCompactPalette bernilai false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rawEntriesData | byte[] | Data entri mentah. |
| transparentIndex | short | Indeks warna transparan. Catatan: indeks bukan indeks entri mentah, melainkan untuk array warna yang dikonversi. |

### PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette) {#PsdColorPalette-int---boolean-}
```
public PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)
```


Menginisialisasi instance baru dari kelas [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorPaletteArgb32Entries | int[] | Entri ARGB 32-bit palet warna. |
| isCompactPalette | boolean | Menunjukkan apakah palet terkompaksi. |

### PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)
```


Menginisialisasi instance baru dari kelas [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Entri palet warna. |
| isCompactPalette | boolean | Menunjukkan apakah palet terkompaksi. |

### PsdColorPalette(Color[] colorPaletteEntries) {#PsdColorPalette-com.aspose.psd.Color---}
```
public PsdColorPalette(Color[] colorPaletteEntries)
```


Menginisialisasi instance baru dari kelas [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) dan IsCompactPalette bernilai false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Entri palet warna. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---short-boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)
```


Menginisialisasi instance baru dari kelas [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Entri palet warna. |
| transparentIndex | short | Indeks warna transparan. |
| useCompactPalette | boolean | Menunjukkan apakah palet terkompaksi. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex) {#PsdColorPalette-com.aspose.psd.Color---short-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)
```


Menginisialisasi instance baru dari kelas [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) dan IsCompactPalette bernilai false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Entri palet warna. |
| transparentIndex | short | Indeks warna transparan. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette)
```


Menyalin palet.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Palet warna. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Menyalin palet.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Palet warna. |
| useCompactPalette | boolean | Menunjukkan apakah palet terkompaksi. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
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
public final int getArgb32Color(int index)
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
public final int[] getArgb32Entries()
```


Mendapatkan array warna ARGB 32-bit.

**Returns:**
int[] - Array struktur ARGB 32-bit yang membentuk [ColorPalette](../../com.aspose.psd/colorpalette) ini. Nilai: Entri.
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


Mendapatkan warna palet berdasarkan indeks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int | Indeks warna palet. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public final Color[] getEntries()
```


Mendapatkan array struktur [Color](../../com.aspose.psd/color).

**Returns:**
com.aspose.psd.Color[] - Array struktur [Color](../../com.aspose.psd/color) yang membentuk [ColorPalette](../../com.aspose.psd/colorpalette) ini. Nilai: Entri.
### getEntriesCount() {#getEntriesCount--}
```
public final int getEntriesCount()
```


Mendapatkan jumlah entri.

Nilai: Jumlah entri.

**Returns:**
int
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public final int getNearestColorIndex(Color color)
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
public final int getNearestColorIndex(int argb32Color)
```


Mendapatkan indeks warna terdekat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| argb32Color | int | Warna ARGB 32-bit. |

**Returns:**
int - Indeks warna terdekat.
### getRawEntries() {#getRawEntries--}
```
public final byte[] getRawEntries()
```


Mendapatkan data entri palet warna mentah.

Nilai: Data entri palet warna mentah.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public final int getRawEntriesCount()
```


Mendapatkan jumlah entri palet warna mentah.

Nilai: Jumlah entri palet warna mentah.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public final Color getTransparentColor()
```


Mendapatkan warna transparan.

Nilai: Warna transparan.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public final short getTransparentIndex()
```


Mendapatkan indeks warna transparan.

Nilai: Indeks warna transparan.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public final boolean hasTransparentColor()
```


Mendapatkan nilai yang menunjukkan apakah warna transparan ada.

Nilai:  true  jika warna transparan ada; jika tidak,  false .

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


Mendapatkan nilai yang menunjukkan apakah palet terkompaksi.

Nilai:  true  jika palet dikompak; jika tidak,  false .

--------------------

Palet terkompak berarti gambar hanya akan berisi entri palet yang ditentukan jika memungkinkan, atau dengan kata lain gambar akan lebih kompak dan menempati ruang lebih sedikit; jika tidak, akan ada entri 2^BitsPerPixel dan gambar akan memesan lebih banyak ruang untuk semua entri palet yang mungkin. Menetapkan nilai ini ke true dan mengubah entri palet dapat menyebabkan penalti kinerja karena pergerakan data dapat terjadi, jadi gunakan dengan hati-hati.

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

