---
title: Enum LineJoinType
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineJoinType énumération. Type de jointure de ligne.
type: docs
weight: 3050
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype/
---
## LineJoinType enumeration

Type de jointure de ligne.

```csharp
public enum LineJoinType : short
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| BevelJoin | `0` | Type de jointure biseautée. |
| RoundJoin | `1` | Type de jointure ronde. |
| MiterJoin | `2` | Type de jointure mitre. |

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


