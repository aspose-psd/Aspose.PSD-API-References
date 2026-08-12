---
title: "PostResource.Levels"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad PostResource. Niveles de la capa Posterize"
type: docs
weight: 30
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/postresource/levels/
---
{{< psd/tize >}}
## PostResource.Levels property

Niveles de la capa Posterize.

```csharp
public short Levels { get; set; }
```

### Valor devuelto

Valor entero Levels

## Ejemplos

El siguiente código demuestra la capacidad de manipular PostResource.

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

### Ver también

* class [PostResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


