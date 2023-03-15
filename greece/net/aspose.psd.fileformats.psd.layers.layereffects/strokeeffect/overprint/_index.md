---
title: StrokeEffect.Overprint
second_title: Aspose.PSD για Αναφορά API .NET
description: StrokeEffect ιδιοκτησία. Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτόStrokeEffect θα συνδυάσει το stroke με τα τρέχοντα περιεχόμενα του επιπέδου.
type: docs
weight: 60
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/overprint/
---
## StrokeEffect.Overprint property

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό[`StrokeEffect`](../) θα συνδυάσει το stroke με τα τρέχοντα περιεχόμενα του επιπέδου.

```csharp
public bool Overprint { get; set; }
```

### Αξία περιουσίας

`αληθής` εάν πρέπει να συνδυάσει τη διαδρομή με τα τρέχοντα περιεχόμενα του στρώματος. σε διαφορετική περίπτωση,`ψευδής` .

### Παραδείγματα

Αυτό το παράδειγμα δείχνει τη δυνατότητα προσθήκης του stroke εφέ με διαφορετικούς τύπους γεμίσματος όπως Χρώμα, Διαβάθμιση ή Μοτίβο.

```csharp
[C#]

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    StrokeEffect strokeEffect;
    IColorFillSettings colorFillSettings;
    IGradientFillSettings gradientFillSettings;
    IPatternFillSettings patternFillSettings;

    // 1. Προσθέτει Color fill, στη θέση Inside
    strokeEffect = psdImage.Layers[1].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Inside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 2. Προσθέτει Color fill, στη θέση Outside
    strokeEffect = psdImage.Layers[2].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Outside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 3. Προσθέτει Color fill, στη θέση Center
    strokeEffect = psdImage.Layers[3].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Center;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 4. Προσθέτει γέμισμα κλίσης, στη θέση Inside
    strokeEffect = psdImage.Layers[4].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Angle = 90;

    // 5. Προσθέτει γέμισμα κλίσης, στη θέση Έξω
    strokeEffect = psdImage.Layers[5].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Outside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 90;

    // 6. Προσθέτει γέμισμα κλίσης, στη θέση Κέντρο
    strokeEffect = psdImage.Layers[6].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Center;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 0;

    // 7. Προσθέτει γέμισμα μοτίβου, στη θέση Inside
    strokeEffect = psdImage.Layers[7].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 200;

    // 8. Προσθέτει γέμισμα μοτίβου, στη θέση Outside
    strokeEffect = psdImage.Layers[8].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Outside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 100;

    // 9. Προσθέτει γέμισμα μοτίβου, στη θέση Κέντρο
    strokeEffect = psdImage.Layers[9].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Center;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 75;

    psdImage.Save(outputFilePng, new PngOptions());
}
```

### Δείτε επίσης

* class [StrokeEffect](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../strokeeffect/)
* συνέλευση [Aspose.PSD](../../../)


