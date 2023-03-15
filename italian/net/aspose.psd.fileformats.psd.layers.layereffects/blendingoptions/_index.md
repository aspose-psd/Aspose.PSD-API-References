---
title: Class BlendingOptions
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.BlendingOptions classe. BlendingOptions. È un wrapper per Lfx2Resource che fornisce API per layer effects
type: docs
weight: 2100
url: /it/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---
## BlendingOptions class

BlendingOptions. È un wrapper per Lfx2Resource che fornisce API per layer effects

```csharp
public class BlendingOptions
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Effects](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/effects/) { get; } | Ottiene gli effetti. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addcoloroverlay/)() | Aggiunge la sovrapposizione di colori. |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/adddropshadow/)() | Aggiunge l'effetto ombra esterna. |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addgradientoverlay/)() | Aggiunge la sovrapposizione Gradiente. |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addinnershadow/)() | Aggiunge l'effetto ombra interna. |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/)() | Aggiunge l'effetto bagliore esterno. |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addpatternoverlay/)() | Aggiunge la sovrapposizione Pattern. |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addstroke/)(FillType) | Aggiunge l'effetto tratto. |

### Esempi

Il codice seguente illustra come modificare le impostazioni di Inner Shadow Layer Effect.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// Carica un'immagine esistente in un'istanza della classe PsdImage
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

### Guarda anche

* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assemblea [Aspose.PSD](../../)


