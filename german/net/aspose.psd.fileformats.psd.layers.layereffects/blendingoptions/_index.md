---
title: "Klasse BlendingOptions"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.BlendingOptions Klasse. BlendingOptions. Es ist ein Wrapper für BaseFxResource, der eine API für Ebeneneffekte bereitstellt."
type: docs
weight: 2290
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---
{{< psd/tize >}}
## BlendingOptions class

BlendingOptions. Es ist ein Wrapper für BaseFxResource, der eine API für Ebeneneffekte bereitstellt

```csharp
public class BlendingOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AreEffectsEnabled](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/areeffectsenabled/) { get; set; } | Liest oder setzt die Sichtbarkeit aller Ebeneneffekte. |
| [Effects](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/effects/) { get; set; } | Liest die Effekte. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addcoloroverlay/)() | Fügt die Farbüberlagerung hinzu. |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/adddropshadow/)() | Fügt den Drop Shadow Effekt hinzu. |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addgradientoverlay/)() | Fügt die Gradient-Überlagerung hinzu. |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addinnershadow/)() | Fügt den Inneren Schatten-Effekt hinzu. |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/)() | Fügt den äußeren Leuchteffekt hinzu. |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addpatternoverlay/)() | Fügt das Muster-Overlay hinzu. |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addstroke/)(FillType) | Fügt den Kontur-Effekt hinzu. |

## Beispiele

Der folgende Code demonstriert, wie man die Einstellungen des Inner Shadow Layer Effect ändert.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// Laden Sie ein vorhandenes Bild in eine Instanz der Klasse PsdImage.
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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


