---
title: Class OuterGlowEffect
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.OuterGlowEffect classe. Effetto livello bagliore esterno
type: docs
weight: 2170
url: /it/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---
## OuterGlowEffect class

Effetto livello bagliore esterno

```csharp
public class OuterGlowEffect : ILayerEffect
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/) { get; set; } | Ottiene o imposta la modalità di fusione. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/effecttype/) { get; } | Ottiene un tipo di effetto type |
| [FillColor](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/fillcolor/) { get; set; } | Ottiene o imposta il colore. |
| [Intensity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/) { get; set; } | Ottiene o imposta l'angolo in gradi. |
| [IsAntiAliasing](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isantialiasing/) { get; set; } | Ottiene o imposta l'effetto AntiAliasing abilitato |
| [IsSoftBlend](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/issoftblend/) { get; set; } | Ottiene o imposta un valore che indica se [knock out]. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isvisible/) { get; set; } | Ottiene o imposta un valore che indica se questa istanza è visibile. |
| [Jitter](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/jitter/) { get; set; } | Ottiene o imposta il rumore. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/noise/) { get; set; } | Ottiene o imposta il rumore. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/opacity/) { get; set; } | Ottiene o imposta l'opacità. |
| [Range](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/range/) { get; set; } | Ottiene o imposta il rumore. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/) { get; } | Ottiene il valore di sfocatura in pixel. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/spread/) { get; set; } | Ottiene o imposta l'intensità come percentuale. |

### Esempi

Il codice seguente illustra il supporto OuterGlowEffect.

```csharp
[C#]

string src = "GreenLayer.psd";
string outputPng = "output261.png";

using (var image = (PsdImage)Image.Load(src))
{
    OuterGlowEffect effect = image.Layers[1].BlendingOptions.AddOuterGlow();
    effect.Range = 10;
    effect.Spread = 10;
    ((IColorFillSettings)effect.FillColor).Color = Color.Red;
    effect.Opacity = 128;
    effect.BlendMode = BlendMode.Normal;

    image.Save(outputPng, new PngOptions());
}
```

### Guarda anche

* interface [ILayerEffect](../ilayereffect/)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assemblea [Aspose.PSD](../../)


