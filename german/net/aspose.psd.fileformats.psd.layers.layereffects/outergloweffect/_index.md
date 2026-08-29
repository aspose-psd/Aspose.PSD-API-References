---
title: "Klasse OuterGlowEffect"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.OuterGlowEffect Klasse. Outer Glow Ebenen-Effekt"
type: docs
weight: 2370
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---
{{< psd/tize >}}
## OuterGlowEffect class

Outer‑Glow‑Ebeneneffekt

```csharp
public class OuterGlowEffect : ILayerEffect
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/) { get; set; } | Liest oder setzt den Mischmodus. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/effecttype/) { get; } | Liest einen Effekt-Typ. |
| [FillColor](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/fillcolor/) { get; set; } | Liest oder setzt die Farbe. |
| [Intensity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/) { get; set; } | Liest oder setzt den Winkel in Grad. |
| [IsAntiAliasing](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isantialiasing/) { get; set; } | Liest oder setzt den aktivierten AntiAliasing-Effekt. |
| [IsSoftBlend](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/issoftblend/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [knocks out]. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isvisible/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob diese Instanz sichtbar ist. |
| [Jitter](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/jitter/) { get; set; } | Liest oder setzt das Rauschen. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/noise/) { get; set; } | Liest oder setzt das Rauschen. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/opacity/) { get; set; } | Liest oder setzt die Deckkraft. |
| [Range](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/range/) { get; set; } | Liest oder setzt das Rauschen. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/) { get; set; } | Liest den Unschärfewert in Pixeln. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/spread/) { get; set; } | Liest oder setzt die Intensität als Prozentsatz. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/geteffectbounds/)(Rectangle, int) | Berechnet und liest die Grenzen der Effektpixel basierend auf den Grenzen der Eingabeebenenpixel. |

## Beispiele

Der folgende Code demonstriert die Unterstützung von OuterGlowEffect.

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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


