---
title: "Enum StrokePosition"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.StrokePosition enum. Die Positionseinstellung steuert die Ausrichtung Ihres Strichs zur Ebene, auf die er im StrokeEffect angewendet wird."
type: docs
weight: 2400
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/
---
{{< psd/tize >}}
## StrokePosition enumeration

Die Positionseinstellung steuert die Ausrichtung Ihres Strichs zur Ebene, auf die er im [`StrokeEffect`](../strokeeffect/) angewendet wird.

```csharp
public enum StrokePosition : short
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Inside | `0` | Der Strich wird von der Kante der Form aus erstellt und nach innen zum Mittelpunkt des Objekts wachsen. |
| Center | `1` | Der Strich wird von der Kante der Form aus erstellt und sowohl nach innen als auch nach außen wachsen. |
| Outside | `2` | Der Strich wird von der Kante der Form aus erstellt und nach außen, vom Objekt weg, wachsen. |

## Beispiele

Dieses Beispiel demonstriert die Möglichkeit, den Strich‑Effekt mit verschiedenen Fülltypen wie Farbe, Verlauf oder Muster hinzuzufügen.

```csharp
[C#]

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    StrokeEffect strokeEffect;
    IColorFillSettings colorFillSettings;
    IGradientFillSettings gradientFillSettings;
    IPatternFillSettings patternFillSettings;

    // 1. Fügt Farbfüllung bei Position Inside hinzu
    strokeEffect = psdImage.Layers[1].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Inside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 2. Fügt Farbfüllung bei Position Outside hinzu
    strokeEffect = psdImage.Layers[2].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Outside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 3. Fügt Farbfüllung bei Position Center hinzu
    strokeEffect = psdImage.Layers[3].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Center;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 4. Fügt Verlaufsfüllung bei Position Inside hinzu
    strokeEffect = psdImage.Layers[4].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Angle = 90;

    // 5. Fügt Verlaufsfüllung bei Position Outside hinzu
    strokeEffect = psdImage.Layers[5].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Outside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 90;

    // 6. Fügt Verlaufsfüllung bei Position Center hinzu
    strokeEffect = psdImage.Layers[6].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Center;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 0;

    // 7. Fügt Musterfüllung bei Position Inside hinzu
    strokeEffect = psdImage.Layers[7].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 200;

    // 8. Fügt Musterfüllung bei Position Outside hinzu
    strokeEffect = psdImage.Layers[8].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Outside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 100;

    // 9. Fügt Musterfüllung bei Position Center hinzu
    strokeEffect = psdImage.Layers[9].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Center;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 75;

    psdImage.Save(outputFilePng, new PngOptions());
}
```

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


