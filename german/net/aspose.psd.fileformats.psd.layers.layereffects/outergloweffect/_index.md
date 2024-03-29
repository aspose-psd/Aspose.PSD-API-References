---
title: Class OuterGlowEffect
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.OuterGlowEffect klas. Äußerer Leuchtschichteffekt
type: docs
weight: 2170
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---
## OuterGlowEffect class

Äußerer Leuchtschichteffekt

```csharp
public class OuterGlowEffect : ILayerEffect
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/) { get; set; } | Ruft den Mischmodus ab oder legt ihn fest. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/effecttype/) { get; } | Ruft einen Effekttyp type ab |
| [FillColor](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/fillcolor/) { get; set; } | Ruft die Farbe ab oder legt sie fest. |
| [Intensity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/) { get; set; } | Ruft den Winkel in Grad ab oder legt ihn fest. |
| [IsAntiAliasing](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isantialiasing/) { get; set; } | Holt oder setzt aktivierten AntiAliasing-Effekt |
| [IsSoftBlend](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/issoftblend/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [knocks out]. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isvisible/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob diese Instanz sichtbar ist. |
| [Jitter](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/jitter/) { get; set; } | Ruft das Rauschen ab oder legt es fest. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/noise/) { get; set; } | Ruft das Rauschen ab oder legt es fest. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/opacity/) { get; set; } | Ruft die Deckkraft ab oder legt sie fest. |
| [Range](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/range/) { get; set; } | Ruft das Rauschen ab oder legt es fest. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/) { get; } | Ruft den Unschärfewert in Pixel ab. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/spread/) { get; set; } | Holt oder setzt die Intensität in Prozent. |

### Beispiele

Der folgende Code demonstriert die OuterGlowEffect-Unterstützung.

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

### Siehe auch

* interface [ILayerEffect](../ilayereffect/)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* Montage [Aspose.PSD](../../)


