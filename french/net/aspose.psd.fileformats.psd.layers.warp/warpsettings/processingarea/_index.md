---
title: "WarpSettings.ProcessingArea"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété WarpSettings. Obtient ou définit la valeur de la taille de la zone de traitement. La valeur par défaut est 10. La plage est 240."
type: docs
weight: 40
url: /fr/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/processingarea/
---
{{< psd/tize >}}
## WarpSettings.ProcessingArea property

Obtient ou définit la valeur de la taille de la zone de traitement. La valeur par défaut est 10. La plage est [2;40]

```csharp
public int ProcessingArea { get; set; }
```

## Exemples

Le code suivant montre la propriété WarpSettings.ProcessingArea pour configurer la déformation du warp.

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

int[] areaValues = { 5, 10, 25, 40 };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // Il récupère WarpSettings depuis Smart Layer
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Il définit la taille de la zone de traitement du warp
        warpSettings.ProcessingArea = areaValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + areaValues[i] + ".png";
        outputFiles.Add(outputFile);

        // Il ne devrait y avoir aucune erreur ici
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Voir aussi

* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


