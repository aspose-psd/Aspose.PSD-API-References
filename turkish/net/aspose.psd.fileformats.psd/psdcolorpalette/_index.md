---
title: "Sınıf PsdColorPalette"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.PsdColorPalette sınıfı. PSD renk paleti"
type: docs
weight: 4070
url: /tr/net/aspose.psd.fileformats.psd/psdcolorpalette/
---
{{< psd/tize >}}
## PsdColorPalette class

PSD renk paleti.

```csharp
public class PsdColorPalette : IPsdColorPalette
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PsdColorPalette](psdcolorpalette/#constructor_6)(byte[]) | Yeni bir `PsdColorPalette` sınıfı örneği başlatır ve IsCompactPalette false değerindedir. |
| [PsdColorPalette](psdcolorpalette/#constructor)(Color[]) | Yeni bir `PsdColorPalette` sınıfı örneği başlatır ve IsCompactPalette false değerindedir. |
| [PsdColorPalette](psdcolorpalette/#constructor_4)(IColorPalette) | Yeni bir `PsdColorPalette` sınıfı örneği başlatır. |
| [PsdColorPalette](psdcolorpalette/#constructor_7)(byte[], bool) | Yeni bir `PsdColorPalette` sınıfı örneği başlatır. |
| [PsdColorPalette](psdcolorpalette/#constructor_8)(byte[], short) | Yeni bir `PsdColorPalette` sınıfı örneği başlatır ve IsCompactPalette false değerindedir. |
| [PsdColorPalette](psdcolorpalette/#constructor_1)(Color[], bool) | Yeni bir `PsdColorPalette` sınıfı örneği başlatır. |
| [PsdColorPalette](psdcolorpalette/#constructor_2)(Color[], short) | Yeni bir `PsdColorPalette` sınıfı örneği başlatır ve IsCompactPalette false değerindedir. |
| [PsdColorPalette](psdcolorpalette/#constructor_5)(IColorPalette, short) | Yeni bir `PsdColorPalette` sınıfı örneği başlatır. |
| [PsdColorPalette](psdcolorpalette/#constructor_10)(int[], bool) | Yeni bir `PsdColorPalette` sınıfı örneği başlatır. |
| [PsdColorPalette](psdcolorpalette/#constructor_9)(byte[], short, bool) | Yeni bir `PsdColorPalette` sınıfı örneği başlatır. |
| [PsdColorPalette](psdcolorpalette/#constructor_3)(Color[], short, bool) | Yeni bir `PsdColorPalette` sınıfı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Argb32Entries](../../aspose.psd.fileformats.psd/psdcolorpalette/argb32entries/) { get; } | 32-bit ARGB renklerinin bir dizisini alır. |
| [Entries](../../aspose.psd.fileformats.psd/psdcolorpalette/entries/) { get; } | [`Color`](../../aspose.psd/color/) yapıların bir dizisini alır. |
| [EntriesCount](../../aspose.psd.fileformats.psd/psdcolorpalette/entriescount/) { get; } | Giriş sayısını alır. |
| [HasTransparentColor](../../aspose.psd.fileformats.psd/psdcolorpalette/hastransparentcolor/) { get; } | Şeffaf rengin var olup olmadığını gösteren bir değer alır. |
| [IsCompactPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/) { get; } | Paletin sıkıştırılmış olup olmadığını gösteren bir değer alır. |
| [RawEntries](../../aspose.psd.fileformats.psd/psdcolorpalette/rawentries/) { get; } | Ham renk paleti giriş verilerini alır. |
| [RawEntriesCount](../../aspose.psd.fileformats.psd/psdcolorpalette/rawentriescount/) { get; } | Ham renk paleti giriş sayısını alır. |
| [TransparentColor](../../aspose.psd.fileformats.psd/psdcolorpalette/transparentcolor/) { get; } | Şeffaf rengi alır. |
| [TransparentIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/transparentindex/) { get; } | Şeffaf rengin indeksini alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [CopyPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/copypalette/#copypalette)(IColorPalette) | Paleti kopyalar. |
| static [CopyPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | Paleti kopyalar. |
| [GetArgb32Color](../../aspose.psd.fileformats.psd/psdcolorpalette/getargb32color/)(int) | İndeks ile 32 bit ARGB palet rengini alır. |
| [GetColor](../../aspose.psd.fileformats.psd/psdcolorpalette/getcolor/)(int) | İndeks ile palet rengini alır. |
| [GetNearestColorIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | En yakın rengin indeksini alır. |
| [GetNearestColorIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | En yakın rengin indeksini alır. |

### Ayrıca Bakınız

* interface [IPsdColorPalette](../../aspose.psd/ipsdcolorpalette/)
* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


