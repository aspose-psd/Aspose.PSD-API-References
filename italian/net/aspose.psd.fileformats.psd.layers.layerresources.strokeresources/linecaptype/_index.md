---
title: Enum LineCapType
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineCapType enum. Tipo di capolinea.
type: docs
weight: 3040
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype/
---
## LineCapType enumeration

Tipo di capolinea.

```csharp
public enum LineCapType : short
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| RoundCap | `0` | Tipo di tappo tondo. |
| SquareCap | `1` | Tipo di tappo quadrato. |
| ButtCap | `2` | Tipo di tappo di testa. |

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


