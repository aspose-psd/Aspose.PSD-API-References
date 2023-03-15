---
title: IGradientFillSettings.Scale
second_title: Référence de l'API Aspose.PSD pour .NET
description: IGradientFillSettings propriété. Obtient ou définit léchelle.
type: docs
weight: 100
url: /fr/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
## IGradientFillSettings.Scale property

Obtient ou définit l'échelle.

```csharp
public int Scale { get; set; }
```

### Valeur de la propriété

L'échelle.

### Exemples

L'exemple suivant montre comment utiliser la propriété Scale pour mettre à l'échelle FillLayer avec un dégradé.

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // obtention d'un calque de remplissage
    FillLayer fillLayer = null;
    foreach (var layer in image.Layers)
    {
        fillLayer = layer as FillLayer;
        if (fillLayer != null)
        {
            break;
        }
    }

    var settings = fillLayer.FillSettings as IGradientFillSettings;

    // met à jour la valeur de l'échelle
    settings.Scale = 200;
    fillLayer.Update(); // Met à jour les données de pixels

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Voir également

* interface [IGradientFillSettings](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../igradientfillsettings/)
* Assemblée [Aspose.PSD](../../../)


