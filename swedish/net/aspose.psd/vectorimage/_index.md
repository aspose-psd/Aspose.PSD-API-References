---
title: Class VectorImage
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.VectorImage klass. Vektorbilden är basklassen för alla typer av vektorbilder.
type: docs
weight: 5720
url: /sv/net/aspose.psd/vectorimage/
---
## VectorImage class

Vektorbilden är basklassen för alla typer av vektorbilder.

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Hämtar eller ställer in ett värde som anger om paletten för automatisk justering. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Hämtar eller ställer in ett värde för bakgrundsfärgen. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Hämtar bildbitar per pixelantal. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Får bildens gränser. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [Container](../../aspose.psd/image/container/) { get; } | Får[`Image`](../image/) container. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Hämtar objektets dataström. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Får värdet filformat |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Hämtar eller ställer in ett värde som anger om bilden har bakgrundsfärg. |
| override [Height](../../aspose.psd/vectorimage/height/) { get; } | Hämtar bildhöjden. |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf/) { get; } | Hämtar objektets höjd, i tum. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Hämtar eller ställer in avbrottsmonitorn. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Får ett värde som indikerar om objektets data är cachad för närvarande och ingen dataläsning krävs. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Hämtar eller ställer in färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| [Size](../../aspose.psd/image/size/) { get; } | Hämtar bildstorleken. |
| [SizeF](../../aspose.psd/vectorimage/sizef/) { get; } | Hämtar objektstorleken, i tum. |
| override [Width](../../aspose.psd/vectorimage/width/) { get; } | Hämtar bildens bredd. |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf/) { get; } | Hämtar objektets bredd, i tum. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Cachelagrar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från det underliggande[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Bestämmer om bilden kan sparas i det angivna filformatet som representeras av de godkända sparalternativen. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Tar bort den aktuella instansen. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Hämtar standardalternativen. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara till hjälp för att behålla bitdjupet och andra parametrar i originalbilden oförändrade. Om vi till exempel laddar en svartvit PNG-bild med 1 bit per pixel och sedan spara den med hjälp av [`Save`](../datastreamsupporter/save/) metod, kommer den utgående PNG-bilden med 8-bitar per pixel att produceras. För att undvika det och spara PNG-bild med 1-bit per pixel, använd den här metoden för att få motsvarande sparalternativ och skicka dem till[`Save`](../image/save/)metod som den andra parametern. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Ändrar storleken på bilden. StandardenLeftTopToLeftTopanvänds. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ImageResizeSettings) | Ändrar storlek på bilden. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ResizeType) | Ändrar storlek på bilden. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Ändrar storleken på höjden proportionellt. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Ändrar storleken på höjden proportionellt. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Ändrar storleken på höjden proportionellt. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Ändrar storleken på bredden proportionellt. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Ändrar storleken på bredden proportionellt. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Ändrar storleken på bredden proportionellt. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Roterar, vänder eller roterar och vänder bilden. |
| [Save](../../aspose.psd/image/save/)() | Sparar bilddata till den underliggande strömmen. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Sparar objektets data till den angivna strömmen. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Sparar objektets data till den angivna filplatsen. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Sparar objektets data till den angivna filplatsen. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Ställer in bildpaletten. |

### Se även

* class [Image](../image/)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef/)
* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


