---
title: "Klasse InnerShadowEffect"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.InnerShadowEffect Klasse. Inner Shadow Ebeneneffekt"
type: docs
weight: 2350
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/
---
{{< psd/tize >}}
## InnerShadowEffect class

Inner‑Shadow‑Ebeneneffekt

```csharp
public class InnerShadowEffect : IShadowEffect
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/angle/) { get; set; } | Liest oder setzt den Winkel in Grad. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/blendmode/) { get; set; } | Liest oder setzt den Mischmodus. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/color/) { get; set; } | Liest oder setzt die Farbe. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/distance/) { get; set; } | Liest oder setzt die Entfernung in Pixeln. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/effecttype/) { get; } | Liest einen Effekttyp |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/isvisible/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob diese Instanz sichtbar ist. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/noise/) { get; set; } | Liest oder setzt das Rauschen. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/opacity/) { get; set; } | Liest oder setzt die Deckkraft. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/size/) { get; set; } | Liest oder setzt den Unschärfewert in Pixeln. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/spread/) { get; set; } | Liest oder setzt die Ausdehnung (Drosselung) als Prozentsatz. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/usegloballight/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [use this angle in all of the layer effects]. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/geteffectbounds/)(Rectangle, int) | Berechnet und liest die Grenzen der Effektpixel basierend auf den Grenzen der Eingabeebenenpixel. |

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

* interface [IShadowEffect](../ishadoweffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


