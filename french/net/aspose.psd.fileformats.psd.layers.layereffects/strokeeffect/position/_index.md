---
title: StrokeEffect.Position
second_title: Référence de l'API Aspose.PSD pour .NET
description: StrokeEffect propriété. Obtient ou définit la position de leffet de trait pour contrôler lalignement de votre trait sur le contenu du calque PSD. La valeur peut êtreInside pour dessiner un trait à lintérieur du contenu du calque PSD ouOutside pour dessiner un trait autour du contenu de la couche PSD etCenter pour dessiner un trait à lintérieur et à lextérieur.
type: docs
weight: 70
url: /fr/net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/position/
---
## StrokeEffect.Position property

Obtient ou définit la position de l'effet de trait pour contrôler l'alignement de votre trait sur le contenu du calque PSD. La valeur peut êtreInside pour dessiner un trait à l'intérieur du contenu du calque PSD, ouOutside pour dessiner un trait autour du contenu de la couche PSD, etCenter pour dessiner un trait à l'intérieur et à l'extérieur.

```csharp
public StrokePosition Position { get; set; }
```

### Exemples

Cet exemple montre la possibilité d'ajouter l'effet de trait avec différents types de remplissage comme Couleur, Dégradé ou Motif.

```csharp
[C#]

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    StrokeEffect strokeEffect;
    IColorFillSettings colorFillSettings;
    IGradientFillSettings gradientFillSettings;
    IPatternFillSettings patternFillSettings;

    // 1. Ajoute un remplissage de couleur, à la position À l'intérieur
    strokeEffect = psdImage.Layers[1].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Inside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 2. Ajoute un remplissage de couleur, à la position Outside
    strokeEffect = psdImage.Layers[2].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Outside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 3. Ajoute un remplissage de couleur, à la position Center
    strokeEffect = psdImage.Layers[3].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Center;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 4. Ajoute un remplissage dégradé, à la position Inside
    strokeEffect = psdImage.Layers[4].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Angle = 90;

    // 5. Ajoute un remplissage dégradé, à la position Outside
    strokeEffect = psdImage.Layers[5].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Outside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 90;

    // 6. Ajoute un remplissage dégradé, à la position Center
    strokeEffect = psdImage.Layers[6].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Center;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 0;

    // 7. Ajoute un motif de remplissage, à la position Inside
    strokeEffect = psdImage.Layers[7].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 200;

    // 8. Ajoute un motif de remplissage, à la position Outside
    strokeEffect = psdImage.Layers[8].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Outside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 100;

    // 9. Ajoute un motif de remplissage, à la position Center
    strokeEffect = psdImage.Layers[9].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Center;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 75;

    psdImage.Save(outputFilePng, new PngOptions());
}
```

### Voir également

* enum [StrokePosition](../../strokeposition/)
* class [StrokeEffect](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../strokeeffect/)
* Assemblée [Aspose.PSD](../../../)


