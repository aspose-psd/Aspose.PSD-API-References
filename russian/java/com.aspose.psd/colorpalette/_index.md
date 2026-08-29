---
title: "ColorPalette"
second_title: "Aspose.PSD for Java API Справочник"
description: "Определяет массив цветов, составляющих цветовую палитру."
type: docs
weight: 27
url: /ru/java/com.aspose.psd/colorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

Определяет массив цветов, составляющих цветовую палитру. Цвета представлены 32-битными ARGB‑цветами. Не наследуемый.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | Инициализирует новый экземпляр класса  ColorPalette . |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | Инициализирует новый экземпляр класса  ColorPalette , при этом IsCompactPalette равно false. |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.psd.Color---boolean-) | Инициализирует новый экземпляр класса  ColorPalette . |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.psd.Color---) | Инициализирует новый экземпляр класса  ColorPalette , при этом IsCompactPalette равно false. |
## Методы

| Метод | Описание |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | Копирует палитру. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | Копирует палитру. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Получает 32‑битный цвет палитры ARGB по индексу. |
| [getArgb32Entries()](#getArgb32Entries--) | Получает массив 32‑битных ARGB‑структур. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | Получает цвет палитры по индексу. |
| [getEntries()](#getEntries--) | Получает массив структур com.aspose.psd.Color. |
| [getEntriesCount()](#getEntriesCount--) | Получает количество элементов. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Получает индекс ближайшего цвета. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Получает индекс ближайшего цвета. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | Получает или задает значение, указывающее, используется ли компактная палитра. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorPalette(int[] argb32Entries, boolean isCompactPalette) {#ColorPalette-int---boolean-}
```
public ColorPalette(int[] argb32Entries, boolean isCompactPalette)
```


Инициализирует новый экземпляр класса  ColorPalette .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argb32Entries | int[] | Элементы 32-битной ARGB палитры цветов. |
| isCompactPalette | boolean | Указывает, является ли палитра компактной. |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


Инициализирует новый экземпляр класса  ColorPalette , при этом IsCompactPalette равно false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argb32Entries | int[] | Элементы 32-битной ARGB палитры цветов. |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.psd.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


Инициализирует новый экземпляр класса  ColorPalette .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | Записи цветовой палитры. |
| isCompactPalette | boolean | Указывает, является ли палитра компактной. |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.psd.Color---}
```
public ColorPalette(Color[] entries)
```


Инициализирует новый экземпляр класса  ColorPalette , при этом IsCompactPalette равно false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | Записи цветовой палитры. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


Копирует палитру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Цветовая палитра. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Копирует палитру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Цветовая палитра. |
| useCompactPalette | boolean | Указывает, является ли палитра компактной. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
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
public int getArgb32Color(int index)
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
public int[] getArgb32Entries()
```


Получает массив 32‑битных ARGB‑структур.

**Returns:**
int[] - Элементы. Массив 32-битных ARGB структур, составляющих эту Aspose.Imaging.ColorPalette.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor(int index) {#getColor-int-}
```
public Color getColor(int index)
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
public Color[] getEntries()
```


Получает массив структур com.aspose.psd.Color.

**Returns:**
com.aspose.psd.Color[] - Элементы. Массив структур com.aspose.psd.Color, составляющих эту Aspose.Imaging.ColorPalette.
### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Получает количество элементов.

**Returns:**
int - Количество элементов.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public int getNearestColorIndex(Color color)
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
public int getNearestColorIndex(int argb32Color)
```


Получает индекс ближайшего цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argb32Color | int | 32‑битный цвет ARGB. |

**Returns:**
int — Индекс ближайшего цвета.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


Получает или задает значение, указывающее, используется ли компактная палитра.

**Returns:**
boolean -  true  если используется компактная палитра; иначе  false .

Сжатая палитра означает, что изображение будет содержать только указанные записи палитры, если это возможно, другими словами изображение будет более компактным и займет меньше места; в противном случае будет 2^BitsPerPixel записей, и изображение зарезервирует больше места для всех возможных записей палитры. Установка этого значения в true и изменение записей палитры могут привести к падению производительности, поскольку может происходить перемещение данных, поэтому используйте это с осторожностью.
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

