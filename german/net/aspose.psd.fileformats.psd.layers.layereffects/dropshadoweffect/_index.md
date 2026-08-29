---
title: "Klasse DropShadowEffect"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.DropShadowEffect Klasse. Drop Shadow Ebenen-Effekt"
type: docs
weight: 2310
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---
{{< psd/tize >}}
## DropShadowEffect class

Drop‑Shadow‑Ebeneneffekt

```csharp
public class DropShadowEffect : IShadowEffect
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/) { get; set; } | Liest oder setzt den Winkel in Grad. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode/) { get; set; } | Liest oder setzt den Mischmodus. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/) { get; set; } | Liest oder setzt die Farbe. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/distance/) { get; set; } | Liest oder setzt die Entfernung in Pixeln. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/) { get; } | Liest einen Effekttyp |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob diese Instanz sichtbar ist. |
| [KnocksOut](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/knocksout/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [knocks out]. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/noise/) { get; set; } | Liest oder setzt das Rauschen. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/opacity/) { get; set; } | Liest oder setzt die Deckkraft. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/size/) { get; set; } | Liest oder setzt den Unschärfewert in Pixeln. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/spread/) { get; set; } | Liest oder setzt die Intensität als Prozentsatz. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/usegloballight/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [use this angle in all of the layer effects]. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/geteffectbounds/)(Rectangle, int) | Berechnet und liest die Grenzen der Effektpixel basierend auf den Grenzen der Eingabeebenenpixel. |

## Beispiele

Der folgende Code demonstriert die Unterstützung der Eigenschaft PsdImage.GlobalAngle, um den globalen Winkelwert zu ändern.

```csharp
[C#]

// Wenn die Eigenschaft DropShadowEffect.UseGlobalLight den Wert 'true' hat, verwendet das DropShadowEffect-Objekt den Winkelwert aus der Eigenschaft PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

Der folgende Code demonstriert die Verwendung der Opacity-Eigenschaft von DropShadowEffect.

```csharp
[C#]

string inputFile = "input.psd";
string outputImage20 = "outputImage20.png";
string outputImage200 = "outputImage200.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;

    // Beispiel mit Opacity = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Beispiel mit Opacity = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Siehe auch

* interface [IShadowEffect](../ishadoweffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


