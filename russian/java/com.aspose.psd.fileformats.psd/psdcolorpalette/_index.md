---
title: "PsdColorPalette"
second_title: "Aspose.PSD for Java API Справочник"
description: "Палитра цветов PSD."
type: docs
weight: 13
url: /ru/java/com.aspose.psd.fileformats.psd/psdcolorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IPsdColorPalette](../../com.aspose.psd/ipsdcolorpalette)
```
public class PsdColorPalette implements IPsdColorPalette
```

Палитра цветов PSD.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PsdColorPalette(IColorPalette colorPalette)](#PsdColorPalette-com.aspose.psd.IColorPalette-) | Инициализирует новый экземпляр класса [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(IColorPalette colorPalette, short transparentIndex)](#PsdColorPalette-com.aspose.psd.IColorPalette-short-) | Инициализирует новый экземпляр класса [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)](#PsdColorPalette-byte---boolean-) | Инициализирует новый экземпляр класса [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData)](#PsdColorPalette-byte---) | Инициализирует новый экземпляр класса [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette), при этом IsCompactPalette имеет значение false. |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-byte---short-boolean-) | Инициализирует новый экземпляр класса [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex)](#PsdColorPalette-byte---short-) | Инициализирует новый экземпляр класса [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette), при этом IsCompactPalette имеет значение false. |
| [PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)](#PsdColorPalette-int---boolean-) | Инициализирует новый экземпляр класса [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---boolean-) | Инициализирует новый экземпляр класса [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries)](#PsdColorPalette-com.aspose.psd.Color---) | Инициализирует новый экземпляр класса [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette), при этом IsCompactPalette имеет значение false. |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---short-boolean-) | Инициализирует новый экземпляр класса [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)](#PsdColorPalette-com.aspose.psd.Color---short-) | Инициализирует новый экземпляр класса [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette), при этом IsCompactPalette имеет значение false. |
## Методы

| Метод | Описание |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | Копирует палитру. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | Копирует палитру. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Получает 32‑битный цвет палитры ARGB по индексу. |
| [getArgb32Entries()](#getArgb32Entries--) | Получает массив 32‑битных цветов ARGB. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | Получает цвет палитры по индексу. |
| [getEntries()](#getEntries--) | Получает массив структур [Color](../../com.aspose.psd/color). |
| [getEntriesCount()](#getEntriesCount--) | Получает количество элементов. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Получает индекс ближайшего цвета. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Получает индекс ближайшего цвета. |
| [getRawEntries()](#getRawEntries--) | Получает необработанные данные записей цветовой палитры. |
| [getRawEntriesCount()](#getRawEntriesCount--) | Получает количество необработанных записей цветовой палитры. |
| [getTransparentColor()](#getTransparentColor--) | Получает прозрачный цвет. |
| [getTransparentIndex()](#getTransparentIndex--) | Получает индекс прозрачного цвета. |
| [hasTransparentColor()](#hasTransparentColor--) | Получает значение, указывающее, существует ли прозрачный цвет. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | Получает значение, указывающее, является ли палитра компактной. |
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


Инициализирует новый экземпляр класса [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Цветовая палитра. |

### PsdColorPalette(IColorPalette colorPalette, short transparentIndex) {#PsdColorPalette-com.aspose.psd.IColorPalette-short-}
```
public PsdColorPalette(IColorPalette colorPalette, short transparentIndex)
```


Инициализирует новый экземпляр класса [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Цветовая палитра. |
| transparentIndex | short | Индекс прозрачного цвета. |

### PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette) {#PsdColorPalette-byte---boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)
```


Инициализирует новый экземпляр класса [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rawEntriesData | byte[] | Необработанные данные записей. |
| isCompactPalette | boolean | Указывает, является ли палитра компактной. |

### PsdColorPalette(byte[] rawEntriesData) {#PsdColorPalette-byte---}
```
public PsdColorPalette(byte[] rawEntriesData)
```


Инициализирует новый экземпляр класса [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette), при этом IsCompactPalette имеет значение false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rawEntriesData | byte[] | Необработанные данные записей. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-byte---short-boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)
```


Инициализирует новый экземпляр класса [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rawEntriesData | byte[] | Необработанные данные записей. |
| transparentIndex | short | Индекс прозрачного цвета. Обратите внимание, что индекс не является индексом необработанных записей, а относится к массиву преобразованных цветов. |
| useCompactPalette | boolean | Указывает, является ли палитра компактной. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex) {#PsdColorPalette-byte---short-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex)
```


Инициализирует новый экземпляр класса [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette), при этом IsCompactPalette имеет значение false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rawEntriesData | byte[] | Необработанные данные записей. |
| transparentIndex | short | Индекс прозрачного цвета. Обратите внимание, что индекс не является индексом необработанных записей, а относится к массиву преобразованных цветов. |

### PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette) {#PsdColorPalette-int---boolean-}
```
public PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)
```


Инициализирует новый экземпляр класса [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorPaletteArgb32Entries | int[] | 32‑битные ARGB‑записи цветовой палитры. |
| isCompactPalette | boolean | Указывает, является ли палитра компактной. |

### PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)
```


Инициализирует новый экземпляр класса [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Записи цветовой палитры. |
| isCompactPalette | boolean | Указывает, является ли палитра компактной. |

### PsdColorPalette(Color[] colorPaletteEntries) {#PsdColorPalette-com.aspose.psd.Color---}
```
public PsdColorPalette(Color[] colorPaletteEntries)
```


Инициализирует новый экземпляр класса [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette), при этом IsCompactPalette имеет значение false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Записи цветовой палитры. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---short-boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)
```


Инициализирует новый экземпляр класса [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Записи цветовой палитры. |
| transparentIndex | short | Индекс прозрачного цвета. |
| useCompactPalette | boolean | Указывает, является ли палитра компактной. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex) {#PsdColorPalette-com.aspose.psd.Color---short-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)
```


Инициализирует новый экземпляр класса [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette), при этом IsCompactPalette имеет значение false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Записи цветовой палитры. |
| transparentIndex | short | Индекс прозрачного цвета. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette)
```


Копирует палитру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Цветовая палитра. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Копирует палитру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Цветовая палитра. |
| useCompactPalette | boolean | Указывает, является ли палитра компактной. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
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
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public final int getArgb32Color(int index)
```


Получает 32‑битный цвет палитры ARGB по индексу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int | 32‑битный ARGB‑индекс цвета палитры. |

**Returns:**
int — Запись цветовой палитры, указанная индексом.
### getArgb32Entries() {#getArgb32Entries--}
```
public final int[] getArgb32Entries()
```


Получает массив 32‑битных цветов ARGB.

**Returns:**
int[] — Массив 32‑битных ARGB‑структур, составляющих эту [ColorPalette](../../com.aspose.psd/colorpalette). Значение: Записи.
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


Получает цвет палитры по индексу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int | Индекс цвета палитры. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public final Color[] getEntries()
```


Получает массив структур [Color](../../com.aspose.psd/color).

**Returns:**
com.aspose.psd.Color[] — Массив структур [Color](../../com.aspose.psd/color), составляющих эту [ColorPalette](../../com.aspose.psd/colorpalette). Значение: Записи.
### getEntriesCount() {#getEntriesCount--}
```
public final int getEntriesCount()
```


Получает количество элементов.

Значение: Количество записей.

**Returns:**
int
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public final int getNearestColorIndex(Color color)
```


Получает индекс ближайшего цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Цвет. |

**Returns:**
int — Индекс ближайшего цвета.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public final int getNearestColorIndex(int argb32Color)
```


Получает индекс ближайшего цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argb32Color | int | 32‑битный цвет ARGB. |

**Returns:**
int — Индекс ближайшего цвета.
### getRawEntries() {#getRawEntries--}
```
public final byte[] getRawEntries()
```


Получает необработанные данные записей цветовой палитры.

Значение: необработанные данные записей цветовой палитры.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public final int getRawEntriesCount()
```


Получает количество необработанных записей цветовой палитры.

Значение: количество необработанных записей цветовой палитры.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public final Color getTransparentColor()
```


Получает прозрачный цвет.

Значение: прозрачный цвет.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public final short getTransparentIndex()
```


Получает индекс прозрачного цвета.

Значение: индекс прозрачного цвета.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public final boolean hasTransparentColor()
```


Получает значение, указывающее, существует ли прозрачный цвет.

Значение:  true  если прозрачный цвет существует; иначе  false .

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


Получает значение, указывающее, является ли палитра компактной.

Значение:  true  если палитра сжата; иначе  false .

--------------------

Сжатая палитра означает, что изображение будет содержать только указанные записи палитры, если это возможно, другими словами изображение будет более компактным и займет меньше места; в противном случае будет 2^BitsPerPixel записей, и изображение зарезервирует больше места для всех возможных записей палитры. Установка этого значения в true и изменение записей палитры могут привести к падению производительности, поскольку может происходить перемещение данных, поэтому используйте это с осторожностью.

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

