---
title: "Sınıf ColorPalette"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.ColorPalette sınıfı. Bir renk paletini oluşturan renk dizisini tanımlar. Renkler 32 bit ARGB renkleridir. Kalıtılamaz"
type: docs
weight: 370
url: /tr/net/aspose.psd/colorpalette/
---
{{< psd/tize >}}
## ColorPalette class

Bir renk paletini oluşturan renklerin bir dizisini tanımlar. Renkler 32-bit ARGB renkleridir. Kalıtılamaz.

```csharp
public sealed class ColorPalette : IColorPalette
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [ColorPalette](colorpalette/#constructor)(Color[]) | `ColorPalette` sınıfının yeni bir örneğini başlatır ve IsCompactPalette false'tur. |
| [ColorPalette](colorpalette/#constructor_2)(int[]) | `ColorPalette` sınıfının yeni bir örneğini başlatır ve IsCompactPalette false'tur. |
| [ColorPalette](colorpalette/#constructor_1)(Color[], bool) | `ColorPalette` sınıfının yeni bir örneğini başlatır. |
| [ColorPalette](colorpalette/#constructor_3)(int[], bool) | `ColorPalette` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Argb32Entries](../../aspose.psd/colorpalette/argb32entries/) { get; } | 32 bit ARGB yapılarının bir dizisini alır. |
| [Entries](../../aspose.psd/colorpalette/entries/) { get; } | [`Color`](../color/) yapıların bir dizisini alır. |
| [EntriesCount](../../aspose.psd/colorpalette/entriescount/) { get; } | Giriş sayısını alır. |
| [IsCompactPalette](../../aspose.psd/colorpalette/iscompactpalette/) { get; } | Kompakt paletin kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette)(IColorPalette) | Paleti kopyalar. |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | Paleti kopyalar. |
| [GetArgb32Color](../../aspose.psd/colorpalette/getargb32color/)(int) | İndeks ile 32 bit ARGB palet rengini alır. |
| [GetColor](../../aspose.psd/colorpalette/getcolor/)(int) | İndeks ile palet rengini alır. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | En yakın rengin indeksini alır. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | En yakın rengin indeksini alır. |

### Ayrıca Bakınız

* interface [IColorPalette](../icolorpalette/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


