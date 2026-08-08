---
title: "IColorPalette"
second_title: "Aspose.PSD for Java API Справочник"
description: "Интерфейс цветовой палитры."
type: docs
weight: 117
url: /ru/java/com.aspose.psd/icolorpalette/
---
```
public interface IColorPalette
```

Интерфейс цветовой палитры.
## Методы

| Метод | Описание |
| --- | --- |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Получает 32‑битный цвет палитры ARGB по индексу. |
| [getArgb32Entries()](#getArgb32Entries--) | Получает массив 32‑битных ARGB‑структур. |
| [getColor(int index)](#getColor-int-) | Получает цвет палитры по индексу. |
| [getEntries()](#getEntries--) | Получает массив структур com.aspose.psd.Color. |
| [getEntriesCount()](#getEntriesCount--) | Получает количество элементов. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Получает индекс ближайшего цвета. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Получает индекс ближайшего 32-битного цвета ARGB. |
| [isCompactPalette()](#isCompactPalette--) | Получает значение, указывающее, используется ли компактная палитра. |
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public abstract int getArgb32Color(int index)
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
public abstract int[] getArgb32Entries()
```


Получает массив 32‑битных ARGB‑структур.

**Returns:**
int[] - 32-битные записи ARGB. Массив 32-битных структур ARGB, составляющих этот com.aspose.psd.ColorPalette.
### getColor(int index) {#getColor-int-}
```
public abstract Color getColor(int index)
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
public abstract Color[] getEntries()
```


Получает массив структур com.aspose.psd.Color.

**Returns:**
com.aspose.psd.Color[] - Записи. Массив структуры com.aspose.psd.Color, составляющей этот com.aspose.psd.ColorPalette.
### getEntriesCount() {#getEntriesCount--}
```
public abstract int getEntriesCount()
```


Получает количество элементов.

**Returns:**
int - Количество элементов.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public abstract int getNearestColorIndex(Color color)
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
public abstract int getNearestColorIndex(int argb32Color)
```


Получает индекс ближайшего 32-битного цвета ARGB.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| argb32Color | int | 32‑битный цвет ARGB. |

**Returns:**
int — Индекс ближайшего цвета.
### isCompactPalette() {#isCompactPalette--}
```
public abstract boolean isCompactPalette()
```


Получает значение, указывающее, используется ли компактная палитра.

Сжатая палитра означает, что изображение будет содержать только указанные записи палитры, если это возможно, другими словами изображение будет более компактным и займет меньше места; в противном случае будет 2^BitsPerPixel записей, и изображение зарезервирует больше места для всех возможных записей палитры. Установка этого значения в true и изменение записей палитры могут привести к падению производительности, поскольку может происходить перемещение данных, поэтому используйте это с осторожностью.

**Returns:**
boolean -  true  если используется компактная палитра; иначе  false .
