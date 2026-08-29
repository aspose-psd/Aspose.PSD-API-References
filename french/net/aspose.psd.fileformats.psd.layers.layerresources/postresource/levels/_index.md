---
title: "PostResource.Levels"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété PostResource. Niveaux du calque Posterize"
type: docs
weight: 30
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/postresource/levels/
---
{{< psd/tize >}}
## PostResource.Levels property

Niveaux du calque Posterize.

```csharp
public short Levels { get; set; }
```

### Valeur de retour

Valeur int Levels

## Exemples

Le code suivant démontre la capacité de manipulation de PostResource.

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

### Voir aussi

* class [PostResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


