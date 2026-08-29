---
title: "VstkResource.StrokeStyleLineWidth"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété VstkResource. Obtient ou définit la largeur de ligne du trait"
type: docs
weight: 140
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinewidth/
---
{{< psd/tize >}}
## VstkResource.StrokeStyleLineWidth property

Obtient ou définit la largeur de ligne du tracé.

```csharp
public double StrokeStyleLineWidth { get; set; }
```

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

* class [VstkResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../../)


