---
title: Class PsdColorPalette
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.PsdColorPalette сорт. Цветовая палитра PSD.
type: docs
weight: 3580
url: /ru/net/aspose.psd.fileformats.psd/psdcolorpalette/
---
## PsdColorPalette class

Цветовая палитра PSD.

```csharp
public class PsdColorPalette : IPsdColorPalette
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PsdColorPalette](psdcolorpalette/#constructor_6)(byte[]) | Инициализирует новый экземпляр`PsdColorPalette` класс, а IsCompactPalette имеет значение false. |
| [PsdColorPalette](psdcolorpalette/#constructor)(Color[]) | Инициализирует новый экземпляр`PsdColorPalette` класс, а IsCompactPalette имеет значение false. |
| [PsdColorPalette](psdcolorpalette/#constructor_4)(IColorPalette) | Инициализирует новый экземпляр`PsdColorPalette` класс. |
| [PsdColorPalette](psdcolorpalette/#constructor_7)(byte[], bool) | Инициализирует новый экземпляр`PsdColorPalette` класс. |
| [PsdColorPalette](psdcolorpalette/#constructor_8)(byte[], short) | Инициализирует новый экземпляр`PsdColorPalette` класс, а IsCompactPalette имеет значение false. |
| [PsdColorPalette](psdcolorpalette/#constructor_1)(Color[], bool) | Инициализирует новый экземпляр`PsdColorPalette` класс. |
| [PsdColorPalette](psdcolorpalette/#constructor_2)(Color[], short) | Инициализирует новый экземпляр`PsdColorPalette` класс, а IsCompactPalette имеет значение false. |
| [PsdColorPalette](psdcolorpalette/#constructor_5)(IColorPalette, short) | Инициализирует новый экземпляр`PsdColorPalette` класс. |
| [PsdColorPalette](psdcolorpalette/#constructor_10)(int[], bool) | Инициализирует новый экземпляр`PsdColorPalette` класс. |
| [PsdColorPalette](psdcolorpalette/#constructor_9)(byte[], short, bool) | Инициализирует новый экземпляр`PsdColorPalette` класс. |
| [PsdColorPalette](psdcolorpalette/#constructor_3)(Color[], short, bool) | Инициализирует новый экземпляр`PsdColorPalette` класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Argb32Entries](../../aspose.psd.fileformats.psd/psdcolorpalette/argb32entries/) { get; } | Получает массив 32-битных цветов ARGB. |
| [Entries](../../aspose.psd.fileformats.psd/psdcolorpalette/entries/) { get; } | Получает массив[`Color`](../../aspose.psd/color/) структуры. |
| [EntriesCount](../../aspose.psd.fileformats.psd/psdcolorpalette/entriescount/) { get; } | Получает количество записей. |
| [HasTransparentColor](../../aspose.psd.fileformats.psd/psdcolorpalette/hastransparentcolor/) { get; } | Получает значение, указывающее, существует ли прозрачный цвет. |
| [IsCompactPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/) { get; } | Получает значение, указывающее, сжимается ли палитра. |
| [RawEntries](../../aspose.psd.fileformats.psd/psdcolorpalette/rawentries/) { get; } | Получает данные необработанных записей цветовой палитры. |
| [RawEntriesCount](../../aspose.psd.fileformats.psd/psdcolorpalette/rawentriescount/) { get; } | Получает количество записей исходной цветовой палитры. |
| [TransparentColor](../../aspose.psd.fileformats.psd/psdcolorpalette/transparentcolor/) { get; } | Получает прозрачный цвет. |
| [TransparentIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/transparentindex/) { get; } | Получает индекс прозрачного цвета. |

## Методы

| Имя | Описание |
| --- | --- |
| static [CopyPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/copypalette/#copypalette)(IColorPalette) | Копирует палитру. |
| static [CopyPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | Копирует палитру. |
| [GetArgb32Color](../../aspose.psd.fileformats.psd/psdcolorpalette/getargb32color/)(int) | Получает 32-битный цвет палитры ARGB по индексу. |
| [GetColor](../../aspose.psd.fileformats.psd/psdcolorpalette/getcolor/)(int) | Получает цвет палитры по индексу. |
| [GetNearestColorIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | Получает индекс ближайшего цвета. |
| [GetNearestColorIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | Получает индекс ближайшего цвета. |

### Смотрите также

* interface [IPsdColorPalette](../../aspose.psd/ipsdcolorpalette/)
* пространство имен [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* сборка [Aspose.PSD](../../)


