---
title: "IGradientFillSettings.Scale"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété IGradientFillSettings. Obtient ou définit l'échelle du dégradé normalisée en pourcentage"
type: docs
weight: 90
url: /fr/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
{{< psd/tize >}}
## IGradientFillSettings.Scale property

Obtient ou définit l'échelle de gradient **normalisée** (en pourcentage).

```csharp
public int Scale { get; set; }
```

### Property Value

L'échelle.

## Exemples

L'exemple suivant montre comment utiliser la propriété Scale pour mettre à l'échelle FillLayer avec un dégradé.

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // obtenir une couche de remplissage
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

    // mettre à jour la valeur d'échelle
    settings.Scale = 200;
    fillLayer.Update(); // Updates pixels data

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Voir aussi

* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


