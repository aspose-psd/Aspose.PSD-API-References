---
title: "CmykColor"
second_title: "Java için Aspose.PSD API Referansı"
description: "Pikselin CMYK rengi."
type: docs
weight: 17
url: /tr/java/com.aspose.psd/cmykcolor/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

Pikselin CMYK rengi.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(CmykColor that)](#CloneTo-com.aspose.psd.CmykColor-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | 32 bit cyan, magenta, yellow ve black değerlerinden bir CmykColor yapısı oluşturur. |
| [getC()](#getC--) | Bu com.aspose.psd.Color yapısının cyan bileşen değerini alır. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Boş olanı alır. |
| [getK()](#getK--) | Bu com.aspose.psd.Color yapısının black bileşen değerini alır. |
| [getM()](#getM--) | Bu com.aspose.psd.Color yapısının magenta bileşen değerini alır. |
| [getY()](#getY--) | Bu com.aspose.psd.Color yapısının yellow bileşen değerini alır. |
| [hashCode()](#hashCode--) | Hash kodunu al. |
| [isEmpty()](#isEmpty--) | Bu  com.aspose.psd.Color  yapısının başlatılmamış olup olmadığını gösteren bir değer alır. |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.psd.CmykColor---) | CMYKColor'dan 32-bit ARGB Color'a icc dönüşümüyle varsayılan profiller kullanılarak dönüşüm. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | 32-bit ARGB'den CMYKColor'a dönüşüm. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | 32-bit ARGB renginden CMYKColor'a dönüşüm. |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.psd.CmykColor-) | CMYKColor'dan Color'a dönüşüm. |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.psd.CmykColor---) | CMYKColor'dan Color'a icc dönüşümüyle varsayılan profiller kullanılarak dönüşüm. |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.psd.CmykColor-) | CMYKColor'dan Color'a icc dönüşümüyle varsayılan profiller kullanılarak dönüşüm. |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-) | CMYKColor'dan Color'a icc dönüşümüyle dönüşüm. |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.psd.CmykColor---) | CMYKColor'dan Color'a icc dönüşümüyle varsayılan profiller kullanılarak dönüşüm. |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-) | CMYKColor'dan Color'a icc dönüşümüyle dönüşüm. |
| [toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | CMYKColor'dan Color'a icc dönüşümüyle dönüşüm. |
| [toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | CMYKColor'dan Color'a icc dönüşümüyle dönüşüm. |
| [toString()](#toString--) |  |
| [toValue()](#toValue--) | to değeri. |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(CmykColor that) {#CloneTo-com.aspose.psd.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| that | [CmykColor](../../com.aspose.psd/cmykcolor) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


32-bit cyan, magenta, yellow ve black değerlerinden bir CmykColor yapısı oluşturur. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili CmykColorHelper\#fromComponents(int, int, int, int) yöntemini kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| camgöbeği | int | Camgöbeği bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| macenta | int | Macenta bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| sarı | int | Sarı bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| siyah | int | Siyah bileşeni. Geçerli değerler 0 ile 255 arasındadır. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### getC() {#getC--}
```
public byte getC()
```


Bu com.aspose.psd.Color yapısının cyan bileşen değerini alır.

**Returns:**
byte - Bu com.aspose.psd.Color nesnesinin cyan bileşen değeri.
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


Boş olanı alır.

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### getK() {#getK--}
```
public byte getK()
```


Bu com.aspose.psd.Color yapısının black bileşen değerini alır.

Value: Bu com.aspose.psd.Color nesnesinin black bileşen değeri.

**Returns:**
byte
### getM() {#getM--}
```
public byte getM()
```


Bu com.aspose.psd.Color yapısının magenta bileşen değerini alır.

**Returns:**
byte - Bu com.aspose.psd.Color nesnesinin magenta bileşen değeri.
### getY() {#getY--}
```
public byte getY()
```


Bu com.aspose.psd.Color yapısının yellow bileşen değerini alır.

**Returns:**
byte - Bu com.aspose.psd.Color nesnesinin yellow bileşen değeri.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash kodunu al.

**Returns:**
int - int.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Bu  com.aspose.psd.Color  yapısının başlatılmamış olup olmadığını gösteren bir değer alır.

**Returns:**
boolean - Bu özellik, bu renk başlatılmamışsa true döndürür; aksi takdirde false.
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


CMYKColor'dan 32-bit ARGB Color'a icc dönüşümüyle varsayılan profiller kullanılarak dönüşüm. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili CmykColorHelper.toArgb32(int[]) yöntemini kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK formatındaki CMYKColor tipinin pikselleri. |

**Returns:**
int[] - 32-bit ARGB renginin dizisi.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


32-bit ARGB'den CMYKColor'a dönüşüm. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili CmykColorHelper.toCmyk(int) yöntemini kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argbPixel | int | 32-bit ARGB formatının pikseli. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  Aspose:Imaging:CmykColor .
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


32-bit ARGB renginden CMYKColor'a dönüşüm. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili CmykColorHelper.toCmyk(int[]) yöntemini kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argbPixels | int[] | 32-bit ARGB formatının pikselleri. |

**Returns:**
com.aspose.psd.CmykColor[] -  Aspose:Imaging:CmykColor[] .
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.psd.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


CMYKColor'dan Color'a dönüşüm. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili CmykColorHelper.toArgb(int) yöntemini kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | CMYK formatındaki CMYKColor tipinin pikselleri. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Aspose.Imaging.Color[] .
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.psd.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


CMYKColor'dan Color'a icc dönüşümüyle varsayılan profiller kullanılarak dönüşüm. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili CmykColorHelper.toArgb(int[]) yöntemini kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK formatındaki CMYKColor tipinin pikselleri. |

**Returns:**
com.aspose.psd.Color[] - ARGB renklerinin dizisi.
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.psd.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


CMYKColor'dan Color'a icc dönüşümüyle varsayılan profiller kullanılarak dönüşüm. Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili CmykColorHelper.toArgbIcc(int) yöntemini kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | CMYK formatındaki CMYKColor tipinin pikseli. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


CMYKColor'dan Color'a icc dönüşümü kullanarak dönüşüm. Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili  CmykColorHelper.toArgbIcc(int, Stream, Stream) yöntemini kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | CMYK formatındaki CMYKColor tipinin pikseli. |
| cmykIccStream | java.io.InputStream | icc cmyk profilini içeren akış. |
| rgbIccStream | java.io.InputStream | icc rgb profilini içeren akış. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.psd.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


CMYKColor'dan Color'a varsayılan profillerle icc dönüşümü kullanarak dönüşüm. Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili CmykColorHelper\#toArgbIcc(int[]) yöntemini kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK formatındaki CMYKColor tipinin pikselleri. |

**Returns:**
com.aspose.psd.Color[] - Bu  com.aspose.psd.Color[] .
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


CMYKColor'dan Color'a icc dönüşümü kullanarak dönüşüm. Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili  CmykColorHelper.toArgbIcc(int[], InputStream, InputStream) yöntemini kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK formatındaki CMYKColor tipinin pikselleri. |
| cmykIccStream | java.io.InputStream | icc cmyk profilini içeren akış. |
| rgbIccStream | java.io.InputStream | icc rgb profilini içeren akış. |

**Returns:**
com.aspose.psd.Color[] - Bu  Aspose.Imaging.Color[] .
### toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


CMYKColor'dan Color'a icc dönüşümüyle dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | CMYK formatındaki CMYKColor tipinin pikseli. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | icc cmyk profilini içeren akış. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | icc rgb profilini içeren akış. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color[] toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


CMYKColor'dan Color'a icc dönüşümüyle dönüşüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK formatındaki CMYKColor tipinin pikselleri. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | icc cmyk profilini içeren akış. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | icc rgb profilini içeren akış. |

**Returns:**
com.aspose.psd.Color[] - Bu  Aspose.Imaging.Color[] .
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


to değeri.

**Returns:**
long - Bu  long .
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

