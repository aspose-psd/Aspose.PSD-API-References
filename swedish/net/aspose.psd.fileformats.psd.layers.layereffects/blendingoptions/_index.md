---
title: Class BlendingOptions
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.BlendingOptions klass. Blandningsalternativ. Det är ett omslag för Lfx2Resource som tillhandahåller api för lagereffekter
type: docs
weight: 2100
url: /sv/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---
## BlendingOptions class

Blandningsalternativ. Det är ett omslag för Lfx2Resource som tillhandahåller api för lagereffekter

```csharp
public class BlendingOptions
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Effects](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/effects/) { get; } | Får effekterna. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addcoloroverlay/)() | Lägger till färgöverlägget. |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/adddropshadow/)() | Lägger till skuggeffekten. |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addgradientoverlay/)() | Lägger till övertoningsöverlägget. |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addinnershadow/)() | Lägger till den inre skuggeffekten. |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/)() | Lägger till den yttre glödeffekten. |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addpatternoverlay/)() | Lägger till mönsteröverlägget. |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addstroke/)(FillType) | Lägger till streckeffekten. |

### Exempel

Följande kod visar hur man ändrar inställningarna för den inre skuggskiktseffekten.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// Ladda en befintlig bild i en instans av klassen PsdImage
var loadOptions = new PsdLoadOptions();
loadOptions.LoadEffectsResource = true;
using (var image = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    var layer = image.Layers[image.Layers.Length - 1];
    var shadowEffect = (IShadowEffect)layer.BlendingOptions.Effects[0];

    shadowEffect.Color = Color.Green;
    shadowEffect.Opacity = 128;
    shadowEffect.Distance = 1;
    shadowEffect.UseGlobalLight = false;
    shadowEffect.Size = 2;
    shadowEffect.Angle = 45;
    shadowEffect.Spread = 50;
    shadowEffect.Noise = 5;

    image.Save(outputFile, new PsdOptions(image));
}
```

### Se även

* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* hopsättning [Aspose.PSD](../../)


