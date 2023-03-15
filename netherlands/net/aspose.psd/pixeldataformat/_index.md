---
title: Class PixelDataFormat
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.PixelDataFormat klas. Het pixelgegevensformaat. Dit is een onveranderlijk object.
type: docs
weight: 5230
url: /nl/net/aspose.psd/pixeldataformat/
---
## PixelDataFormat class

Het pixelgegevensformaat. Dit is een onveranderlijk object.

```csharp
public class PixelDataFormat
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| static [Cmyk](../../aspose.psd/pixeldataformat/cmyk/) { get; } | Krijgt de`PixelDataFormat` gedefinieerd voor 32 bits per pixel met 8 bits voor cyaan, magenta, geel en zwart. |
| static [Cmyka](../../aspose.psd/pixeldataformat/cmyka/) { get; } | Krijgt de acmyk. |
| static [Grayscale](../../aspose.psd/pixeldataformat/grayscale/) { get; } | Krijgt de`PixelDataFormat`gedefinieerd voor 8 bits per pixel met 8 bits die grijswaardenintensiteit vertegenwoordigen in het interval 0-255. |
| static [GrayscaleAlpha](../../aspose.psd/pixeldataformat/grayscalealpha/) { get; } | Krijgt de`PixelDataFormat` gedefinieerd voor 16 bits per pixel met 8 bits die grijswaardenintensiteit vertegenwoordigen in het 0-255 interval en extra 8 bits alfacomponent. |
| static [Rgb16Bpp555](../../aspose.psd/pixeldataformat/rgb16bpp555/) { get; } | Krijgt de`PixelDataFormat` gedefinieerd voor 16 bits per pixel met 5 bits voor rood, groen en blauw, alfa is niet gedefinieerd. |
| static [Rgb16Bpp565](../../aspose.psd/pixeldataformat/rgb16bpp565/) { get; } | Krijgt de`PixelDataFormat`gedefinieerd voor 16 bits per pixel met 5 bits voor rood, 6 bits voor groen en 5 bits voor blauw, alfa is niet gedefinieerd. |
| static [Rgb24Bpp](../../aspose.psd/pixeldataformat/rgb24bpp/) { get; } | Krijgt de`PixelDataFormat` gedefinieerd voor 24 bits per pixel met 8 bits voor alfa, rood, groen en blauw, alfa is niet gedefinieerd. |
| static [Rgb24BppPng](../../aspose.psd/pixeldataformat/rgb24bpppng/) { get; } | Krijgt de`PixelDataFormat` gedefinieerd voor 24 bits per pixel met 8 bits voor alfa, rood, groen en blauw, alfa is niet gedefinieerd. |
| static [Rgb32Bpp](../../aspose.psd/pixeldataformat/rgb32bpp/) { get; } | Krijgt de`PixelDataFormat` gedefinieerd voor 32 bits per pixel met 8 bits voor alfa, rood, groen en blauw. |
| static [Rgba32Bpp](../../aspose.psd/pixeldataformat/rgba32bpp/) { get; } | Krijgt de`PixelDataFormat` gedefinieerd voor 32 bits per pixel met 8 bits voor alfa, rood, groen en blauw. |
| static [Rgba64Bpp](../../aspose.psd/pixeldataformat/rgba64bpp/) { get; } | Krijgt de`PixelDataFormat` gedefinieerd voor 64 bits per pixel met 16 bits voor alfa, rood, groen en blauw. |
| static [RgbIndexed1Bpp](../../aspose.psd/pixeldataformat/rgbindexed1bpp/) { get; } | Krijgt de`PixelDataFormat` gedefinieerd voor geïndexeerd 1 bit per kleur. De opslag van geïndexeerde pixelgegevens is bedoeld om gegevensopslag en ophalen mogelijk te maken overal waar het kleurenpalet wordt gebruikt. Wees voorzichtig, omdat conversie van het ene palet naar het andere of van RGBA naar geïndexeerd kleurmodel nodig kan zijn . |
| static [RgbIndexed2Bpp](../../aspose.psd/pixeldataformat/rgbindexed2bpp/) { get; } | Krijgt de`PixelDataFormat`gedefinieerd voor geïndexeerd 2 bit per kleur. De opslag van geïndexeerde pixelgegevens is bedoeld om gegevensopslag en -oproep mogelijk te maken overal waar het kleurenpalet wordt gebruikt. Wees voorzichtig, omdat mogelijk conversie van het ene palet naar het andere of van RGBA naar geïndexeerd kleurenmodel nodig is . |
| static [RgbIndexed4Bpp](../../aspose.psd/pixeldataformat/rgbindexed4bpp/) { get; } | Krijgt de`PixelDataFormat` gedefinieerd voor geïndexeerd 4 bit per kleur. De opslag van geïndexeerde pixelgegevens is bedoeld om gegevensopslag en ophalen van gegevens mogelijk te maken overal waar het kleurenpalet wordt gebruikt. Wees voorzichtig, omdat conversie van het ene palet naar het andere of van RGBA naar geïndexeerd kleurmodel nodig kan zijn . |
| static [RgbIndexed8Bpp](../../aspose.psd/pixeldataformat/rgbindexed8bpp/) { get; } | Krijgt de`PixelDataFormat` gedefinieerd voor geïndexeerd 8 bit per kleur. De opslag van geïndexeerde pixelgegevens is bedoeld om gegevensopslag en ophalen overal waar het kleurenpalet wordt gebruikt mogelijk te maken. Wees voorzichtig, omdat conversie van het ene palet naar het andere of van RGBA naar geïndexeerd kleurmodel nodig kan zijn . |
| static [YCbCr](../../aspose.psd/pixeldataformat/ycbcr/) { get; } | Krijgt de`PixelDataFormat` gedefinieerd voor 24 bits per pixel met 8 bits voor elk van de componenten luma, blue-difference en red-difference chroma. |
| static [Ycck](../../aspose.psd/pixeldataformat/ycck/) { get; } | Krijgt de`PixelDataFormat` gedefinieerd voor 32 bits per pixel met 8 bits voor elk van de componenten luma, blue-difference, red-difference en black chroma. |
| [BitsPerPixel](../../aspose.psd/pixeldataformat/bitsperpixel/) { get; } | Haalt de bits per pixel op. |
| [Caption](../../aspose.psd/pixeldataformat/caption/) { get; } | Krijgt het bijschrift van het pixelgegevensformaat. |
| [ChannelBits](../../aspose.psd/pixeldataformat/channelbits/) { get; } | Krijgt het aantal bits voor elk kanaal. |
| [ChannelsCount](../../aspose.psd/pixeldataformat/channelscount/) { get; } | Haalt het aantal kanalen op. |
| [PixelFormat](../../aspose.psd/pixeldataformat/pixelformat/) { get; } | Haalt het pixelformaat op. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [GetBgr](../../aspose.psd/pixeldataformat/getbgr/)(int) | Krijgt BGR-kleur met een gespecificeerd aantal bits per sample. |
| static [GetBgra](../../aspose.psd/pixeldataformat/getbgra/)(int) | Krijgt BGRA-kleur met een opgegeven aantal bits per sample. |
| static [GetCieLab](../../aspose.psd/pixeldataformat/getcielab/)(int, int, int) | Krijgt CIE Lab-kleur met een gespecificeerd aantal bits per sample. |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk)(int) | Krijgt CMYK-kleur met een gespecificeerd aantal bits per sample. |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk_1)(int, int, int, int) | Krijgt CMYK-kleur met een gespecificeerd aantal bits per sample. |
| static [GetCmyka](../../aspose.psd/pixeldataformat/getcmyka/)(int, int, int, int, int) | Krijgt CMYKA-kleur met een gespecificeerd aantal bits per sample. |
| static [GetGrayscale](../../aspose.psd/pixeldataformat/getgrayscale/)(int) | Krijgt grijswaardenkleur met een gespecificeerd aantal bits per sample. |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha)(int) | Krijgt GrayscaleAlpha-kleur met een gespecificeerd aantal bits per sample. |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha_1)(int, int) | Krijgt GrayscaleAlpha-kleur met een gespecificeerd aantal bits per sample. |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb)(int) | Krijgt RGB-kleur met een opgegeven aantal bits per sample. |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb_1)(int, int, int) | Krijgt RGB-kleur met een opgegeven aantal bits per sample. |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba)(int) | Krijgt RGBA-kleur met een opgegeven aantal bits per sample. |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba_1)(int, int, int, int) | Krijgt RGBA-kleur met een opgegeven aantal bits per sample. |
| static [GetRgbIndexed](../../aspose.psd/pixeldataformat/getrgbindexed/)(int) | Krijgt BGRA geïndexeerde kleur met een gespecificeerd aantal bits per sample. |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr)(int) | Krijgt YCbCr-kleur met een gespecificeerd aantal bits per sample. |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr_1)(int, int, int) | Krijgt YCbCr-kleur met een gespecificeerd aantal bits per sample. |
| static [GetYcck](../../aspose.psd/pixeldataformat/getycck/)(int) | Krijgt YCCK-kleur met een gespecificeerd aantal bits per sample. |
| override [Equals](../../aspose.psd/pixeldataformat/equals/)(object) | Bepaalt of de opgegevenObject is gelijk aan deze instantie. |
| override [GetHashCode](../../aspose.psd/pixeldataformat/gethashcode/)() | Retourneert een hash-code voor deze instantie. |
| override [ToString](../../aspose.psd/pixeldataformat/tostring/)() | Geeft als resultaat eenString die deze instantie vertegenwoordigt. |
| [operator ==](../../aspose.psd/pixeldataformat/op_equality/) | Geeft resultaat van gelijkheid voor twee`PixelDataFormat` klassen. |
| [operator !=](../../aspose.psd/pixeldataformat/op_inequality/) | Geeft resultaat van niet-gelijkheid voor twee`PixelDataFormat` klassen. |

### Zie ook

* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


