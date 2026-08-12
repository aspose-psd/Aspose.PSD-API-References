---
title: "PostResource.Levels"
second_title: "Aspose.PSD för .NET API‑referens"
description: "PostResource property. Nivåer för Posterize-lager"
type: docs
weight: 30
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/postresource/levels/
---
{{< psd/tize >}}
## PostResource.Levels property

Nivåer för Posterize‑lagret.

```csharp
public short Levels { get; set; }
```

### Returvärde

Nivåer int-värde

## Exempel

Följande kod demonstrerar möjligheten att manipulera PostResource.

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

### Se även

* class [PostResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


