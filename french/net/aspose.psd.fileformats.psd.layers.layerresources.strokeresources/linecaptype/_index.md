---
title: "Enum LineCapType"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineCapType enum. type de terminaison de ligne"
type: docs
weight: 3400
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype/
---
{{< psd/tize >}}
## LineCapType enumeration

Type d'extrémité de ligne.

```csharp
public enum LineCapType : short
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| RoundCap | `0` | Type de terminaison ronde. |
| SquareCap | `1` | Type de terminaison carrée. |
| ButtCap | `2` | Type de terminaison bout. |

## Exemples

Le code suivant démontre la prise en charge de la ressource VstkResource.

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

### Voir aussi

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


