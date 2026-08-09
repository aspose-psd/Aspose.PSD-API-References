---
title: "PostResource.Levels"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PostResource-Eigenschaft. Ebenen der Posterize-Schicht."
type: docs
weight: 30
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/postresource/levels/
---
{{< psd/tize >}}
## PostResource.Levels property

Stufen der Posterize Ebene.

```csharp
public short Levels { get; set; }
```

### Rückgabewert

Levels int-Wert

## Beispiele

Der folgende Code demonstriert die Fähigkeit zur Manipulation von PostResource.

```csharp
[C#]

string sourceFile = "zendeya_posterize.psd";
string outputFile = "zendeya_posterize_10.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];

    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is PostResource)
        {
            ((PostResource)resource).Levels = 10;
            image.Save(outputFile);

            break;
        }
    }
}
```

### Siehe auch

* class [PostResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


