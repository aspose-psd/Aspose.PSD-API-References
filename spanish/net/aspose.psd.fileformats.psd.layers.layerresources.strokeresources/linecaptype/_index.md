---
title: "Enumeración LineCapType"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineCapType enum. Tipo de extremo de línea"
type: docs
weight: 3400
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype/
---
{{< psd/tize >}}
## LineCapType enumeration

Tipo de terminación de línea.

```csharp
public enum LineCapType : short
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| RoundCap | `0` | Tipo de extremo redondo. |
| SquareCap | `1` | Tipo de extremo cuadrado. |
| ButtCap | `2` | Tipo de extremo plano. |

## Ejemplos

El siguiente código demuestra el soporte del recurso VstkResource.

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

### Ver también

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


