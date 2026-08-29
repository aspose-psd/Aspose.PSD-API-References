---
title: "CmykColorHelper"
second_title: "Aspose.PSD for Java API Справочник"
description: "Вспомогательные методы для работы с CMYK‑цветом, представленным как знаковое 32‑битное целое значение."
type: docs
weight: 18
url: /ru/java/com.aspose.psd/cmykcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

Вспомогательные методы для работы с цветом CMYK, представленным как знаковое 32‑битное целое значение. Предоставляет аналогичный API как у структуры  com.aspose.psd.CmykColor  . Она более легковесна, потому что цвет CMYK представлен просто как Int32, а не как структура с внутренними полями. Пожалуйста, по возможности используйте статические методы этого класса вместо устаревшей структуры  com.aspose.psd.CmykColor  .
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | Создаёт CMYK из 32‑битных значений cyan, magenta, yellow и black. |
| [getC(int cmyk)](#getC-int-) | Получает значение компоненты cyan. |
| [getClass()](#getClass--) |  |
| [getK(int cmyk)](#getK-int-) | Получает значение компоненты black. |
| [getM(int cmyk)](#getM-int-) | Получает значение компоненты magenta. |
| [getY(int cmyk)](#getY-int-) | Получает значение компоненты yellow. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb(int cmykPixel)](#toArgb-int-) | Преобразование цвета CMYK в цвет ARGB. |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | Преобразование цветов CMYK в цвета ARGB. |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | Преобразование цветов CMYK в цвета ARGB. |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | Преобразование из цвета CMYK в цвет ARGB с использованием Icc-конверсии с профилями по умолчанию. |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | Преобразование из цвета CMYK в цвет ARGB с использованием Icc-конверсии с пользовательским профилем. |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | Преобразование из цветов CMYK в цвета ARGB с использованием Icc-конверсии с профилями по умолчанию. |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | Преобразование из цветов CMYK в цвета ARGB с использованием Icc-конверсии с пользовательскими профилями. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | Преобразование из цвета ARGB в цвет CMYK. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | Преобразование из цветов ARGB в цвета CMYK. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | Преобразование из цвета ARGB в цвет CMYK. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | Преобразование из цветов ARGB в цвета CMYK. |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | Преобразует RGB в CMYK. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | Преобразование из цвета ARGB в цвет CMYK с использованием Icc-конверсии с профилями по умолчанию. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | Преобразование из цвета ARGB в цвет CMYK с использованием Icc-конверсии с пользовательскими профилями. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc-конверсии с профилями по умолчанию. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | Преобразование из цветов ARGB в цвета CMYK с использованием Icc-конверсии с пользовательскими профилями. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Преобразует RGB в CMYK с использованием пользовательских ICC профилей. |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


Создаёт CMYK из 32‑битных значений cyan, magenta, yellow и black.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| циан | int | Циановый компонент. Допустимые значения от 0 до 255. |
| пурпурный | int | Магентный компонент. Допустимые значения от 0 до 255. |
| желтый | int | Желтый компонент. Допустимые значения от 0 до 255. |
| черный | int | Черный компонент. Допустимые значения от 0 до 255. |

**Returns:**
int — CMYK‑цвет, представленный как 32‑битное целое значение.
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


Получает значение компоненты cyan.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmyk | int | CMYK‑цвет, представленный как 32‑битное целое значение. |

**Returns:**
int — значение цианового компонента.
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


Получает значение компоненты black.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmyk | int | CMYK‑цвет, представленный как 32‑битное целое значение. |

**Returns:**
int — значение черного компонента.
### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


Получает значение компоненты magenta.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmyk | int | CMYK‑цвет, представленный как 32‑битное целое значение. |

**Returns:**
int — значение магентного компонента.
### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


Получает значение компоненты yellow.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmyk | int | CMYK‑цвет, представленный как 32‑битное целое значение. |

**Returns:**
int — значение желтого компонента.
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


Преобразование цвета CMYK в цвет ARGB.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixel | int | CMYK‑цвет, представленный как 32‑битное целое значение. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


Преобразование цветов CMYK в цвета ARGB.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixels | int[] | CMYK‑цвета, представленные как 32‑битные целочисленные значения. |

**Returns:**
com.aspose.psd.Color[] - ARGB‑цвета.
### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


Преобразование цветов CMYK в цвета ARGB.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixels | int[] | CMYK‑цвета, представленные как 32‑битные целочисленные значения. |

**Returns:**
int[] - ARGB‑цвета, представленные как 32‑битные целочисленные значения.
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


Преобразование из цвета CMYK в цвет ARGB с использованием Icc-конверсии с профилями по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixel | int | CMYK‑цвет, представленный как 32‑битное целое значение. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


Преобразование из цвета CMYK в цвет ARGB с использованием Icc-конверсии с пользовательским профилем.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixel | int | CMYK‑цвет, представленный как 32‑битное целое значение. |
| cmykIccStream | java.io.InputStream | Поток, содержащий профиль CMYK Icc. |
| rgbIccStream | java.io.InputStream | Поток, содержащий профиль RGB Icc. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


Преобразование из цветов CMYK в цвета ARGB с использованием Icc-конверсии с профилями по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixels | int[] | CMYK‑пиксели, представленные как 32‑битные целочисленные значения. |

**Returns:**
com.aspose.psd.Color[] - ARGB‑цвета.
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


Преобразование из цветов CMYK в цвета ARGB с использованием Icc-конверсии с пользовательскими профилями.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixels | int[] | CMYK‑цвета, представленные как 32‑битные целочисленные значения. |
| cmykIccStream | java.io.InputStream | Поток, содержащий профиль CMYK Icc. |
| rgbIccStream | java.io.InputStream | Поток, содержащий профиль RGB Icc. |

**Returns:**
com.aspose.psd.Color[] - ARGB‑цвета.
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static int toCmyk(Color pixel)
```


Преобразование из цвета ARGB в цвет CMYK.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | ARGB‑цвет. |

**Returns:**
int — CMYK‑цвет, представленный как 32‑битное целое значение.
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


Преобразование из цветов ARGB в цвета CMYK.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ARGB‑цвета. |

**Returns:**
int[] - CMYK‑цвета, представленные как 32‑битные целочисленные значения.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


Преобразование из цвета ARGB в цвет CMYK.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argbPixel | int | ARGB‑цвет, представленный как 32‑битное целочисленное значение. |

**Returns:**
int — CMYK‑цвет, представленный как 32‑битное целое значение.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


Преобразование из цветов ARGB в цвета CMYK.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argbPixels | int[] | ARGB‑цвета, представленные как 32‑битные целочисленные значения. |

**Returns:**
int[] - CMYK‑цвета, представленные как 32‑битные целочисленные значения.
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


Преобразует RGB в CMYK.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argbPixels | int[] | RGB‑цвета, представленные как 32‑битные целочисленные значения. |
| startIndex | int | Начальный индекс RGB‑цвета. |
| length | int | Количество RGB‑пикселей для преобразования. |

**Returns:**
byte[] - CMYK‑цвета, представленные как массив байтов.
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static int toCmykIcc(Color pixel)
```


Преобразование из цвета ARGB в цвет CMYK с использованием Icc-конверсии с профилями по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | ARGB‑цвет. |

**Returns:**
int — CMYK‑цвет, представленный как 32‑битное целое значение.
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


Преобразование из цвета ARGB в цвет CMYK с использованием Icc-конверсии с пользовательскими профилями.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | ARGB‑цвет. |
| rgbIccStream | java.io.InputStream | Поток, содержащий профиль RGB Icc. |
| cmykIccStream | java.io.InputStream | Поток, содержащий профиль CMYK Icc. |

**Returns:**
int — CMYK‑цвет, представленный как 32‑битное целое значение.
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


Преобразование из цветов ARGB в цвета CMYK с использованием Icc-конверсии с профилями по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ARGB‑цвета. |

**Returns:**
int[] - CMYK‑цвета, представленные как 32‑битные целочисленные значения.
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


Преобразование из цветов ARGB в цвета CMYK с использованием Icc-конверсии с пользовательскими профилями.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ARGB‑цвета. |
| rgbIccStream | java.io.InputStream | Поток, содержащий профиль RGB Icc. |
| cmykIccStream | java.io.InputStream | Поток, содержащий профиль CMYK Icc. |

**Returns:**
int[] - CMYK‑цвета, представленные как 32‑битные целочисленные значения.
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Преобразует RGB в CMYK с использованием пользовательских ICC профилей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пиксели | int[] | RGB‑цвета, представленные как 32‑битные целочисленные значения. |
| startIndex | int | Начальный индекс RGB‑цвета. |
| length | int | Количество RGB‑пикселей для преобразования. |
| rgbIccStream | java.io.InputStream | Поток профиля RGB. |
| cmykIccStream | java.io.InputStream | Поток профиля CMYK. |

**Returns:**
byte[] - CMYK‑цвета, представленные как массив байтов.
### toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIccBytes-internalized-int---int-int-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static byte[] toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пиксели | int[] |  |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

