---
title: VstkResource.StrokeStyleLineAlignment
second_title: Referencia de API de Aspose.PSD para .NET
description: VstkResource propiedad. Obtiene o establece la alineación de línea de estilo de trazo.
type: docs
weight: 100
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinealignment/
---
## VstkResource.StrokeStyleLineAlignment property

Obtiene o establece la alineación de línea de estilo de trazo.

```csharp
public StrokePosition StrokeStyleLineAlignment { get; set; }
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

* enum [StrokePosition](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeposition/)
* class [VstkResource](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* asamblea [Aspose.PSD](../../../)


