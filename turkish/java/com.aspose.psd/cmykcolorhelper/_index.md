---
title: "CmykColorHelper"
second_title: "Java için Aspose.PSD API Referansı"
description: "İmzalı 32-bit tamsayı değeri olarak sunulan CMYK rengiyle çalışmak için yardımcı yöntemler."
type: docs
weight: 18
url: /tr/java/com.aspose.psd/cmykcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

CMYK rengini imzalı 32-bit tamsayı değeri olarak sunan yardımcı yöntemler.  com.aspose.psd.CmykColor  yapısı gibi benzer bir API sağlar. CMYK rengi sadece Int32 olarak sunulduğu için, iç alanları olan bir yapı yerine daha hafiftir. Mümkün olduğunda, kullanımdan kaldırılmış  com.aspose.psd.CmykColor  yapısı yerine bu sınıfın statik yöntemlerini tercih edin.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | 32-bit cyan, magenta, yellow ve black değerlerinden CMYK oluşturur. |
| [getC(int cmyk)](#getC-int-) | Cyan bileşen değerini alır. |
| [getClass()](#getClass--) |  |
| [getK(int cmyk)](#getK-int-) | Black bileşen değerini alır. |
| [getM(int cmyk)](#getM-int-) | Magenta bileşen değerini alır. |
| [getY(int cmyk)](#getY-int-) | Yellow bileşen değerini alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb(int cmykPixel)](#toArgb-int-) | CMYK renginden ARGB rengine dönüşüm. |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | CMYK renklerinden ARGB renklerine dönüşüm. |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | CMYK renklerinden ARGB renklerine dönüşüm. |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | CMYK renginden ARGB Rengine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm. |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | CMYK renginden ARGB rengine, özel profil ile Icc dönüşümü kullanılarak dönüşüm. |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | CMYK renklerinden ARGB renklerine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm. |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | CMYK renklerinden ARGB renklerine, özel profillerle Icc dönüşümü kullanılarak dönüşüm. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | ARGB renginden CMYK rengine dönüşüm. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | ARGB renklerinden CMYK renklerine dönüşüm. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | ARGB renginden CMYK rengine dönüşüm. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | ARGB renklerinden CMYK renklerine dönüşüm. |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | RGB'yi CMYK'ye dönüştürür. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | ARGB renginden CMYK rengine, varsayılan profillerle Icc dönüşümü kullanarak dönüşüm. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | ARGB renginden CMYK rengine, özel profillerle Icc dönüşümü kullanarak dönüşüm. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | ARGB renklerinden CMYK renklerine, varsayılan profillerle Icc dönüşümü kullanarak dönüşüm. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | ARGB renklerinden CMYK renklerine, özel profillerle Icc dönüşümü kullanarak dönüşüm. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | RGB'yi, özel ICC profilleri kullanarak CMYK'ye dönüştürür. |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


32-bit cyan, magenta, yellow ve black değerlerinden CMYK oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| camgöbeği | int | Camgöbeği bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| macenta | int | Macenta bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| sarı | int | Sarı bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| siyah | int | Siyah bileşeni. Geçerli değerler 0 ile 255 arasındadır. |

**Returns:**
int - CMYK rengi 32-bit tam sayı değeri olarak sunar.
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


Cyan bileşen değerini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmyk | int | CMYK rengi 32-bit tam sayı değeri olarak sunar. |

**Returns:**
int - Camgöbeği bileşen değeri.
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


Black bileşen değerini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmyk | int | CMYK rengi 32-bit tam sayı değeri olarak sunar. |

**Returns:**
int - Siyah bileşen değeri.
### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


Magenta bileşen değerini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmyk | int | CMYK rengi 32-bit tam sayı değeri olarak sunar. |

**Returns:**
int - Macenta bileşen değeri.
### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


Yellow bileşen değerini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmyk | int | CMYK rengi 32-bit tam sayı değeri olarak sunar. |

**Returns:**
int - Sarı bileşen değeri.
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


CMYK renginden ARGB rengine dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixel | int | CMYK rengi 32-bit tam sayı değeri olarak sunar. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


CMYK renklerinden ARGB renklerine dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixels | int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunar. |

**Returns:**
com.aspose.psd.Color[] - ARGB renkleri.
### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


CMYK renklerinden ARGB renklerine dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixels | int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunar. |

**Returns:**
int[] - ARGB renkleri 32-bit tam sayı değerleri olarak sunar.
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


CMYK renginden ARGB Rengine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixel | int | CMYK rengi 32-bit tam sayı değeri olarak sunar. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


CMYK renginden ARGB rengine, özel profil ile Icc dönüşümü kullanılarak dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixel | int | CMYK rengi 32-bit tam sayı değeri olarak sunar. |
| cmykIccStream | java.io.InputStream | CMYK Icc profilini içeren akış. |
| rgbIccStream | java.io.InputStream | RGB Icc profilini içeren akış. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


CMYK renklerinden ARGB renklerine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixels | int[] | CMYK pikselleri 32-bit tamsayı değerleri olarak sunulur. |

**Returns:**
com.aspose.psd.Color[] - ARGB renkleri.
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


CMYK renklerinden ARGB renklerine, özel profillerle Icc dönüşümü kullanılarak dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixels | int[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunar. |
| cmykIccStream | java.io.InputStream | CMYK Icc profilini içeren akış. |
| rgbIccStream | java.io.InputStream | RGB Icc profilini içeren akış. |

**Returns:**
com.aspose.psd.Color[] - ARGB renkleri.
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static int toCmyk(Color pixel)
```


ARGB renginden CMYK rengine dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | ARGB rengi. |

**Returns:**
int - CMYK rengi 32-bit tam sayı değeri olarak sunar.
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ARGB renkleri. |

**Returns:**
int[] - CMYK renkleri 32-bit tamsayı değerleri olarak sunulur.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


ARGB renginden CMYK rengine dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argbPixel | int | ARGB rengi 32-bit tamsayı değeri olarak sunulur. |

**Returns:**
int - CMYK rengi 32-bit tam sayı değeri olarak sunar.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


ARGB renklerinden CMYK renklerine dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argbPixels | int[] | ARGB renkleri 32-bit tamsayı değerleri olarak sunulur. |

**Returns:**
int[] - CMYK renkleri 32-bit tamsayı değerleri olarak sunulur.
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


RGB'yi CMYK'ye dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argbPixels | int[] | RGB renkleri 32-bit tamsayı değerleri olarak sunulur. |
| startIndex | int | RGB renginin başlangıç indeksi. |
| length | int | Dönüştürülecek RGB piksel sayısı. |

**Returns:**
byte[] - CMYK renkleri bayt dizisi olarak sunulur.
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static int toCmykIcc(Color pixel)
```


ARGB renginden CMYK rengine, varsayılan profillerle Icc dönüşümü kullanarak dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | ARGB rengi. |

**Returns:**
int - CMYK rengi 32-bit tam sayı değeri olarak sunar.
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


ARGB renginden CMYK rengine, özel profillerle Icc dönüşümü kullanarak dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | ARGB rengi. |
| rgbIccStream | java.io.InputStream | RGB Icc profilini içeren akış. |
| cmykIccStream | java.io.InputStream | CMYK Icc profilini içeren akış. |

**Returns:**
int - CMYK rengi 32-bit tam sayı değeri olarak sunar.
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


ARGB renklerinden CMYK renklerine, varsayılan profillerle Icc dönüşümü kullanarak dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ARGB renkleri. |

**Returns:**
int[] - CMYK renkleri 32-bit tamsayı değerleri olarak sunulur.
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


ARGB renklerinden CMYK renklerine, özel profillerle Icc dönüşümü kullanarak dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ARGB renkleri. |
| rgbIccStream | java.io.InputStream | RGB Icc profilini içeren akış. |
| cmykIccStream | java.io.InputStream | CMYK Icc profilini içeren akış. |

**Returns:**
int[] - CMYK renkleri 32-bit tamsayı değerleri olarak sunulur.
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


RGB'yi, özel ICC profilleri kullanarak CMYK'ye dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| piksel | int[] | RGB renkleri 32-bit tamsayı değerleri olarak sunulur. |
| startIndex | int | RGB renginin başlangıç indeksi. |
| length | int | Dönüştürülecek RGB piksel sayısı. |
| rgbIccStream | java.io.InputStream | RGB profil akışı. |
| cmykIccStream | java.io.InputStream | CMYK profil akışı. |

**Returns:**
byte[] - CMYK renkleri bayt dizisi olarak sunulur.
### toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIccBytes-internalized-int---int-int-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static byte[] toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| piksel | int[] |  |
| startIndex | int |  |
| length | int |  |
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

