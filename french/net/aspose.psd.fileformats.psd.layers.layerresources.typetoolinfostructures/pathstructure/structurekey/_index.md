---
title: PathStructure.StructureKey
second_title: Référence de l'API Aspose.PSD pour .NET
description: PathStructure champ. Identifie la clé de structure.
type: docs
weight: 60
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/structurekey/
---
## PathStructure.StructureKey field

Identifie la clé de structure.

```csharp
public const int StructureKey;
```

### Exemples

Le code suivant montre la possibilité de charger un fichier avec la structure PathStructure.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### Voir également

* class [PathStructure](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* Assemblée [Aspose.PSD](../../../)


