---
title: "PathStructure.Path"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété PathStructure. Obtient ou définit le chemin"
type: docs
weight: 40
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/
---
{{< psd/tize >}}
## PathStructure.Path property

Obtient ou définit le chemin.

```csharp
public string Path { get; set; }
```

### Property Value

Le chemin complet.

## Exemples

Le code suivant montre la capacité de charger un fichier avec la structure PathStructure.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### Voir aussi

* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


