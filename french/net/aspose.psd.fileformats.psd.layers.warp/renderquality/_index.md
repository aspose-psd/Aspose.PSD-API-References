---
title: "Enum RenderQuality"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.RenderQuality enum. Il décrit la qualité de rendu de la déformation"
type: docs
weight: 3990
url: /fr/net/aspose.psd.fileformats.psd.layers.warp/renderquality/
---
{{< psd/tize >}}
## RenderQuality enumeration

Il décrit la qualité de rendu de la déformation.

```csharp
public enum RenderQuality
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Turbo | `4` | L'option la plus rapide, mais la qualité en souffre. |
| VeryFast | `18` | Si vous avez besoin de rapidité, cela peut convenir aux petites courbures. |
| Fast | `35` | Permet d'accélérer le rendu avec une légère perte de qualité. |
| Normal | `60` | Valeur recommandée pour la plupart des courbures |
| Good | `130` | Qualité supérieure à la norme, vitesse plus lente. Recommandé pour les fortes distorsions. |
| Excellent | `260` | L'option la plus lente. Recommandé pour les fortes distorsions et les hautes résolutions. |

## Exemples

Le code suivant montre la propriété WarpSettings.RenderQuality pour configurer la déformation du warp.

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

RenderQuality[] qualityValues = { RenderQuality.Turbo, RenderQuality.Fast, RenderQuality.Normal, RenderQuality.Excellent };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // Il récupère WarpSettings depuis Smart Layer
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Il définit la taille de la zone de traitement du warp
        warpSettings.RenderQuality = qualityValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + qualityValues[i].ToString() + ".png";
        outputFiles.Add(outputFile);

        // Il ne devrait y avoir aucune erreur ici
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Voir aussi

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


