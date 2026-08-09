---
title: "WarpSettings.RenderQuality"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "WarpSettings propriété. Obtient ou définit la valeur de la qualité de rendu du warp entre vitesse et qualité"
type: docs
weight: 50
url: /fr/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/renderquality/
---
{{< psd/tize >}}
## WarpSettings.RenderQuality property

Obtient ou définit la valeur de la qualité de rendu warp - entre vitesse et qualité

```csharp
public RenderQuality RenderQuality { get; set; }
```

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

* enum [RenderQuality](../../renderquality/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


