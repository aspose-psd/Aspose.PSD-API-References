---
title: PathStructure.Length
second_title: Référence de l'API Aspose.PSD pour .NET
description: PathStructure propriété. Obtient leOSTypeStructure longueur en octets.
type: docs
weight: 30
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/
---
## PathStructure.Length property

Obtient le[`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) longueur en octets.

```csharp
public override int Length { get; }
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


