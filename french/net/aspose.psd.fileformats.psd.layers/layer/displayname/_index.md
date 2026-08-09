---
title: "Layer.DisplayName"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété Layer. Obtient ou définit le nom d’affichage du calque"
type: docs
weight: 110
url: /fr/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
{{< psd/tize >}}
## Layer.DisplayName property

Obtient ou définit le nom d'affichage du calque.

```csharp
public string DisplayName { get; set; }
```

### Property Value

Le nom d’affichage du calque.

## Exemples

L’exemple suivant montre la capacité de définir la valeur DisplayName, afin que le nom du calque s’affiche correctement.

```csharp
[C#]

// apportez des modifications aux noms des calques et enregistrez-le
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // définir une nouvelle valeur dans la propriété DisplayName
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### Voir aussi

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


