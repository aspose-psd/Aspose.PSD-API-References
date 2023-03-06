---
title: Class AiLayerSection
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Ai.AiLayerSection klas. Het Aiformaat Layer Section
type: docs
weight: 1270
url: /nl/net/aspose.psd.fileformats.ai/ailayersection/
---
## AiLayerSection class

Het Ai-formaat Layer Section

```csharp
public sealed class AiLayerSection : AiDataSection
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Blue](../../aspose.psd.fileformats.ai/ailayersection/blue/) { get; set; } | Haalt of stelt de blauwe kleurcomponent in. |
| [ColorNumber](../../aspose.psd.fileformats.ai/ailayersection/colornumber/) { get; set; } | Haalt of stelt het kleurnummer in. -1 is de aangepaste kleurwaarde van de eigenschappen Rood, Groen en Blauw. Specificeert de kleurinstelling van de laag. |
| [DimValue](../../aspose.psd.fileformats.ai/ailayersection/dimvalue/) { get; set; } | Haalt de dimwaarde op of stelt deze in als percentage. Vermindert de intensiteit van gekoppelde afbeeldingen en bitmapafbeeldingen in de laag tot het opgegeven percentage. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Krijgt een waarde die aangeeft of deze instantie is verwijderd. |
| [Green](../../aspose.psd.fileformats.ai/ailayersection/green/) { get; set; } | Haalt of stelt de groene kleurcomponent in. |
| [IsImagesDimmed](../../aspose.psd.fileformats.ai/ailayersection/isimagesdimmed/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of deze laag gedimd is. Vermindert de intensiteit van gekoppelde afbeeldingen en bitmapafbeeldingen in de laag. |
| [IsLocked](../../aspose.psd.fileformats.ai/ailayersection/islocked/) { get; set; } | Haalt of stelt een waarde in die aangeeft of deze laag vergrendeld is. Voorkomt wijzigingen aan het item. |
| [IsPreview](../../aspose.psd.fileformats.ai/ailayersection/ispreview/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of deze laag een voorbeeld is. Geeft de illustratie in de laag weer in kleur in plaats van als contouren. |
| [IsPrinted](../../aspose.psd.fileformats.ai/ailayersection/isprinted/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of deze laag wordt afgedrukt. Maakt de illustratie in de laag afdrukbaar indien waar. |
| [IsShown](../../aspose.psd.fileformats.ai/ailayersection/isshown/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of deze laag wordt weergegeven. Geeft alle illustraties in de laag op het tekengebied weer, indien waar. |
| [IsTemplate](../../aspose.psd.fileformats.ai/ailayersection/istemplate/) { get; set; } | Haalt of stelt een waarde in die aangeeft of deze laag een sjabloonlaag is. |
| [Name](../../aspose.psd.fileformats.ai/ailayersection/name/) { get; set; } | Hiermee wordt de naam van de laag opgehaald of ingesteld. Specificeert de naam van het item zoals deze wordt weergegeven in het deelvenster Lagen. |
| [RasterImages](../../aspose.psd.fileformats.ai/ailayersection/rasterimages/) { get; } | Haalt de rasterafbeeldingen op. |
| [Red](../../aspose.psd.fileformats.ai/ailayersection/red/) { get; set; } | Haalt of stelt de rode kleurcomponent in. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddRasterImage](../../aspose.psd.fileformats.ai/ailayersection/addrasterimage/)(AiRasterImageSection) | Voegt de rasterafbeelding toe. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwijdert de huidige instantie. |
| [GetData](../../aspose.psd.fileformats.ai/aidatasection/getdata/)() | Haalt de tekenreeksgegevens op. |

### Voorbeelden

De volgende code laat zien hoe instellingen van rasterafbeeldingen in AI-indelingsbestanden kunnen worden geladen.

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

### Zie ook

* class [AiDataSection](../aidatasection/)
* naamruimte [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* montage [Aspose.PSD](../../)


