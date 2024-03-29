---
title: Class InnerShadowEffect
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.InnerShadowEffect classe. Effetto livello ombra interna
type: docs
weight: 2160
url: /it/net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/
---
## InnerShadowEffect class

Effetto livello ombra interna

```csharp
public class InnerShadowEffect : IShadowEffect
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/angle/) { get; set; } | Ottiene o imposta l'angolo in gradi. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/blendmode/) { get; set; } | Ottiene o imposta la modalità di fusione. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/color/) { get; set; } | Ottiene o imposta il colore. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/distance/) { get; set; } | Ottiene o imposta la distanza in pixel. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/effecttype/) { get; } | Ottiene un tipo di effetto |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/isvisible/) { get; set; } | Ottiene o imposta un valore che indica se questa istanza è visibile. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/noise/) { get; set; } | Ottiene o imposta il rumore. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/opacity/) { get; set; } | Ottiene o imposta l'opacità. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/size/) { get; set; } | Ottiene o imposta il valore di sfocatura in pixel. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/spread/) { get; set; } | Ottiene o imposta lo spread (choke) come percentuale. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/usegloballight/) { get; set; } | Ottiene o imposta un valore che indica se [utilizzare questo angolo in tutti gli effetti di livello]. |

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

* interface [IShadowEffect](../ishadoweffect/)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assemblea [Aspose.PSD](../../)


