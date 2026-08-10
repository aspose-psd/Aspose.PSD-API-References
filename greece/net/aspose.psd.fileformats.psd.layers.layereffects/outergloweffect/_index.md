---
title: "Κλάση OuterGlowEffect"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.OuterGlowEffect κλάση. Εφέ στρώσης Outer Glow."
type: docs
weight: 2370
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---
{{< psd/tize >}}
## OuterGlowEffect class

Εφέ στρώσης Εξωτερικής Λάμψης

```csharp
public class OuterGlowEffect : ILayerEffect
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/effecttype/) { get; } | Λαμβάνει έναν τύπο εφέ. |
| [FillColor](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/fillcolor/) { get; set; } | Λαμβάνει ή ορίζει το χρώμα. |
| [Intensity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/) { get; set; } | Λαμβάνει ή ορίζει τη γωνία σε μοίρες. |
| [IsAntiAliasing](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isantialiasing/) { get; set; } | Λαμβάνει ή ορίζει το ενεργοποιημένο εφέ AntiAliasing. |
| [IsSoftBlend](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/issoftblend/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [knocks out]. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isvisible/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ορατή. |
| [Jitter](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/jitter/) { get; set; } | Λαμβάνει ή ορίζει τον θόρυβο. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/noise/) { get; set; } | Λαμβάνει ή ορίζει τον θόρυβο. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/opacity/) { get; set; } | Λαμβάνει ή ορίζει τη διαφάνεια. |
| [Range](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/range/) { get; set; } | Λαμβάνει ή ορίζει τον θόρυβο. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/) { get; set; } | Λαμβάνει την τιμή θολώματος σε εικονοστοιχεία. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/spread/) { get; set; } | Λαμβάνει ή ορίζει την ένταση ως ποσοστό. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/geteffectbounds/)(Rectangle, int) | Υπολογίζει και λαμβάνει τα όρια των εικονοστοιχείων εφέ βάσει των ορίων των εικονοστοιχείων εισόδου της στρώσης. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη του OuterGlowEffect.

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

### Δείτε επίσης

* interface [ILayerEffect](../ilayereffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


