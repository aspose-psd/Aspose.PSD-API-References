---
title: "CmykColor"
second_title: "Aspose.PSD for Java API Справочник"
description: "CMYK‑цвет пикселя."
type: docs
weight: 17
url: /ru/java/com.aspose.psd/cmykcolor/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

CMYK‑цвет пикселя.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(CmykColor that)](#CloneTo-com.aspose.psd.CmykColor-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | Создаёт структуру  CmykColor  из 32‑битных значений циана, мадженты, жёлтого и чёрного цветов. |
| [getC()](#getC--) | Получает значение компоненты циана этой структуры  com.aspose.psd.Color . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Получает пустое. |
| [getK()](#getK--) | Получает значение черного компонента этой  com.aspose.psd.Color  структуры. |
| [getM()](#getM--) | Получает значение пурпурного компонента этой  com.aspose.psd.Color  структуры. |
| [getY()](#getY--) | Получает значение желтого компонента этой  com.aspose.psd.Color  структуры. |
| [hashCode()](#hashCode--) | Получить хеш-код. |
| [isEmpty()](#isEmpty--) | Возвращает значение, указывающее, является ли эта структура  com.aspose.psd.Color неинициализированной. |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.psd.CmykColor---) | Преобразование из CMYKColor в 32-битный ARGB Color с использованием ICC-преобразования и профилей по умолчанию. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | Преобразование из 32-битного ARGB в CMYKColor. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | Преобразование из 32-битного ARGB цвета в CMYKColor. |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.psd.CmykColor-) | Преобразование из CMYKColor в Color. |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.psd.CmykColor---) | Преобразование из CMYKColor в Color с использованием ICC-преобразования и профилей по умолчанию. |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.psd.CmykColor-) | Преобразование из CMYKColor в Color с использованием ICC-преобразования и профилей по умолчанию. |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-) | Преобразование из CMYKColor в Color с использованием ICC-преобразования. |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.psd.CmykColor---) | Преобразование из CMYKColor в Color с использованием ICC-преобразования и профилей по умолчанию. |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-) | Преобразование из CMYKColor в Color с использованием ICC-преобразования. |
| [toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | Преобразование из CMYKColor в Color с использованием ICC-преобразования. |
| [toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | Преобразование из CMYKColor в Color с использованием ICC-преобразования. |
| [toString()](#toString--) |  |
| [toValue()](#toValue--) | Значение to. |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(CmykColor that) {#CloneTo-com.aspose.psd.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| that | [CmykColor](../../com.aspose.psd/cmykcolor) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


Создает структуру  CmykColor  из 32-битных значений циана, пурпурного, желтого и черного. Этот метод устарел. Пожалуйста, используйте более эффективный CmykColorHelper\#fromComponents(int, int, int, int).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| циан | int | Циановый компонент. Допустимые значения от 0 до 255. |
| пурпурный | int | Магентный компонент. Допустимые значения от 0 до 255. |
| желтый | int | Желтый компонент. Допустимые значения от 0 до 255. |
| черный | int | Черный компонент. Допустимые значения от 0 до 255. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### getC() {#getC--}
```
public byte getC()
```


Получает значение компоненты циана этой структуры  com.aspose.psd.Color .

**Returns:**
byte - Значение компонента циана этой  com.aspose.psd.Color .
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


Получает пустое.

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### getK() {#getK--}
```
public byte getK()
```


Получает значение черного компонента этой  com.aspose.psd.Color  структуры.

Значение: Значение черного компонента этой  com.aspose.psd.Color .

**Returns:**
byte
### getM() {#getM--}
```
public byte getM()
```


Получает значение пурпурного компонента этой  com.aspose.psd.Color  структуры.

**Returns:**
byte - Значение компонента пурпурного этой  com.aspose.psd.Color .
### getY() {#getY--}
```
public byte getY()
```


Получает значение желтого компонента этой  com.aspose.psd.Color  структуры.

**Returns:**
byte - Значение желтого компонента этой  com.aspose.psd.Color .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Получить хеш-код.

**Returns:**
int - Тип int.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Возвращает значение, указывающее, является ли эта структура  com.aspose.psd.Color неинициализированной.

**Returns:**
boolean - Это свойство возвращает true, если этот цвет не инициализирован; иначе — false.
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| Параметр | Тип | Описание |
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


Преобразование из CMYKColor в 32-битный ARGB Color с использованием ICC-преобразования и профилей по умолчанию. Этот метод устарел. Пожалуйста, используйте более эффективный  CmykColorHelper.toArgb32(int[]) .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Пиксели типа CMYKColor в формате CMYK. |

**Returns:**
int[] - Массив 32-битных ARGB цветов.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


Преобразование из 32-битного ARGB в CMYKColor. Этот метод устарел. Пожалуйста, используйте более эффективный  CmykColorHelper.toCmyk(int) .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argbPixel | int | Пиксель формата 32-битный ARGB. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  Aspose:Imaging:CmykColor .
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


Преобразование из 32-битного ARGB цвета в CMYKColor. Этот метод устарел. Пожалуйста, используйте более эффективный  CmykColorHelper.toCmyk(int[]) .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argbPixels | int[] | Пиксели формата 32-битный ARGB. |

**Returns:**
com.aspose.psd.CmykColor[] - Aspose:Imaging:CmykColor[].
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.psd.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


Преобразование из CMYKColor в Color. Этот метод устарел. Пожалуйста, используйте более эффективный CmykColorHelper.toArgb(int).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Пиксели типа CMYKColor в формате CMYK. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Aspose.Imaging.Color[] .
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.psd.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


Преобразование из CMYKColor в Color с использованием icc‑конверсии и профилей по умолчанию. Этот метод устарел. Пожалуйста, используйте более эффективный CmykColorHelper.toArgb(int[]).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Пиксели типа CMYKColor в формате CMYK. |

**Returns:**
com.aspose.psd.Color[] — массив цветов ARGB.
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.psd.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


Преобразование из CMYKColor в Color с использованием icc‑конверсии и профилей по умолчанию. Этот метод устарел. Пожалуйста, используйте более эффективный CmykColorHelper.toArgbIcc(int).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Пиксель типа CMYKColor в формате CMYK. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


Преобразование из CMYKColor в Color с использованием icc‑конверсии. Этот метод устарел. Пожалуйста, используйте более эффективный CmykColorHelper.toArgbIcc(int, Stream, Stream).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Пиксель типа CMYKColor в формате CMYK. |
| cmykIccStream | java.io.InputStream | Поток, содержащий профиль ICC CMYK. |
| rgbIccStream | java.io.InputStream | Поток, содержащий профиль ICC RGB. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.psd.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


Преобразование из CMYKColor в Color с использованием icc‑конверсии и профилей по умолчанию. Этот метод устарел. Пожалуйста, используйте более эффективный CmykColorHelper\#toArgbIcc(int[]).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Пиксели типа CMYKColor в формате CMYK. |

**Returns:**
com.aspose.psd.Color[] —  com.aspose.psd.Color[].
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


Преобразование из CMYKColor в Color с использованием icc‑конверсии. Этот метод устарел. Пожалуйста, используйте более эффективный CmykColorHelper.toArgbIcc(int[], InputStream, InputStream).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Пиксели типа CMYKColor в формате CMYK. |
| cmykIccStream | java.io.InputStream | Поток, содержащий профиль ICC CMYK. |
| rgbIccStream | java.io.InputStream | Поток, содержащий профиль ICC RGB. |

**Returns:**
com.aspose.psd.Color[] —  Aspose.Imaging.Color[].
### toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


Преобразование из CMYKColor в Color с использованием ICC-преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Пиксель типа CMYKColor в формате CMYK. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | Поток, содержащий профиль ICC CMYK. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | Поток, содержащий профиль ICC RGB. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color[] toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


Преобразование из CMYKColor в Color с использованием ICC-преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Пиксели типа CMYKColor в формате CMYK. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | Поток, содержащий профиль ICC CMYK. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | Поток, содержащий профиль ICC RGB. |

**Returns:**
com.aspose.psd.Color[] —  Aspose.Imaging.Color[].
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


Значение to.

**Returns:**
long —  long.
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

