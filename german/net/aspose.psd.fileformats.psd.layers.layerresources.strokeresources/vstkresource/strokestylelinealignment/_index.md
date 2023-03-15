---
title: VstkResource.StrokeStyleLineAlignment
second_title: Aspose.PSD für .NET-API-Referenz
description: VstkResource eigendom. Ruft die Linienausrichtung des Strichstils ab oder legt sie fest.
type: docs
weight: 100
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinealignment/
---
## VstkResource.StrokeStyleLineAlignment property

Ruft die Linienausrichtung des Strichstils ab oder legt sie fest.

```csharp
public StrokePosition StrokeStyleLineAlignment { get; set; }
```

### Beispiele

Der folgende Code demonstriert die Unterstützung der VstkResource-Ressource.

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

### Siehe auch

* enum [StrokePosition](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeposition/)
* class [VstkResource](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* Montage [Aspose.PSD](../../../)


