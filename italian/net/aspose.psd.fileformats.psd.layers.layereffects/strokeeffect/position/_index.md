---
title: StrokeEffect.Position
second_title: Aspose.PSD per riferimento API .NET
description: StrokeEffect proprietà. Ottiene o imposta la posizione delleffetto tratto per controllare lallineamento del tratto al contenuto del livello PSD. Il valore può essereInside per disegnare il tratto allinterno del contenuto del livello PSD oOutside per tracciare un tratto attorno al contenuto del livello PSD eCenter per disegnare tratti sia allinterno che allesterno.
type: docs
weight: 70
url: /it/net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/position/
---
## StrokeEffect.Position property

Ottiene o imposta la posizione dell'effetto tratto per controllare l'allineamento del tratto al contenuto del livello PSD. Il valore può essereInside per disegnare il tratto all'interno del contenuto del livello PSD, oOutside per tracciare un tratto attorno al contenuto del livello PSD, eCenter per disegnare tratti sia all'interno che all'esterno.

```csharp
public StrokePosition Position { get; set; }
```

### Esempi

Questo esempio dimostra la possibilità di aggiungere l'effetto tratto con diversi tipi di riempimento come Colore, Gradiente o Motivo.

```csharp
[C#]

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    StrokeEffect strokeEffect;
    IColorFillSettings colorFillSettings;
    IGradientFillSettings gradientFillSettings;
    IPatternFillSettings patternFillSettings;

    // 1. Aggiunge il riempimento Colore, nella posizione Dentro
    strokeEffect = psdImage.Layers[1].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Inside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 2. Aggiunge il riempimento Colore, nella posizione Fuori
    strokeEffect = psdImage.Layers[2].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Outside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 3. Aggiunge il riempimento Colore, nella posizione Center
    strokeEffect = psdImage.Layers[3].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Center;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 4. Aggiunge il riempimento sfumato, nella posizione Dentro
    strokeEffect = psdImage.Layers[4].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Angle = 90;

    // 5. Aggiunge il riempimento sfumato, nella posizione Outside
    strokeEffect = psdImage.Layers[5].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Outside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 90;

    // 6. Aggiunge il riempimento sfumato, nella posizione Center
    strokeEffect = psdImage.Layers[6].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Center;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 0;

    // 7. Aggiunge il riempimento a motivo, nella posizione Dentro
    strokeEffect = psdImage.Layers[7].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 200;

    // 8. Aggiunge il riempimento a motivo, nella posizione Outside
    strokeEffect = psdImage.Layers[8].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Outside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 100;

    // 9. Aggiunge il riempimento a motivo, nella posizione Center
    strokeEffect = psdImage.Layers[9].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Center;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 75;

    psdImage.Save(outputFilePng, new PngOptions());
}
```

### Guarda anche

* enum [StrokePosition](../../strokeposition/)
* class [StrokeEffect](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../strokeeffect/)
* assemblea [Aspose.PSD](../../../)


