---
title: "PathStructure.Key"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété PathStructure. Obtient la clé de la structure"
type: docs
weight: 20
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/
---
{{< psd/tize >}}
## PathStructure.Key property

Obtient la clé de structure.

```csharp
public override int Key { get; }
```

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


