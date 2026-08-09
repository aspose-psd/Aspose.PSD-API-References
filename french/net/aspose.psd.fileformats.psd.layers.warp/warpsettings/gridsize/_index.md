---
title: "WarpSettings.GridSize"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété WarpSettings. Obtient ou définit la taille de la grille de déformation. La valeur par défaut est 1"
type: docs
weight: 30
url: /fr/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/gridsize/
---
{{< psd/tize >}}
## WarpSettings.GridSize property

Obtient ou définit la taille de la grille warp. La valeur par défaut est 1.

```csharp
public Size GridSize { get; set; }
```

## Exemples

Le code suivant montre la prise en charge de la propriété WarpSettings.GridSize.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Obtenir les paramètres de déformation
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Définir une nouvelle taille
    // Pour Photoshop, la valeur peut être comprise entre 1 et 50 et vous ne pouvez pas enregistrer correctement le fichier PSD.
    warpSettings.GridSize = new Size(100, 100);

    // Définir une valeur valide
    warpSettings.GridSize = new Size(3, 3);

    // Rendre le fichier d'exemple avec une grille x3
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Voir aussi

* struct [Size](../../../aspose.psd/size/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


