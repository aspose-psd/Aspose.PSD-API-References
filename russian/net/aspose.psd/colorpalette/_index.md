---
title: "Класс ColorPalette"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.ColorPalette. Определяет массив цветов, составляющих цветовую палитру. Цвета представлены 32‑битными ARGB‑значениями. Не наследуемый"
type: docs
weight: 370
url: /ru/net/aspose.psd/colorpalette/
---
{{< psd/tize >}}
## ColorPalette class

Определяет массив цветов, составляющих цветовую палитру. Цвета — 32‑битные ARGB‑цвета. Не наследуемый.

```csharp
public sealed class ColorPalette : IColorPalette
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ColorPalette](colorpalette/#constructor)(Color[]) | Инициализирует новый экземпляр класса `ColorPalette` и свойство IsCompactPalette равно false. |
| [ColorPalette](colorpalette/#constructor_2)(int[]) | Инициализирует новый экземпляр класса `ColorPalette` и свойство IsCompactPalette равно false. |
| [ColorPalette](colorpalette/#constructor_1)(Color[], bool) | Инициализирует новый экземпляр класса `ColorPalette`. |
| [ColorPalette](colorpalette/#constructor_3)(int[], bool) | Инициализирует новый экземпляр класса `ColorPalette`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Argb32Entries](../../aspose.psd/colorpalette/argb32entries/) { get; } | Возвращает массив 32‑битных ARGB‑структур. |
| [Entries](../../aspose.psd/colorpalette/entries/) { get; } | Возвращает массив структур [`Color`](../color/). |
| [EntriesCount](../../aspose.psd/colorpalette/entriescount/) { get; } | Возвращает количество записей. |
| [IsCompactPalette](../../aspose.psd/colorpalette/iscompactpalette/) { get; } | Получает или задает значение, указывающее, используется ли компактная палитра. |

## Методы

| Имя | Описание |
| --- | --- |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette)(IColorPalette) | Копирует палитру. |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | Копирует палитру. |
| [GetArgb32Color](../../aspose.psd/colorpalette/getargb32color/)(int) | Возвращает 32‑битный ARGB‑цвет палитры по индексу. |
| [GetColor](../../aspose.psd/colorpalette/getcolor/)(int) | Возвращает цвет палитры по индексу. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | Возвращает индекс ближайшего цвета. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | Возвращает индекс ближайшего цвета. |

### См. также

* interface [IColorPalette](../icolorpalette/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


