---
title: "CmykColorHelper"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Metode bantu untuk bekerja dengan warna CMYK yang disajikan sebagai nilai integer 32-bit bertanda."
type: docs
weight: 18
url: /id/java/com.aspose.psd/cmykcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

Metode bantuan untuk bekerja dengan warna CMYK yang disajikan sebagai nilai integer 32-bit bertanda. Menyediakan API serupa dengan struct  com.aspose.psd.CmykColor . Lebih ringan karena warna CMYK disajikan hanya sebagai Int32 bukan sebagai struktur dengan bidang internal. Harap gunakan metode statis dari kelas ini bila memungkinkan alih-alih struct  com.aspose.psd.CmykColor  yang sudah usang.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | Membuat CMYK dari nilai cyan, magenta, kuning, dan hitam 32-bit. |
| [getC(int cmyk)](#getC-int-) | Mendapatkan nilai komponen cyan. |
| [getClass()](#getClass--) |  |
| [getK(int cmyk)](#getK-int-) | Mendapatkan nilai komponen hitam. |
| [getM(int cmyk)](#getM-int-) | Mendapatkan nilai komponen magenta. |
| [getY(int cmyk)](#getY-int-) | Mendapatkan nilai komponen kuning. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb(int cmykPixel)](#toArgb-int-) | Konversi dari warna CMYK ke warna ARGB. |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | Konversi dari warna CMYK ke warna ARGB. |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | Konversi dari warna CMYK ke warna ARGB. |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | Konversi dari warna CMYK ke warna ARGB menggunakan konversi Icc dengan profil default. |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | Konversi dari warna CMYK ke warna ARGB menggunakan konversi Icc dengan profil khusus. |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | Konversi dari warna CMYK ke warna ARGB menggunakan konversi Icc dengan profil default. |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | Konversi dari warna CMYK ke warna ARGB menggunakan konversi Icc dengan profil khusus. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | Konversi dari warna ARGB ke warna CMYK. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | Konversi dari warna ARGB ke warna CMYK. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | Konversi dari warna ARGB ke warna CMYK. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | Konversi dari warna ARGB ke warna CMYK. |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | Mengonversi RGB ke CMYK. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | Konversi dari warna ARGB ke warna CMYK menggunakan konversi Icc dengan profil default. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | Konversi dari warna ARGB ke warna CMYK menggunakan konversi Icc dengan profil khusus. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | Konversi dari warna ARGB ke warna CMYK menggunakan konversi Icc dengan profil default. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | Konversi dari warna ARGB ke warna CMYK menggunakan konversi Icc dengan profil khusus. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Mengonversi RGB ke CMYK menggunakan profil ICC khusus. |
| [toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIccBytes-internalized-int---int-int-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


Membuat CMYK dari nilai cyan, magenta, kuning, dan hitam 32-bit.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sian | int | Komponen cyan. Nilai yang valid antara 0 hingga 255. |
| magenta | int | Komponen magenta. Nilai yang valid antara 0 hingga 255. |
| kuning | int | Komponen kuning. Nilai yang valid antara 0 hingga 255. |
| hitam | int | Komponen hitam. Nilai yang valid antara 0 hingga 255. |

**Returns:**
int - Warna CMYK yang disajikan sebagai nilai integer 32-bit.
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


Mendapatkan nilai komponen cyan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cmyk | int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |

**Returns:**
int - Nilai komponen cyan.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getK(int cmyk) {#getK-int-}
```
public static int getK(int cmyk)
```


Mendapatkan nilai komponen hitam.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cmyk | int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |

**Returns:**
int - Nilai komponen hitam.
### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


Mendapatkan nilai komponen magenta.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cmyk | int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |

**Returns:**
int - Nilai komponen magenta.
### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


Mendapatkan nilai komponen kuning.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cmyk | int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |

**Returns:**
int - Nilai komponen kuning.
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




### toArgb(int cmykPixel) {#toArgb-int-}
```
public static Color toArgb(int cmykPixel)
```


Konversi dari warna CMYK ke warna ARGB.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cmykPixel | int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


Konversi dari warna CMYK ke warna ARGB.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cmykPixels | int[] | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |

**Returns:**
com.aspose.psd.Color[] - Warna ARGB.
### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


Konversi dari warna CMYK ke warna ARGB.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cmykPixels | int[] | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |

**Returns:**
int[] - Warna ARGB yang disajikan sebagai nilai integer 32-bit.
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


Konversi dari warna CMYK ke warna ARGB menggunakan konversi Icc dengan profil default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cmykPixel | int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


Konversi dari warna CMYK ke warna ARGB menggunakan konversi Icc dengan profil khusus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cmykPixel | int | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |
| cmykIccStream | java.io.InputStream | Aliran yang berisi profil Icc CMYK. |
| rgbIccStream | java.io.InputStream | Aliran yang berisi profil Icc RGB. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


Konversi dari warna CMYK ke warna ARGB menggunakan konversi Icc dengan profil default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cmykPixels | int[] | Piksel CMYK yang disajikan sebagai nilai integer 32-bit. |

**Returns:**
com.aspose.psd.Color[] - Warna ARGB.
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


Konversi dari warna CMYK ke warna ARGB menggunakan konversi Icc dengan profil khusus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cmykPixels | int[] | Warna CMYK yang disajikan sebagai nilai integer 32-bit. |
| cmykIccStream | java.io.InputStream | Aliran yang berisi profil Icc CMYK. |
| rgbIccStream | java.io.InputStream | Aliran yang berisi profil Icc RGB. |

**Returns:**
com.aspose.psd.Color[] - Warna ARGB.
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static int toCmyk(Color pixel)
```


Konversi dari warna ARGB ke warna CMYK.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Warna ARGB. |

**Returns:**
int - Warna CMYK yang disajikan sebagai nilai integer 32-bit.
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


Konversi dari warna ARGB ke warna CMYK.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Warna-warna ARGB. |

**Returns:**
int[] - Warna CMYK yang disajikan sebagai nilai integer 32-bit.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


Konversi dari warna ARGB ke warna CMYK.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| argbPixel | int | Warna ARGB yang disajikan sebagai nilai integer 32-bit. |

**Returns:**
int - Warna CMYK yang disajikan sebagai nilai integer 32-bit.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


Konversi dari warna ARGB ke warna CMYK.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| argbPixels | int[] | Warna ARGB yang disajikan sebagai nilai integer 32-bit. |

**Returns:**
int[] - Warna CMYK yang disajikan sebagai nilai integer 32-bit.
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


Mengonversi RGB ke CMYK.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| argbPixels | int[] | Warna RGB yang disajikan sebagai nilai integer 32-bit. |
| startIndex | int | Indeks awal warna RGB. |
| panjang | int | Jumlah piksel RGB yang akan dikonversi. |

**Returns:**
byte[] - Warna CMYK yang disajikan sebagai array byte.
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static int toCmykIcc(Color pixel)
```


Konversi dari warna ARGB ke warna CMYK menggunakan konversi Icc dengan profil default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Warna ARGB. |

**Returns:**
int - Warna CMYK yang disajikan sebagai nilai integer 32-bit.
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


Konversi dari warna ARGB ke warna CMYK menggunakan konversi Icc dengan profil khusus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Warna ARGB. |
| rgbIccStream | java.io.InputStream | Aliran yang berisi profil Icc RGB. |
| cmykIccStream | java.io.InputStream | Aliran yang berisi profil Icc CMYK. |

**Returns:**
int - Warna CMYK yang disajikan sebagai nilai integer 32-bit.
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


Konversi dari warna ARGB ke warna CMYK menggunakan konversi Icc dengan profil default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Warna-warna ARGB. |

**Returns:**
int[] - Warna CMYK yang disajikan sebagai nilai integer 32-bit.
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


Konversi dari warna ARGB ke warna CMYK menggunakan konversi Icc dengan profil khusus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Warna-warna ARGB. |
| rgbIccStream | java.io.InputStream | Aliran yang berisi profil Icc RGB. |
| cmykIccStream | java.io.InputStream | Aliran yang berisi profil Icc CMYK. |

**Returns:**
int[] - Warna CMYK yang disajikan sebagai nilai integer 32-bit.
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Mengonversi RGB ke CMYK menggunakan profil ICC khusus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| piksel | int[] | Warna RGB yang disajikan sebagai nilai integer 32-bit. |
| startIndex | int | Indeks awal warna RGB. |
| panjang | int | Jumlah piksel RGB yang akan dikonversi. |
| rgbIccStream | java.io.InputStream | Aliran profil RGB. |
| cmykIccStream | java.io.InputStream | Aliran profil CMYK. |

**Returns:**
byte[] - Warna CMYK yang disajikan sebagai array byte.
### toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIccBytes-internalized-int---int-int-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static byte[] toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| piksel | int[] |  |
| startIndex | int |  |
| panjang | int |  |
| rgbIccStream | com.aspose.ms.System.IO.Stream |  |
| cmykIccStream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
byte[]
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

