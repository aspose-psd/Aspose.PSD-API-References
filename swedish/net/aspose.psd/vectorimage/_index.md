---
title: "Klass VectorImage"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.VectorImage-klass. Vektorbilden är basklassen för alla typer av vektorbilder."
type: docs
weight: 6220
url: /sv/net/aspose.psd/vectorimage/
---
{{< psd/tize >}}
## VectorImage class

Vektorbilden är basklassen för alla typer av vektorbilder.

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Hämtar eller anger ett värde som indikerar om paletten justeras automatiskt. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Hämtar eller anger ett värde för bakgrundsfärgen. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Hämtar antalet bildbitar per pixel. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Hämtar bildens gränser. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Hämtar eller anger en hint för buffertstorleken som definierar maximal tillåten storlek för alla interna buffertar. |
| [Container](../../aspose.psd/image/container/) { get; } | Hämtar [`Image`](../image/) behållaren. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Hämtar objektets datastream. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Hämtar ett värde som indikerar om denna instans har frigjorts. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Hämtar ett värde för filformatet |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Hämtar eller anger ett värde som indikerar om bilden har bakgrundsfärg. |
| override [Height](../../aspose.psd/vectorimage/height/) { get; } | Hämtar bildens höjd. |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf/) { get; } | Hämtar objektets höjd, i tum. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Hämtar eller anger avbrottsmotorn. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Hämtar ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Hämtar eller anger färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| [Size](../../aspose.psd/image/size/) { get; } | Hämtar bildstorleken. |
| [SizeF](../../aspose.psd/vectorimage/sizef/) { get; } | Hämtar objektets storlek, i tum. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Hämtar ett värde som indikerar om bildpaletten används. |
| override [Width](../../aspose.psd/vectorimage/width/) { get; } | Hämtar bildbredden. |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf/) { get; } | Hämtar objektets bredd, i tum. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Cachar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från den underliggande [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/). |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Bestämmer om bilden kan sparas till det angivna filformatet som representeras av de överförda sparalternativen. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Frigör den aktuella instansen. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Hämtar standardalternativen. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara användbart för att behålla bitdjup och andra parametrar för den ursprungliga bilden oförändrade. Till exempel, om vi laddar en svartvit PNG-bild med 1 bit per pixel och sedan sparar den med hjälp av [`Save`](../datastreamsupporter/save/) metoden, kommer en PNG-bild med 8 bitar per pixel att produceras. För att undvika detta och spara PNG-bilden med 1 bit per pixel, använd den här metoden för att få motsvarande sparalternativ och skicka dem till [`Save`](../image/save/) metoden som den andra parametern. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Ändrar bildens storlek. Standardvärdet NearestNeighbourResample används. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ImageResizeSettings) | Ändrar bildens storlek. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ResizeType) | Ändrar bildens storlek. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Ändrar höjden proportionellt. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Ändrar höjden proportionellt. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Ändrar höjden proportionellt. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Ändrar bredden proportionellt. Standardvärdet NearestNeighbourResample används. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Ändrar bredden proportionellt. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Ändrar bredden proportionellt. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Rotera, vänd eller rotera och vänd bilden. |
| [Save](../../aspose.psd/image/save/)() | Sparar bilddata till den underliggande strömmen. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Sparar objektets data till den angivna strömmen. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Sparar objektets data till den angivna filplatsen. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativen. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Sparar objektets data till den angivna filplatsen. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativen. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativen. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativen. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Ställer in bildpaletten. |

### Se även

* class [Image](../image/)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


