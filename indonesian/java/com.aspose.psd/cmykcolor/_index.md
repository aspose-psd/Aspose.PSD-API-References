---
title: "CmykColor"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Warna CMYK piksel."
type: docs
weight: 17
url: /id/java/com.aspose.psd/cmykcolor/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

Warna CMYK piksel.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(CmykColor that)](#CloneTo-com.aspose.psd.CmykColor-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | Membuat struktur CmykColor dari nilai cyan, magenta, kuning, dan hitam 32-bit. |
| [getC()](#getC--) | Mendapatkan nilai komponen cyan dari struktur com.aspose.psd.Color ini. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Mendapatkan nilai kosong. |
| [getK()](#getK--) | Mendapatkan nilai komponen hitam dari struktur com.aspose.psd.Color ini. |
| [getM()](#getM--) | Mendapatkan nilai komponen magenta dari struktur com.aspose.psd.Color ini. |
| [getY()](#getY--) | Mendapatkan nilai komponen kuning dari struktur com.aspose.psd.Color ini. |
| [hashCode()](#hashCode--) | Metode get hash code. |
| [isEmpty()](#isEmpty--) | Mendapatkan nilai yang menunjukkan apakah struktur  com.aspose.psd.Color  ini belum diinisialisasi. |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.psd.CmykColor---) | Konversi dari CMYKColor ke warna ARGB 32-bit menggunakan konversi icc dengan profil default. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | Konversi dari ARGB 32-bit ke CMYKColor. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | Konversi dari warna ARGB 32-bit ke CMYKColor. |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.psd.CmykColor-) | Konversi dari CMYKColor ke Color. |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.psd.CmykColor---) | Konversi dari CMYKColor ke Color menggunakan konversi icc dengan profil default. |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.psd.CmykColor-) | Konversi dari CMYKColor ke Color menggunakan konversi icc dengan profil default. |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-) | Konversi dari CMYKColor ke Color menggunakan konversi icc. |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.psd.CmykColor---) | Konversi dari CMYKColor ke Color menggunakan konversi icc dengan profil default. |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-) | Konversi dari CMYKColor ke Color menggunakan konversi icc. |
| [toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | Konversi dari CMYKColor ke Color menggunakan konversi icc. |
| [toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | Konversi dari CMYKColor ke Color menggunakan konversi icc. |
| [toString()](#toString--) |  |
| [toValue()](#toValue--) | Nilai to. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CmykColor() {#CmykColor--}
```
public CmykColor()
```


### Clone() {#Clone--}
```
public CmykColor Clone()
```




**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(CmykColor that) {#CloneTo-com.aspose.psd.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| that | [CmykColor](../../com.aspose.psd/cmykcolor) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


Membuat struktur CmykColor dari nilai cyan, magenta, kuning, dan hitam 32-bit. Metode ini sudah usang. Silakan gunakan CmykColorHelper\#fromComponents(int, int, int, int) yang lebih efektif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sian | int | Komponen cyan. Nilai yang valid antara 0 hingga 255. |
| magenta | int | Komponen magenta. Nilai yang valid antara 0 hingga 255. |
| kuning | int | Komponen kuning. Nilai yang valid antara 0 hingga 255. |
| hitam | int | Komponen hitam. Nilai yang valid antara 0 hingga 255. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### getC() {#getC--}
```
public byte getC()
```


Mendapatkan nilai komponen cyan dari struktur com.aspose.psd.Color ini.

**Returns:**
byte - Nilai komponen cyan dari com.aspose.psd.Color ini.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static CmykColor getEmpty()
```


Mendapatkan nilai kosong.

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### getK() {#getK--}
```
public byte getK()
```


Mendapatkan nilai komponen hitam dari struktur com.aspose.psd.Color ini.

Nilai: Nilai komponen hitam dari com.aspose.psd.Color ini.

**Returns:**
byte
### getM() {#getM--}
```
public byte getM()
```


Mendapatkan nilai komponen magenta dari struktur com.aspose.psd.Color ini.

**Returns:**
byte - Nilai komponen magenta dari com.aspose.psd.Color ini.
### getY() {#getY--}
```
public byte getY()
```


Mendapatkan nilai komponen kuning dari struktur com.aspose.psd.Color ini.

**Returns:**
byte - Nilai komponen kuning dari com.aspose.psd.Color ini.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Metode get hash code.

**Returns:**
int - Nilai int.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Mendapatkan nilai yang menunjukkan apakah struktur  com.aspose.psd.Color  ini belum diinisialisasi.

**Returns:**
boolean - Properti ini mengembalikan true jika warna ini belum diinisialisasi; jika tidak, false.
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj1 | [CmykColor](../../com.aspose.psd/cmykcolor) |  |
| obj2 | [CmykColor](../../com.aspose.psd/cmykcolor) |  |

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




### toArgb32(CmykColor[] cmykPixels) {#toArgb32-com.aspose.psd.CmykColor---}
```
public static int[] toArgb32(CmykColor[] cmykPixels)
```


Konversi dari CMYKColor ke warna ARGB 32-bit menggunakan konversi icc dengan profil default. Metode ini sudah usang. Silakan gunakan CmykColorHelper.toArgb32(int[]) yang lebih efektif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Piksel tipe CMYKColor dalam format CMYK. |

**Returns:**
int[] - Array warna ARGB 32-bit.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


Konversi dari ARGB 32-bit ke CMYKColor. Metode ini sudah usang. Silakan gunakan CmykColorHelper.toCmyk(int) yang lebih efektif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| argbPixel | int | Piksel dalam format ARGB 32-bit. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  Aspose:Imaging:CmykColor .
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


Konversi dari warna ARGB 32-bit ke CMYKColor. Metode ini sudah usang. Silakan gunakan CmykColorHelper.toCmyk(int[]) yang lebih efektif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| argbPixels | int[] | Pixel-pixel dari format ARGB 32-bit. |

**Returns:**
com.aspose.psd.CmykColor[] - Aspose:Imaging:CmykColor[] .
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.psd.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


Konversi dari CMYKColor ke Color. Metode ini sudah usang. Silakan gunakan CmykColorHelper.toArgb(int) yang lebih efektif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Piksel tipe CMYKColor dalam format CMYK. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Aspose.Imaging.Color[] .
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.psd.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


Konversi dari CMYKColor ke Color menggunakan konversi icc dengan profil default. Metode ini sudah usang. Silakan gunakan CmykColorHelper.toArgb(int[]) yang lebih efektif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Piksel tipe CMYKColor dalam format CMYK. |

**Returns:**
com.aspose.psd.Color[] - Array dari warna ARGB.
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.psd.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


Konversi dari CMYKColor ke Color menggunakan konversi icc dengan profil default. Metode ini sudah usang. Silakan gunakan CmykColorHelper.toArgbIcc(int) yang lebih efektif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Pixel tipe CMYKColor dalam format CMYK. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


Konversi dari CMYKColor ke Color menggunakan konversi icc. Metode ini sudah usang. Silakan gunakan CmykColorHelper.toArgbIcc(int, Stream, Stream) yang lebih efektif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Pixel tipe CMYKColor dalam format CMYK. |
| cmykIccStream | java.io.InputStream | Aliran yang berisi profil icc cmyk. |
| rgbIccStream | java.io.InputStream | Aliran yang berisi profil icc rgb. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.psd.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


Konversi dari CMYKColor ke Color menggunakan konversi icc dengan profil default. Metode ini sudah usang. Silakan gunakan CmykColorHelper\\#toArgbIcc(int[]) yang lebih efektif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Piksel tipe CMYKColor dalam format CMYK. |

**Returns:**
com.aspose.psd.Color[] - com.aspose.psd.Color[] .
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


Konversi dari CMYKColor ke Color menggunakan konversi icc. Metode ini sudah usang. Silakan gunakan CmykColorHelper.toArgbIcc(int[], InputStream, InputStream) yang lebih efektif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Piksel tipe CMYKColor dalam format CMYK. |
| cmykIccStream | java.io.InputStream | Aliran yang berisi profil icc cmyk. |
| rgbIccStream | java.io.InputStream | Aliran yang berisi profil icc rgb. |

**Returns:**
com.aspose.psd.Color[] - Aspose.Imaging.Color[] .
### toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


Konversi dari CMYKColor ke Color menggunakan konversi icc.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Pixel tipe CMYKColor dalam format CMYK. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | Aliran yang berisi profil icc cmyk. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | Aliran yang berisi profil icc rgb. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color[] toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


Konversi dari CMYKColor ke Color menggunakan konversi icc.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Piksel tipe CMYKColor dalam format CMYK. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | Aliran yang berisi profil icc cmyk. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | Aliran yang berisi profil icc rgb. |

**Returns:**
com.aspose.psd.Color[] - Aspose.Imaging.Color[] .
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toValue() {#toValue--}
```
public long toValue()
```


Nilai to.

**Returns:**
long - long .
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

