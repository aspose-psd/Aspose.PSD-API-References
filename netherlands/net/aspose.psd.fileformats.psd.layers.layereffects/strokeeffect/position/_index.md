---
title: StrokeEffect.Position
second_title: Aspose.PSD voor .NET API-referentie
description: StrokeEffect eigendom. Hiermee wordt de positie van het lijneffect opgehaald of ingesteld om de uitlijning van uw lijn met de inhoud van de PSDlaag te regelen. De waarde kan zijnInside om een lijn binnen de inhoud van de PSDlaag te tekenen ofOutside om een lijn rond de inhoud van de PSDlaag te tekenen enCenter om zowel binnen als buiten een slag te tekenen.
type: docs
weight: 70
url: /nl/net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/position/
---
## StrokeEffect.Position property

Hiermee wordt de positie van het lijneffect opgehaald of ingesteld om de uitlijning van uw lijn met de inhoud van de PSD-laag te regelen. De waarde kan zijnInside om een lijn binnen de inhoud van de PSD-laag te tekenen, ofOutside om een lijn rond de inhoud van de PSD-laag te tekenen, enCenter om zowel binnen als buiten een slag te tekenen.

```csharp
public StrokePosition Position { get; set; }
```

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

* enum [StrokePosition](../../strokeposition/)
* class [StrokeEffect](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../strokeeffect/)
* montage [Aspose.PSD](../../../)


