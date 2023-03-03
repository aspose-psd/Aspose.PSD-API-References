---
title: Enum LineCapType
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineCapType énumération. Type de limite de ligne.
type: docs
weight: 3040
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype/
---
## LineCapType enumeration

Type de limite de ligne.

```csharp
public enum LineCapType : short
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| RoundCap | `0` | Type de bouchon rond. |
| SquareCap | `1` | Type de bouchon carré. |
| ButtCap | `2` | Type de bouchon bout à bout. |

### Exemples

Le code suivant illustre la prise en charge de la ressource VstkResource.

```csharp
[C#]

string srcFile = "StrokeShapeTest1.psd";
string dstFile = "StrokeShapeTest2.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    Layer layer = image.Layers[1];
    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is VstkResource)
        {
            VstkResource vstkResource = (VstkResource)resource;
            vstkResource.StrokeStyleLineAlignment = StrokePosition.Outside;
            vstkResource.StrokeStyleLineWidth = 20;
        }
    }

    image.Save(dstFile);
}
```

### Voir également

* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* Assemblée [Aspose.PSD](../../)


