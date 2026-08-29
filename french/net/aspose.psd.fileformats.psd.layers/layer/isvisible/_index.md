---
title: "Layer.IsVisible"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété Layer. Obtient ou définit une valeur indiquant si le calque est visible"
type: docs
weight: 180
url: /fr/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
{{< psd/tize >}}
## Layer.IsVisible property

Obtient ou définit une valeur indiquant si le calque est visible

```csharp
public bool IsVisible { get; set; }
```

### Property Value

`true` si cette instance est visible ; sinon, `false`.

## Exemples

L'exemple suivant montre comment vous pouvez modifier la visibilité du LayerGroup dans Aspose.PSD

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// apportez des modifications aux noms des calques et enregistrez-le
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Désactivez tout à l'intérieur d'un groupe
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### Voir aussi

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


