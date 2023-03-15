---
title: VstkResource.StrokeStyleLineAlignment
second_title: Référence de l'API Aspose.PSD pour .NET
description: VstkResource propriété. Obtient ou définit lalignement des lignes de style Stroke.
type: docs
weight: 100
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinealignment/
---
## VstkResource.StrokeStyleLineAlignment property

Obtient ou définit l'alignement des lignes de style Stroke.

```csharp
public StrokePosition StrokeStyleLineAlignment { get; set; }
```

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

* enum [StrokePosition](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeposition/)
* class [VstkResource](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* Assemblée [Aspose.PSD](../../../)


