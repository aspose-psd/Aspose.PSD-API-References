---
title: Class PixelDataFormat
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.PixelDataFormat klass. Pixeldataformatet. Detta är ett oföränderligt objekt.
type: docs
weight: 5230
url: /sv/net/aspose.psd/pixeldataformat/
---
## PixelDataFormat class

Pixeldataformatet. Detta är ett oföränderligt objekt.

```csharp
public class PixelDataFormat
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [Cmyk](../../aspose.psd/pixeldataformat/cmyk/) { get; } | Får`PixelDataFormat` definieras för 32 bitar per pixel med 8 bitar för var och en av cyan, magenta, gul och svart. |
| static [Cmyka](../../aspose.psd/pixeldataformat/cmyka/) { get; } | Får acmyken. |
| static [Grayscale](../../aspose.psd/pixeldataformat/grayscale/) { get; } | Får`PixelDataFormat`definierad för 8 bitar per pixel med 8 bitar som representerar gråskaleintensitet i intervallet 0-255. |
| static [GrayscaleAlpha](../../aspose.psd/pixeldataformat/grayscalealpha/) { get; } | Får`PixelDataFormat` definierad för 16 bitar per pixel med 8 bitar som representerar gråskaleintensitet i intervallet 0-255 och ytterligare 8 bitars alfakomponent. |
| static [Rgb16Bpp555](../../aspose.psd/pixeldataformat/rgb16bpp555/) { get; } | Får`PixelDataFormat` definierad för 16 bitar per pixel med 5 bitar för var och en av de röda, gröna och blå, alfa är inte definierad. |
| static [Rgb16Bpp565](../../aspose.psd/pixeldataformat/rgb16bpp565/) { get; } | Får`PixelDataFormat`definierad för 16 bitar per pixel med 5 bitar för rött, 6 bitar för grönt och 5 bitar för blått, alfa är inte definierat. |
| static [Rgb24Bpp](../../aspose.psd/pixeldataformat/rgb24bpp/) { get; } | Får`PixelDataFormat` definieras för 24 bitar per pixel med 8 bitar för var och en av alfa, röd, grön och blå, alfa är inte definierad. |
| static [Rgb24BppPng](../../aspose.psd/pixeldataformat/rgb24bpppng/) { get; } | Får`PixelDataFormat` definieras för 24 bitar per pixel med 8 bitar för var och en av alfa, röd, grön och blå, alfa är inte definierad. |
| static [Rgb32Bpp](../../aspose.psd/pixeldataformat/rgb32bpp/) { get; } | Får`PixelDataFormat` definieras för 32 bitar per pixel med 8 bitar för var och en av alfa, röd, grön och blå. |
| static [Rgba32Bpp](../../aspose.psd/pixeldataformat/rgba32bpp/) { get; } | Får`PixelDataFormat` definieras för 32 bitar per pixel med 8 bitar för var och en av alfa, röd, grön och blå. |
| static [Rgba64Bpp](../../aspose.psd/pixeldataformat/rgba64bpp/) { get; } | Får`PixelDataFormat` definierad för 64 bitar per pixel med 16 bitar för var och en av alfa, röd, grön och blå. |
| static [RgbIndexed1Bpp](../../aspose.psd/pixeldataformat/rgbindexed1bpp/) { get; } | Får`PixelDataFormat` definierad för indexerad 1 bit per färg. Den indexerade pixeldatalagringen är avsedd att möjliggöra datalagring och hämtning överallt där färgpaletten används. Använd med försiktighet, eftersom det kan kräva konvertering från en palett till en annan eller från RGBA till indexerad färgmodell . |
| static [RgbIndexed2Bpp](../../aspose.psd/pixeldataformat/rgbindexed2bpp/) { get; } | Får`PixelDataFormat`definierad för indexerad 2 bitar per färg. Den indexerade pixeldatalagringen är avsedd att tillåta datalagring och hämtning överallt där färgpaletten används. Använd med försiktighet, eftersom det kan kräva konvertering från en palett till en annan eller från RGBA till indexerad färgmodell . |
| static [RgbIndexed4Bpp](../../aspose.psd/pixeldataformat/rgbindexed4bpp/) { get; } | Får`PixelDataFormat` definierad för indexerad 4 bitar per färg. Den indexerade pixeldatalagringen är avsedd att tillåta datalagring och hämtning överallt där färgpaletten används. Använd med försiktighet, eftersom det kan kräva konvertering från en palett till en annan eller från RGBA till indexerad färgmodell . |
| static [RgbIndexed8Bpp](../../aspose.psd/pixeldataformat/rgbindexed8bpp/) { get; } | Får`PixelDataFormat` definierad för indexerad 8 bitar per färg. Den indexerade pixeldatalagringen är avsedd att möjliggöra datalagring och hämtning överallt där färgpaletten används. Använd med försiktighet, eftersom det kan kräva konvertering från en palett till en annan eller från RGBA till indexerad färgmodell . |
| static [YCbCr](../../aspose.psd/pixeldataformat/ycbcr/) { get; } | Får`PixelDataFormat` definierad för 24 bitar per pixel med 8 bitar för var och en av luma-, blåskillnads- och rödskillnads-chroma-komponenterna. |
| static [Ycck](../../aspose.psd/pixeldataformat/ycck/) { get; } | Får`PixelDataFormat` definierad för 32 bitar per pixel med 8 bitar för var och en av komponenterna luma, blå-skillnad, röd-skillnad och svart chroma. |
| [BitsPerPixel](../../aspose.psd/pixeldataformat/bitsperpixel/) { get; } | Hämtar bitarna per pixel. |
| [Caption](../../aspose.psd/pixeldataformat/caption/) { get; } | Hämtar bildtexten för pixeldataformat. |
| [ChannelBits](../../aspose.psd/pixeldataformat/channelbits/) { get; } | Får antalet bitar för varje kanal. |
| [ChannelsCount](../../aspose.psd/pixeldataformat/channelscount/) { get; } | Får antalet kanaler. |
| [PixelFormat](../../aspose.psd/pixeldataformat/pixelformat/) { get; } | Hämtar pixelformatet. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [GetBgr](../../aspose.psd/pixeldataformat/getbgr/)(int) | Får BGR-färg med ett specificerat antal bitar per sampel. |
| static [GetBgra](../../aspose.psd/pixeldataformat/getbgra/)(int) | Får BGRA-färg med ett specificerat antal bitar per sampel. |
| static [GetCieLab](../../aspose.psd/pixeldataformat/getcielab/)(int, int, int) | Får CIE Lab-färg med ett specificerat antal bitar per sampel. |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk)(int) | Får CMYK-färg med ett specificerat antal bitar per sampel. |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk_1)(int, int, int, int) | Får CMYK-färg med ett specificerat antal bitar per sampel. |
| static [GetCmyka](../../aspose.psd/pixeldataformat/getcmyka/)(int, int, int, int, int) | Får CMYKA-färg med ett specificerat antal bitar per sampel. |
| static [GetGrayscale](../../aspose.psd/pixeldataformat/getgrayscale/)(int) | Får gråskalefärg med ett specificerat antal bitar per sampel. |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha)(int) | Får GrayscaleAlpha-färg med ett specificerat antal bitar per sampel. |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha_1)(int, int) | Får GrayscaleAlpha-färg med ett specificerat antal bitar per sampel. |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb)(int) | Får RGB-färg med ett specificerat antal bitar per sampel. |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb_1)(int, int, int) | Får RGB-färg med ett specificerat antal bitar per sampel. |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba)(int) | Får RGBA-färg med ett specificerat antal bitar per sampel. |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba_1)(int, int, int, int) | Får RGBA-färg med ett specificerat antal bitar per sampel. |
| static [GetRgbIndexed](../../aspose.psd/pixeldataformat/getrgbindexed/)(int) | Får BGRA-indexerad färg med ett specificerat antal bitar per sampel. |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr)(int) | Får YCbCr-färg med ett specificerat antal bitar per sampel. |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr_1)(int, int, int) | Får YCbCr-färg med ett specificerat antal bitar per sampel. |
| static [GetYcck](../../aspose.psd/pixeldataformat/getycck/)(int) | Får YCCK-färg med ett specificerat antal bitar per sampel. |
| override [Equals](../../aspose.psd/pixeldataformat/equals/)(object) | Bestämmer om den angivnaObject är lika med denna instans. |
| override [GetHashCode](../../aspose.psd/pixeldataformat/gethashcode/)() | Returnerar en hash-kod för denna instans. |
| override [ToString](../../aspose.psd/pixeldataformat/tostring/)() | Returnerar enString som representerar denna instans. |
| [operator ==](../../aspose.psd/pixeldataformat/op_equality/) | Returnerar resultatet av likhet för två`PixelDataFormat` klasser. |
| [operator !=](../../aspose.psd/pixeldataformat/op_inequality/) | Returnerar resultatet av icke-likhet för två`PixelDataFormat` klasser. |

### Se även

* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


