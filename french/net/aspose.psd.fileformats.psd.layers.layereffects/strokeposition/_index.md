---
title: "Énumération StrokePosition"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Énumération Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.StrokePosition. Le paramètre de position contrôle l'alignement de votre contour par rapport au calque auquel il est appliqué dans le StrokeEffect"
type: docs
weight: 2400
url: /fr/net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/
---
{{< psd/tize >}}
## StrokePosition enumeration

Le paramètre de position contrôle l'alignement de votre contour par rapport au calque auquel il est appliqué dans le [`StrokeEffect`](../strokeeffect/).

```csharp
public enum StrokePosition : short
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Inside | `0` | Le contour sera créé à partir du bord de la forme et s'étendra vers l'intérieur, jusqu'au centre de l'objet. |
| Center | `1` | Le contour sera créé à partir du bord de la forme et s'étendra à la fois vers l'intérieur et vers l'extérieur. |
| Outside | `2` | Le contour sera créé à partir du bord de la forme et s'étendra vers l'extérieur, loin de l'objet. |

## Exemples

Cet exemple montre la capacité d'ajouter l'effet de contour avec différents types de remplissage tels que Couleur, Dégradé ou Motif.

```csharp
[C#]

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    StrokeEffect strokeEffect;
    IColorFillSettings colorFillSettings;
    IGradientFillSettings gradientFillSettings;
    IPatternFillSettings patternFillSettings;

    // 1. Ajoute un remplissage Couleur, à la position Intérieur
    strokeEffect = psdImage.Layers[1].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Inside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 2. Ajoute un remplissage Couleur, à la position Extérieur
    strokeEffect = psdImage.Layers[2].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Outside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 3. Ajoute un remplissage Couleur, à la position Centre
    strokeEffect = psdImage.Layers[3].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Center;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 4. Ajoute un remplissage Dégradé, à la position Intérieur
    strokeEffect = psdImage.Layers[4].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Angle = 90;

    // 5. Ajoute un remplissage Dégradé, à la position Extérieur
    strokeEffect = psdImage.Layers[5].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Outside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 90;

    // 6. Ajoute un remplissage Dégradé, à la position Centre
    strokeEffect = psdImage.Layers[6].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Center;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 0;

    // 7. Ajoute un remplissage Motif, à la position Intérieur
    strokeEffect = psdImage.Layers[7].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 200;

    // 8. Ajoute un remplissage Motif, à la position Extérieur
    strokeEffect = psdImage.Layers[8].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Outside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 100;

    // 9. Ajoute un remplissage Motif, à la position Centre
    strokeEffect = psdImage.Layers[9].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Center;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 75;

    psdImage.Save(outputFilePng, new PngOptions());
}
```

### Voir aussi

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


