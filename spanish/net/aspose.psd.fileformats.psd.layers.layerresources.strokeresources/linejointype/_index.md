---
title: Enum LineJoinType
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineJoinType enumeración. Tipo de unión de línea.
type: docs
weight: 3050
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype/
---
## LineJoinType enumeration

Tipo de unión de línea.

```csharp
public enum LineJoinType : short
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| BevelJoin | `0` | Tipo de unión en bisel. |
| RoundJoin | `1` | Tipo de unión redonda. |
| MiterJoin | `2` | Tipo de unión a inglete. |

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


