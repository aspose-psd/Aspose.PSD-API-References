---
title: Enum LineJoinType
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineJoinType enum. Tipo di unione di linee.
type: docs
weight: 3050
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype/
---
## LineJoinType enumeration

Tipo di unione di linee.

```csharp
public enum LineJoinType : short
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| BevelJoin | `0` | Tipo di giunzione smussata. |
| RoundJoin | `1` | Tipo di giunzione arrotondata. |
| MiterJoin | `2` | Tipo di giunzione ad angolo. |

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

* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assemblea [Aspose.PSD](../../)


