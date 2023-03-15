---
title: StrokeEffect.Overprint
second_title: Aspose.PSD voor .NET API-referentie
description: StrokeEffect eigendom. Haalt of stelt een waarde in die aangeeft of ditStrokeEffect zal de lijn laten overvloeien tegen de inhoud van de huidige laag.
type: docs
weight: 60
url: /nl/net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/overprint/
---
## StrokeEffect.Overprint property

Haalt of stelt een waarde in die aangeeft of dit[`StrokeEffect`](../) zal de lijn laten overvloeien tegen de inhoud van de huidige laag.

```csharp
public bool Overprint { get; set; }
```

### Eigendoms-waarde

`WAAR` als het de lijn moet laten overvloeien tegen de inhoud van de huidige laag; anders,`vals` .

### Voorbeelden

Dit voorbeeld demonstreert de mogelijkheid om het lijneffect toe te voegen met verschillende typen vulling zoals Kleur, Verloop of Patroon.

```csharp
[C#]

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    StrokeEffect strokeEffect;
    IColorFillSettings colorFillSettings;
    IGradientFillSettings gradientFillSettings;
    IPatternFillSettings patternFillSettings;

    // 1. Voegt kleurvulling toe, op positie Binnen
    strokeEffect = psdImage.Layers[1].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Inside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 2. Voegt kleurvulling toe, op positie Buiten
    strokeEffect = psdImage.Layers[2].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Outside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 3. Voegt kleurvulling toe, op positie midden
    strokeEffect = psdImage.Layers[3].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Center;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 4. Voegt verloopvulling toe, op positie Binnen
    strokeEffect = psdImage.Layers[4].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Angle = 90;

    // 5. Voegt verloopvulling toe, op positie Buiten
    strokeEffect = psdImage.Layers[5].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Outside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 90;

    // 6. Voegt verloopvulling toe, op positie midden
    strokeEffect = psdImage.Layers[6].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Center;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 0;

    // 7. Voegt patroonvulling toe, op positie Binnen
    strokeEffect = psdImage.Layers[7].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 200;

    // 8. Voegt patroonvulling toe, op positie Buiten
    strokeEffect = psdImage.Layers[8].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Outside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 100;

    // 9. Voegt patroonvulling toe, op positie midden
    strokeEffect = psdImage.Layers[9].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Center;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 75;

    psdImage.Save(outputFilePng, new PngOptions());
}
```

### Zie ook

* class [StrokeEffect](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../strokeeffect/)
* montage [Aspose.PSD](../../../)


