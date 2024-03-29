---
title: Class BlendingOptions
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.BlendingOptions klas. Mischoptionen. Es ist ein Wrapper für Lfx2Resource der eine API für Ebeneneffekte bereitstellt
type: docs
weight: 2100
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---
## BlendingOptions class

Mischoptionen. Es ist ein Wrapper für Lfx2Resource, der eine API für Ebeneneffekte bereitstellt

```csharp
public class BlendingOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Effects](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/effects/) { get; } | Ruft die Effekte ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addcoloroverlay/)() | Fügt die Farbüberlagerung hinzu. |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/adddropshadow/)() | Fügt den Schlagschatteneffekt hinzu. |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addgradientoverlay/)() | Fügt die Verlaufsüberlagerung hinzu. |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addinnershadow/)() | Fügt den inneren Schatteneffekt hinzu. |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/)() | Fügt den äußeren Glüheffekt hinzu. |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addpatternoverlay/)() | Fügt die Musterüberlagerung hinzu. |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addstroke/)(FillType) | Fügt den Stricheffekt hinzu. |

### Beispiele

Der folgende Code zeigt, wie die Einstellungen des Effekts „Innere Schattenebene“ geändert werden.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// Ein vorhandenes Bild in eine Instanz der PsdImage-Klasse laden
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

### Siehe auch

* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* Montage [Aspose.PSD](../../)


