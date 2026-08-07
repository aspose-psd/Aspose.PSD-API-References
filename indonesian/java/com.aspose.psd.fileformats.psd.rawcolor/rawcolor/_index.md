---
title: "RawColor"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Kelas Raw Color membantu menyimpan warna dengan jumlah kanal apa pun, mode warna apa pun, dan kedalaman bit apa pun. Harap perhatikan bahwa beberapa kelas internal dapat mengalami masalah saat mengonversi RawColor ke format aslinya, jadi jika API menyediakan warna CMYK untuk Anda, lebih dapat diandalkan untuk menggunakan format yang disediakan."
type: docs
weight: 11
url: /id/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolor/
---

**Inheritance:**
java.lang.Object
```
public final class RawColor
```

Kelas Raw Color membantu menyimpan warna dengan jumlah kanal apa pun, mode warna apa pun, dan kedalaman bit apa pun. Harap perhatikan, beberapa kelas internal dapat mengalami masalah saat mengonversi RawColor ke format aslinya, jadi jika API menyediakan warna CMYK untuk Anda, lebih dapat diandalkan untuk menggunakan format yang disediakan. Juga, mungkin ada beberapa kasus ketika Raw Color dapat dikonversi.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [RawColor(ColorComponent[] components)](#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---) | Menginisialisasi instance baru dari kelas [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor). |
| [RawColor(PixelDataFormat pixelDataFormat)](#RawColor-com.aspose.psd.PixelDataFormat-) |  |
| [RawColor(PixelDataFormat pixelDataFormat, short colorMode)](#RawColor-com.aspose.psd.PixelDataFormat-short-) | Menginisialisasi instance baru dari kelas [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) dari format data piksel menggunakan mode warna yang telah ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah Object yang ditentukan, sama dengan instance ini. |
| [getAsInt()](#getAsInt--) | Mendapatkan warna sebagai int jika memungkinkan untuk mendapatkannya. |
| [getAsLong()](#getAsLong--) | Mendapatkan warna sebagai long jika memungkinkan untuk mendapatkannya. |
| [getBitDepth()](#getBitDepth--) | Mendapatkan kedalaman bit dari Raw Color. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | Mode yang harus diikuti oleh warna. |
| [getColorModeName()](#getColorModeName--) | Mendapatkan nama mode warna. |
| [getComponents()](#getComponents--) | Mendapatkan komponen warna. |
| [hashCode()](#hashCode--) | Mendapatkan kode hash dari objek saat ini. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(RawColor left, RawColor right)](#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Mengimplementasikan operator ==. |
| [op_Inequality(RawColor left, RawColor right)](#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Mengimplementasikan operator !=. |
| [setAsInt(int value)](#setAsInt-int-) | Mengatur data ke semua kanal dari argumen int jika memungkinkan. |
| [setAsLong(long value)](#setAsLong-long-) | Mengatur data ke semua kanal dari argumen int jika memungkinkan. |
| [setColorMode(short value)](#setColorMode-short-) | Mode yang harus diikuti oleh warna. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColor(ColorComponent[] components) {#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---}
```
public RawColor(ColorComponent[] components)
```


Menginisialisasi instance baru dari kelas [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| components | [ColorComponent\[\]](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) | Komponen warna khusus. |

### RawColor(PixelDataFormat pixelDataFormat) {#RawColor-com.aspose.psd.PixelDataFormat-}
```
public RawColor(PixelDataFormat pixelDataFormat)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) |  |

### RawColor(PixelDataFormat pixelDataFormat, short colorMode) {#RawColor-com.aspose.psd.PixelDataFormat-short-}
```
public RawColor(PixelDataFormat pixelDataFormat, short colorMode)
```


Menginisialisasi instance baru dari kelas [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) dari format data piksel menggunakan mode warna yang telah ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Format data piksel. |
| colorMode | short |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah Object yang ditentukan, sama dengan instance ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Objek untuk dibandingkan dengan instance ini. |

**Returns:**
boolean -  true  jika Objek yang ditentukan sama dengan instance ini; jika tidak,  false .
### getAsInt() {#getAsInt--}
```
public final int getAsInt()
```


Mendapatkan warna sebagai int jika memungkinkan untuk mendapatkannya.

**Returns:**
int - Data kanal disimpan dalam Int
### getAsLong() {#getAsLong--}
```
public final long getAsLong()
```


Mendapatkan warna sebagai long jika memungkinkan untuk mendapatkannya.

**Returns:**
long - Data saluran disimpan dalam Int
### getBitDepth() {#getBitDepth--}
```
public final int getBitDepth()
```


Mendapatkan kedalaman bit dari Warna Mentah. Misalnya untuk warna ARGB dengan 8 bit per saluran/komponen adalah 32 Kedalaman Bit untuk warna ARGB penuh dengan 16 bit per saluran/komponen adalah 64. Kedalaman bit diakumulasi dari jumlah kedalaman bit saluran. Hal ini memungkinkan jika saluran yang berbeda memiliki kedalaman bit yang berbeda.

**Returns:**
int - Jumlah semua kedalaman bit saluran
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Mode yang harus diikuti oleh warna.

**Returns:**
short
### getColorModeName() {#getColorModeName--}
```
public final String getColorModeName()
```


Mendapatkan nama mode warna. Nama mode warna diakumulasi dari nama saluran/komponen

**Returns:**
java.lang.String - String dengan nama mode warna
### getComponents() {#getComponents--}
```
public final ColorComponent[] getComponents()
```


Mendapatkan komponen warna. Setiap komponen adalah saluran terpisah, dan jika Anda menggunakan skema warna yang tidak populer, lebih baik bekerja dengan setiap saluran secara terpisah

Nilai: Komponen warna

**Returns:**
com.aspose.psd.fileformats.psd.rawcolor.ColorComponent[]
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mendapatkan kode hash dari objek saat ini.

**Returns:**
int - Kode hash.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(RawColor left, RawColor right) {#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Equality(RawColor left, RawColor right)
```


Mengimplementasikan operator ==.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | RawColor pertama. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | RawColor kedua. |

**Returns:**
boolean - Hasil operator.
### op_Inequality(RawColor left, RawColor right) {#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Inequality(RawColor left, RawColor right)
```


Mengimplementasikan operator !=.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | RawColor pertama. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | RawColor kedua. |

**Returns:**
boolean - Hasil operator.
### setAsInt(int value) {#setAsInt-int-}
```
public final void setAsInt(int value)
```


Mengatur data ke semua kanal dari argumen int jika memungkinkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai int yang berisi data komponen |

### setAsLong(long value) {#setAsLong-long-}
```
public final void setAsLong(long value)
```


Mengatur data ke semua kanal dari argumen int jika memungkinkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long | Nilai int yang berisi data komponen |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Mode yang harus diikuti oleh warna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

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

