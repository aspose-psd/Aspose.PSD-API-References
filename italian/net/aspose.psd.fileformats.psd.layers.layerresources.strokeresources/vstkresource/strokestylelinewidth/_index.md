---
title: VstkResource.StrokeStyleLineWidth
second_title: Aspose.PSD per riferimento API .NET
description: VstkResource proprietà. Ottiene o imposta la larghezza della linea Stroke.
type: docs
weight: 160
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinewidth/
---
## VstkResource.StrokeStyleLineWidth property

Ottiene o imposta la larghezza della linea Stroke.

```csharp
public double StrokeStyleLineWidth { get; set; }
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

* class [VstkResource](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* assemblea [Aspose.PSD](../../../)


