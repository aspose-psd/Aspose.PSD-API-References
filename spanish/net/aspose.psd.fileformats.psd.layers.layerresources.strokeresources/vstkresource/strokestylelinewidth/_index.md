---
title: VstkResource.StrokeStyleLineWidth
second_title: Referencia de API de Aspose.PSD para .NET
description: VstkResource propiedad. Obtiene o establece Ancho de línea de trazo.
type: docs
weight: 160
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinewidth/
---
## VstkResource.StrokeStyleLineWidth property

Obtiene o establece Ancho de línea de trazo.

```csharp
public double StrokeStyleLineWidth { get; set; }
```

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

* class [VstkResource](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* asamblea [Aspose.PSD](../../../)


