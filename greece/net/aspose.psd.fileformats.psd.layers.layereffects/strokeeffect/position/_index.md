---
title: "StrokeEffect.Position"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "StrokeEffect ιδιότητα. Λαμβάνει ή ορίζει τη θέση του εφέ περιγράμματος για να ελέγχει την ευθυγράμμιση του περιγράμματος με το περιεχόμενο του στρώματος PSD. Η τιμή μπορεί να είναι Inside για να σχεδιάζει το περίγραμμα μέσα στο περιεχόμενο του στρώματος PSD ή Outside για να σχεδιάζει το περίγραμμα γύρω από το περιεχόμενο του στρώματος PSD και Center για να σχεδιάζει το περίγραμμα τόσο μέσα όσο και έξω"
type: docs
weight: 70
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/position/
---
{{< psd/tize >}}
## StrokeEffect.Position property

Λαμβάνει ή ορίζει τη θέση του εφέ στίγματος για να ελέγχει την ευθυγράμμιση του στίγματος σας με το περιεχόμενο του στρώματος PSD. Η τιμή μπορεί να είναι Inside για να σχεδιάζει το στίγμα μέσα στο περιεχόμενο του στρώματος PSD, ή Outside για να σχεδιάζει το στίγμα γύρω από το περιεχόμενο του στρώματος PSD, και Center για να σχεδιάζει το στίγμα τόσο μέσα όσο και έξω.

```csharp
public StrokePosition Position { get; set; }
```

## Παραδείγματα

Αυτό το παράδειγμα δείχνει τη δυνατότητα προσθήκης του εφέ περιγράμματος με διαφορετικούς τύπους γεμίσματος όπως Χρώμα, Διαβάθμιση ή Μοτίβο.

```csharp
[C#]

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    StrokeEffect strokeEffect;
    IColorFillSettings colorFillSettings;
    IGradientFillSettings gradientFillSettings;
    IPatternFillSettings patternFillSettings;

    // 1. Προσθέτει γέμισμα Χρώματος, στη θέση Εσωτερική
    strokeEffect = psdImage.Layers[1].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Inside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 2. Προσθέτει γέμισμα Χρώματος, στη θέση Εξωτερική
    strokeEffect = psdImage.Layers[2].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Outside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 3. Προσθέτει γέμισμα Χρώματος, στη θέση Κέντρο
    strokeEffect = psdImage.Layers[3].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Center;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 4. Προσθέτει γέμισμα Διαβάθμισης, στη θέση Εσωτερική
    strokeEffect = psdImage.Layers[4].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Angle = 90;

    // 5. Προσθέτει γέμισμα Διαβάθμισης, στη θέση Εξωτερική
    strokeEffect = psdImage.Layers[5].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Outside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 90;

    // 6. Προσθέτει γέμισμα Διαβάθμισης, στη θέση Κέντρο
    strokeEffect = psdImage.Layers[6].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Center;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 0;

    // 7. Προσθέτει γέμισμα Μοτίβου, στη θέση Εσωτερική
    strokeEffect = psdImage.Layers[7].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 200;

    // 8. Προσθέτει γέμισμα Μοτίβου, στη θέση Εξωτερική
    strokeEffect = psdImage.Layers[8].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Outside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 100;

    // 9. Προσθέτει γέμισμα Μοτίβου, στη θέση Κέντρο
    strokeEffect = psdImage.Layers[9].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Center;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 75;

    psdImage.Save(outputFilePng, new PngOptions());
}
```

### Δείτε επίσης

* enum [StrokePosition](../../strokeposition/)
* class [StrokeEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


