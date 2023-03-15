---
title: VstkResource.StrokeStyleLineAlignment
second_title: Aspose.PSD per riferimento API .NET
description: VstkResource proprietà. Ottiene o imposta lallineamento della linea in stile Stroke.
type: docs
weight: 100
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinealignment/
---
## VstkResource.StrokeStyleLineAlignment property

Ottiene o imposta l'allineamento della linea in stile Stroke.

```csharp
public StrokePosition StrokeStyleLineAlignment { get; set; }
```

### Esempi

Il codice seguente illustra il supporto della risorsa VstkResource.

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

### Guarda anche

* enum [StrokePosition](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeposition/)
* class [VstkResource](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* assemblea [Aspose.PSD](../../../)


