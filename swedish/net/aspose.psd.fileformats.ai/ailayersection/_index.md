---
title: "Klass AiLayerSection"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Ai.AiLayerSection klass. Den Ai format Layer Section"
type: docs
weight: 1280
url: /sv/net/aspose.psd.fileformats.ai/ailayersection/
---
{{< psd/tize >}}
## AiLayerSection class

Ai-formatets lagersektion

```csharp
public sealed class AiLayerSection : AiDataSection
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Blue](../../aspose.psd.fileformats.ai/ailayersection/blue/) { get; set; } | Hämtar eller anger den blå färgkomponenten. |
| [ColorIndex](../../aspose.psd.fileformats.ai/ailayersection/colorindex/) { get; set; } | Hämtar eller anger färgindexet. Detta argument kan ha värden mellan –1 och 26. Varje heltal representerar en färg som kan tilldelas lagret för användaridentifieringsändamål. |
| [ColorNumber](../../aspose.psd.fileformats.ai/ailayersection/colornumber/) { get; set; } | Hämtar eller anger färgnumret. -1 är det anpassade färgvärdet från egenskaperna Röd, Grön, Blå. Anger lagrets färginställning. |
| [DimValue](../../aspose.psd.fileformats.ai/ailayersection/dimvalue/) { get; set; } | Hämtar eller anger dimningsvärdet som procent. Reducerar intensiteten för länkade bilder och bitmapbilder som finns i lagret till den angivna procenten. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Hämtar ett värde som indikerar om denna instans har frigjorts. |
| [Green](../../aspose.psd.fileformats.ai/ailayersection/green/) { get; set; } | Hämtar eller anger den gröna färgkomponenten. |
| [HasMultiLayerMasks](../../aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/) { get; set; } | Hämtar eller anger ett värde som indikerar om detta objekt har multilagermasker. |
| [IsImagesDimmed](../../aspose.psd.fileformats.ai/ailayersection/isimagesdimmed/) { get; set; } | Hämtar eller anger ett värde som indikerar om detta lager är dämpat. Minskar intensiteten för länkade bilder och bitmapbilder som finns i lagret. |
| [IsLocked](../../aspose.psd.fileformats.ai/ailayersection/islocked/) { get; set; } | Hämtar eller anger ett värde som indikerar om detta lager är låst. Förhindrar ändringar av objektet. |
| [IsPreview](../../aspose.psd.fileformats.ai/ailayersection/ispreview/) { get; set; } | Hämtar eller anger ett värde som indikerar om detta lager är förhandsgranskning. Visar konstverket i lagret i färg istället för som konturer. |
| [IsPrinted](../../aspose.psd.fileformats.ai/ailayersection/isprinted/) { get; set; } | Hämtar eller anger ett värde som indikerar om detta lager är utskrivet. Gör konstverket i lagret utskrivbart om sant. |
| [IsShown](../../aspose.psd.fileformats.ai/ailayersection/isshown/) { get; set; } | Hämtar eller anger ett värde som indikerar om detta lager visas. Visar allt konstverk i lagret på arbetsytan om sant. |
| [IsTemplate](../../aspose.psd.fileformats.ai/ailayersection/istemplate/) { get; set; } | Hämtar eller anger ett värde som indikerar om detta lager är ett malllager. |
| [Name](../../aspose.psd.fileformats.ai/ailayersection/name/) { get; set; } | Hämtar eller anger lagrets namn. Anger namnet på objektet som det visas i lagerpanelen. |
| [RasterImages](../../aspose.psd.fileformats.ai/ailayersection/rasterimages/) { get; } | Hämtar rasterbilderna. |
| [Red](../../aspose.psd.fileformats.ai/ailayersection/red/) { get; set; } | Hämtar eller anger den röda färgkomponenten. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddRasterImage](../../aspose.psd.fileformats.ai/ailayersection/addrasterimage/)(AiRasterImageSection) | Lägger till rasterbilden. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Frigör den aktuella instansen. |
| [GetData](../../aspose.psd.fileformats.ai/aidatasection/getdata/)() | Hämtar strängdata. |

## Exempel

Följande kod demonstrerar hur man laddar inställningar för Raster Images i AI Format Files.

```csharp
[C#]

const double DefaultTolerance = 1e-6;

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}

string sourceFile = "sample.ai";
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AiLayerSection layer = image.Layers[0];

    AssertIsTrue(layer.RasterImages != null, "RasterImages property should be not null");
    AssertIsTrue(layer.RasterImages.Length == 1, "RasterImages property should contain exactly one item");

    AiRasterImageSection rasterImage = layer.RasterImages[0];
    AssertIsTrue(rasterImage.Pixels != null, "rasterImage.Pixels property should be not null");
    AssertIsTrue(rasterImage.Pixels.Length == 100, "rasterImage.Pixels property should contain exactly 100 items");
    AssertIsTrue((uint)rasterImage.Pixels[99] == 0xFFB21616, "rasterImage.Pixels[99] should be 0xFFB21616");
    AssertIsTrue((uint)rasterImage.Pixels[19] == 0xFF00FF00, "rasterImage.Pixels[19] should be 0xFF00FF00");
    AssertIsTrue((uint)rasterImage.Pixels[10] == 0xFF01FD00, "rasterImage.Pixels[10] should be 0xFF01FD00");
    AssertIsTrue((uint)rasterImage.Pixels[0] == 0xFF0000FF, "rasterImage.Pixels[0] should be 0xFF0000FF");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Width) < DefaultTolerance, "rasterImage.Width should be 0.99987");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Height) < DefaultTolerance, "rasterImage.Height should be 0.99987");
    AssertIsTrue(Math.Abs(387 - rasterImage.OffsetX) < DefaultTolerance, "rasterImage.OffsetX should be 387");
    AssertIsTrue(Math.Abs(379 - rasterImage.OffsetY) < DefaultTolerance, "rasterImage.OffsetY should be 379");
    AssertIsTrue(Math.Abs(0 - rasterImage.Angle) < DefaultTolerance, "rasterImage.Angle should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.LeftBottomShift) < DefaultTolerance, "rasterImage.LeftBottomShift should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.X) < DefaultTolerance, "rasterImage.ImageRectangle.X should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.Y) < DefaultTolerance, "rasterImage.ImageRectangle.Y should be 0");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Width) < DefaultTolerance, "rasterImage.ImageRectangle.Width should be 10");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Height) < DefaultTolerance, "rasterImage.ImageRectangle.Height should be 10");
}
```

### Se även

* class [AiDataSection](../aidatasection/)
* namespace [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../)


