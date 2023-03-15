---
title: Enum LineCapType
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineCapType enumeración. Tipo de límite de línea.
type: docs
weight: 3040
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype/
---
## LineCapType enumeration

Tipo de límite de línea.

```csharp
public enum LineCapType : short
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| RoundCap | `0` | Tipo tapa redonda. |
| SquareCap | `1` | Tipo tapa cuadrada. |
| ButtCap | `2` | Tipo tapa a tope. |

### Ejemplos

El código siguiente demuestra la compatibilidad con el recurso VstkResource.

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

* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* asamblea [Aspose.PSD](../../)


