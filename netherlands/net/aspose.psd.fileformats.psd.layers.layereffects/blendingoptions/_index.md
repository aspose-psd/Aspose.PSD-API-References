---
title: Class BlendingOptions
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.BlendingOptions klas. BlendingOptions. Het is een wrapper voor Lfx2Resource die api biedt voor laageffecten
type: docs
weight: 2100
url: /nl/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---
## BlendingOptions class

BlendingOptions. Het is een wrapper voor Lfx2Resource die api biedt voor laageffecten

```csharp
public class BlendingOptions
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Effects](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/effects/) { get; } | Krijgt de effecten. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addcoloroverlay/)() | Voegt de kleuroverlay toe. |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/adddropshadow/)() | Voegt het slagschaduweffect toe. |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addgradientoverlay/)() | Voegt de verloopoverlay toe. |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addinnershadow/)() | Voegt het binnenste schaduweffect toe. |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/)() | Voegt het buitenste gloedeffect toe. |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addpatternoverlay/)() | Voegt de patroonoverlay toe. |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addstroke/)(FillType) | Voegt het lijneffect toe. |

### Voorbeelden

De volgende code laat zien hoe u de instellingen van het Inner Shadow Layer Effect kunt wijzigen.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// Laad een bestaande afbeelding in een instantie van de PsdImage-klasse
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

### Zie ook

* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* montage [Aspose.PSD](../../)


