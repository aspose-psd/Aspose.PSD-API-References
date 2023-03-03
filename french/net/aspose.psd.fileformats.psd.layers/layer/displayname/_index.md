---
title: Layer.DisplayName
second_title: Référence de l'API Aspose.PSD pour .NET
description: Layer propriété. Obtient ou définit le nom daffichage de la couche.
type: docs
weight: 100
url: /fr/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
## Layer.DisplayName property

Obtient ou définit le nom d'affichage de la couche.

```csharp
public string DisplayName { get; set; }
```

### Valeur de la propriété

Le nom d'affichage de la couche.

### Exemples

L'exemple suivant montre la possibilité de définir la valeur DisplayName, dans laquelle le nom de la couche s'affiche correctement.

```csharp
[C#]

// apportez des modifications aux noms de couches et enregistrez-les
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // définit une nouvelle valeur dans la propriété DisplayName
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### Voir également

* class [Layer](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* Assemblée [Aspose.PSD](../../../)


