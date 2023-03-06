---
title: Class ColorPalette
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.ColorPalette sınıf. Bir renk paleti oluşturan bir renk dizisini tanımlar. Renkler 32 bit ARGB renkleridir. Kalıtsal değil.
type: docs
weight: 370
url: /tr/net/aspose.psd/colorpalette/
---
## ColorPalette class

Bir renk paleti oluşturan bir renk dizisini tanımlar. Renkler 32 bit ARGB renkleridir. Kalıtsal değil.

```csharp
public sealed class ColorPalette : IColorPalette
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ColorPalette](colorpalette/#constructor)(Color[]) | Yeni bir örneğini başlatır.`ColorPalette` class ve IsCompactPalette false. |
| [ColorPalette](colorpalette/#constructor_2)(int[]) | Yeni bir örneğini başlatır.`ColorPalette` class ve IsCompactPalette false. |
| [ColorPalette](colorpalette/#constructor_1)(Color[], bool) | Yeni bir örneğini başlatır.`ColorPalette` sınıf. |
| [ColorPalette](colorpalette/#constructor_3)(int[], bool) | Yeni bir örneğini başlatır.`ColorPalette` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Argb32Entries](../../aspose.psd/colorpalette/argb32entries/) { get; } | 32-bit ARGB yapıları dizisi alır. |
| [Entries](../../aspose.psd/colorpalette/entries/) { get; } | Bir dizi alır[`Color`](../color/) yapılar. |
| [EntriesCount](../../aspose.psd/colorpalette/entriescount/) { get; } | Giriş sayısını alır. |
| [IsCompactPalette](../../aspose.psd/colorpalette/iscompactpalette/) { get; } | Kompakt paletin kullanılıp kullanılmadığını gösteren bir değer alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette)(IColorPalette) | Paleti kopyalar. |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | Paleti kopyalar. |
| [GetArgb32Color](../../aspose.psd/colorpalette/getargb32color/)(int) | Dizine göre 32 bit ARGB palet rengini alır. |
| [GetColor](../../aspose.psd/colorpalette/getcolor/)(int) | Palet rengini indekse göre alır. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | En yakın rengin indeksini alır. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | En yakın rengin indeksini alır. |

### Ayrıca bakınız

* interface [IColorPalette](../icolorpalette/)
* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)


