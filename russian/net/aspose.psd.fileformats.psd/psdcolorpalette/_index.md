---
title: "Класс PsdColorPalette"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.PsdColorPalette class. Палитра цветов PSD"
type: docs
weight: 4040
url: /ru/net/aspose.psd.fileformats.psd/psdcolorpalette/
---
{{< psd/tize >}}
## PsdColorPalette class

Цветовая палитра PSD.

```csharp
public class PsdColorPalette : IPsdColorPalette
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PsdColorPalette](psdcolorpalette/#constructor_6)(byte[]) | Инициализирует новый экземпляр класса `PsdColorPalette` и IsCompactPalette имеет значение false. |
| [PsdColorPalette](psdcolorpalette/#constructor)(Color[]) | Инициализирует новый экземпляр класса `PsdColorPalette` и IsCompactPalette имеет значение false. |
| [PsdColorPalette](psdcolorpalette/#constructor_4)(IColorPalette) | Инициализирует новый экземпляр класса `PsdColorPalette`. |
| [PsdColorPalette](psdcolorpalette/#constructor_7)(byte[], bool) | Инициализирует новый экземпляр класса `PsdColorPalette`. |
| [PsdColorPalette](psdcolorpalette/#constructor_8)(byte[], short) | Инициализирует новый экземпляр класса `PsdColorPalette` и IsCompactPalette имеет значение false. |
| [PsdColorPalette](psdcolorpalette/#constructor_1)(Color[], bool) | Инициализирует новый экземпляр класса `PsdColorPalette`. |
| [PsdColorPalette](psdcolorpalette/#constructor_2)(Color[], short) | Инициализирует новый экземпляр класса `PsdColorPalette` и IsCompactPalette имеет значение false. |
| [PsdColorPalette](psdcolorpalette/#constructor_5)(IColorPalette, short) | Инициализирует новый экземпляр класса `PsdColorPalette`. |
| [PsdColorPalette](psdcolorpalette/#constructor_10)(int[], bool) | Инициализирует новый экземпляр класса `PsdColorPalette`. |
| [PsdColorPalette](psdcolorpalette/#constructor_9)(byte[], short, bool) | Инициализирует новый экземпляр класса `PsdColorPalette`. |
| [PsdColorPalette](psdcolorpalette/#constructor_3)(Color[], short, bool) | Инициализирует новый экземпляр класса `PsdColorPalette`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Argb32Entries](../../aspose.psd.fileformats.psd/psdcolorpalette/argb32entries/) { get; } | Возвращает массив 32-битных цветов ARGB. |
| [Entries](../../aspose.psd.fileformats.psd/psdcolorpalette/entries/) { get; } | Возвращает массив структур [`Color`](../../aspose.psd/color/). |
| [EntriesCount](../../aspose.psd.fileformats.psd/psdcolorpalette/entriescount/) { get; } | Возвращает количество записей. |
| [HasTransparentColor](../../aspose.psd.fileformats.psd/psdcolorpalette/hastransparentcolor/) { get; } | Возвращает значение, указывающее, существует ли прозрачный цвет. |
| [IsCompactPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/) { get; } | Возвращает значение, указывающее, является ли палитра компактной. |
| [RawEntries](../../aspose.psd.fileformats.psd/psdcolorpalette/rawentries/) { get; } | Возвращает необработанные данные записей палитры цветов. |
| [RawEntriesCount](../../aspose.psd.fileformats.psd/psdcolorpalette/rawentriescount/) { get; } | Возвращает количество необработанных записей палитры цветов. |
| [TransparentColor](../../aspose.psd.fileformats.psd/psdcolorpalette/transparentcolor/) { get; } | Возвращает прозрачный цвет. |
| [TransparentIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/transparentindex/) { get; } | Возвращает индекс прозрачного цвета. |

## Методы

| Имя | Описание |
| --- | --- |
| static [CopyPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/copypalette/#copypalette)(IColorPalette) | Копирует палитру. |
| static [CopyPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | Копирует палитру. |
| [GetArgb32Color](../../aspose.psd.fileformats.psd/psdcolorpalette/getargb32color/)(int) | Возвращает 32‑битный ARGB‑цвет палитры по индексу. |
| [GetColor](../../aspose.psd.fileformats.psd/psdcolorpalette/getcolor/)(int) | Возвращает цвет палитры по индексу. |
| [GetNearestColorIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | Возвращает индекс ближайшего цвета. |
| [GetNearestColorIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | Возвращает индекс ближайшего цвета. |

### См. также

* interface [IPsdColorPalette](../../aspose.psd/ipsdcolorpalette/)
* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


