---
title: "Enum LineJoinType"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineJoinType enum. Type de jointure de ligne"
type: docs
weight: 3410
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype/
---
{{< psd/tize >}}
## LineJoinType enumeration

Type de jointure de ligne.

```csharp
public enum LineJoinType : short
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| BevelJoin | `0` | Type de jointure biseau. |
| RoundJoin | `1` | Type de jointure ronde. |
| MiterJoin | `2` | Type de jointure en onglet. |

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


