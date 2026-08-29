---
title: "PathStructure.Length"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété PathStructure. Obtient la longueur OSTypeStructure en octets"
type: docs
weight: 30
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/
---
{{< psd/tize >}}
## PathStructure.Length property

Obtient la longueur en octets du [`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/).

```csharp
public override int Length { get; }
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


