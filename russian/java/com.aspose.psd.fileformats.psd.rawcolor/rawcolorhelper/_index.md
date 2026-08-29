---
title: "RawColorHelper"
second_title: "Aspose.PSD for Java API Справочник"
description: "Класс Raw Color Helper помогает быстрее создавать RawColor, используя предопределённые метаданные каналов."
type: docs
weight: 12
url: /ru/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public class RawColorHelper
```

Raw Color Helper Class помогает быстрее создавать RawColor, используя предопределённые метаданные каналов.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RawColorHelper()](#RawColorHelper--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [createArgb16BitColor(int a, int r, int g, int b)](#createArgb16BitColor-int-int-int-int-) | Создаёт цвет ARGB с 16‑битным разрешением на канал. |
| [createArgb8BitColor(byte a, byte r, byte g, byte b)](#createArgb8BitColor-byte-byte-byte-byte-) | Создаёт цвет ARGB с 8‑битным разрешением на канал. |
| [createArgb8BitColor(Color drawingColor)](#createArgb8BitColor-com.aspose.psd.Color-) | Создаёт цвет ARGB с 8‑битным разрешением на канал из Drawing.Color |
| [createCmyk16BitBitColor(int c, int m, int y, int k)](#createCmyk16BitBitColor-int-int-int-int-) | Создаёт цвет CMYK с 16‑битным разрешением на канал. |
| [createCmyk8BitColor(byte c, byte m, byte y, byte k)](#createCmyk8BitColor-byte-byte-byte-byte-) | Создаёт цвет CMYK с 8‑битным разрешением на канал. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColorHelper() {#RawColorHelper--}
```
public RawColorHelper()
```


### createArgb16BitColor(int a, int r, int g, int b) {#createArgb16BitColor-int-int-int-int-}
```
public static RawColor createArgb16BitColor(int a, int r, int g, int b)
```


Создаёт цвет ARGB с 16‑битным разрешением на канал.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | int | Значение альфа‑компоненты (0‑65535). |
| r | int | Значение красного компонента (0‑65535). |
| g | int | Значение зелёного компонента (0‑65535). |
|  | b | int | Значение синего компонента (0‑65535). |

--------------------

Компоненты цвета упакованы в 64‑битное целое число в следующем порядке: альфа (биты 48‑63), красный (биты 32‑47), зелёный (биты 16‑31) и синий (биты 0‑15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(byte a, byte r, byte g, byte b) {#createArgb8BitColor-byte-byte-byte-byte-}
```
public static RawColor createArgb8BitColor(byte a, byte r, byte g, byte b)
```


Создаёт цвет ARGB с 8‑битным разрешением на канал.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | byte | Значение альфа‑компоненты (0‑255). |
| r | byte | Значение красного компонента (0‑255). |
| g | byte | Значение зелёного компонента (0‑255). |
|  | b | byte | Значение синего компонента (0‑255). |

--------------------

Компоненты цвета упакованы в 32‑битное целое число в следующем порядке: альфа (биты 24‑31), красный (биты 16‑23), зелёный (биты 8‑15) и синий (биты 0‑7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(Color drawingColor) {#createArgb8BitColor-com.aspose.psd.Color-}
```
public static RawColor createArgb8BitColor(Color drawingColor)
```


Создаёт цвет ARGB с 8‑битным разрешением на канал из Drawing.Color

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | drawingColor | [Color](../../com.aspose.psd/color) | Цвет System.Drawing |

--------------------

Компоненты цвета упакованы в 32‑битное целое число в следующем порядке: альфа (биты 24‑31), красный (биты 16‑23), зелёный (биты 8‑15) и синий (биты 0‑7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createCmyk16BitBitColor(int c, int m, int y, int k) {#createCmyk16BitBitColor-int-int-int-int-}
```
public static RawColor createCmyk16BitBitColor(int c, int m, int y, int k)
```


Создаёт цвет CMYK с 16‑битным разрешением на канал.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| c | int | Значение цианового компонента (0‑65535). |
| m | int | Значение пурпурного компонента (0-65535). |
| y | int | Значение желтого компонента (0-65535). |
|  | k | int | Значение ключевого (черного) компонента (0-65535). |

--------------------

Цветовые компоненты упакованы в 64‑битное целое число в следующем порядке: циан (биты 48‑63), пурпурный (биты 32‑47), желтый (биты 16‑31) и ключ/черный (биты 0‑15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
### createCmyk8BitColor(byte c, byte m, byte y, byte k) {#createCmyk8BitColor-byte-byte-byte-byte-}
```
public static RawColor createCmyk8BitColor(byte c, byte m, byte y, byte k)
```


Создаёт цвет CMYK с 8‑битным разрешением на канал.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| c | byte | Значение цианового компонента (0-255). |
| m | byte | Значение пурпурного компонента (0-255). |
| y | byte | Значение желтого компонента (0-255). |
|  | k | byte | Значение ключевого (черного) компонента (0-255). |

--------------------

Цветовые компоненты упакованы в 32‑битное целое число в следующем порядке: циан (биты 24‑31), пурпурный (биты 16‑23), желтый (биты 8‑15) и ключ/черный (биты 0‑7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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

