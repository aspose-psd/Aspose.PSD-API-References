---
title: StrokeEffect.Position
second_title: Aspose.PSD für .NET-API-Referenz
description: StrokeEffect eigendom. Ruft die Position des Stricheffekts ab oder legt sie fest um die Ausrichtung Ihres Strichs am Inhalt der PSDEbene zu steuern. Der Wert kann seinInside Um einen Strich innerhalb des Inhalts der PSDEbene zu zeichnen oderOutside Um einen Strich um den Inhalt der PSDEbene zu zeichnen undCenter um Striche sowohl innen als auch außen zu zeichnen.
type: docs
weight: 70
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/position/
---
## StrokeEffect.Position property

Ruft die Position des Stricheffekts ab oder legt sie fest, um die Ausrichtung Ihres Strichs am Inhalt der PSD-Ebene zu steuern. Der Wert kann seinInside Um einen Strich innerhalb des Inhalts der PSD-Ebene zu zeichnen, oderOutside Um einen Strich um den Inhalt der PSD-Ebene zu zeichnen, undCenter um Striche sowohl innen als auch außen zu zeichnen.

```csharp
public StrokePosition Position { get; set; }
```

### Beispiele

Dieses Beispiel demonstriert die Möglichkeit, den Stricheffekt mit verschiedenen Fülltypen wie Farbe, Farbverlauf oder Muster hinzuzufügen.

```csharp
[C#]

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    StrokeEffect strokeEffect;
    IColorFillSettings colorFillSettings;
    IGradientFillSettings gradientFillSettings;
    IPatternFillSettings patternFillSettings;

    // 1. Fügt eine Farbfüllung an der Position Inside hinzu
    strokeEffect = psdImage.Layers[1].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Inside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 2. Fügt eine Farbfüllung an der Position Outside hinzu
    strokeEffect = psdImage.Layers[2].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Outside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 3. Fügt eine Farbfüllung an der Position Center hinzu
    strokeEffect = psdImage.Layers[3].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Center;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 4. Fügt eine Verlaufsfüllung an der Position Inside hinzu
    strokeEffect = psdImage.Layers[4].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Angle = 90;

    // 5. Fügt eine Verlaufsfüllung an der Position Outside hinzu
    strokeEffect = psdImage.Layers[5].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Outside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 90;

    // 6. Fügt eine Verlaufsfüllung an der Position Center hinzu
    strokeEffect = psdImage.Layers[6].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Center;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 0;

    // 7. Fügt Musterfüllung an Position Inside hinzu
    strokeEffect = psdImage.Layers[7].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 200;

    // 8. Fügt eine Musterfüllung an der Position Outside hinzu
    strokeEffect = psdImage.Layers[8].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Outside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 100;

    // 9. Fügt Musterfüllung an Position Center hinzu
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
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../strokeeffect/)
* Montage [Aspose.PSD](../../../)


