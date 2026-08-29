---
title: "StrokeEffect.Position"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "StrokeEffect-Eigenschaft. Ruft die Position des Strich‑Effekts ab oder legt sie fest, um die Ausrichtung Ihres Strichs am PSD‑Ebeneninhalt zu steuern. Der Wert kann Inside sein, um den Strich innerhalb des PSD‑Ebeneninhalts zu zeichnen, Outside, um den Strich um den PSD‑Ebeneninhalt zu zeichnen, und Center, um den Strich sowohl innen als auch außen zu zeichnen."
type: docs
weight: 70
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/position/
---
{{< psd/tize >}}
## StrokeEffect.Position property

Liest oder legt die Position des Strich‑Effekts fest, um die Ausrichtung Ihres Strichs am PSD‑Ebeneninhalt zu steuern. Der Wert kann Inside sein, um den Strich innerhalb des PSD‑Ebeneninhalts zu zeichnen, Outside, um den Strich um den PSD‑Ebeneninhalt zu zeichnen, und Center, um den Strich sowohl innerhalb als auch außerhalb zu zeichnen.

```csharp
public StrokePosition Position { get; set; }
```

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

* enum [StrokePosition](../../strokeposition/)
* class [StrokeEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


