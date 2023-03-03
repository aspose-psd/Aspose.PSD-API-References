---
title: PathStructure.PathStructure
second_title: Référence de l'API Aspose.PSD pour .NET
description: PathStructure constructeur. Initialise une nouvelle instance duPathStructure classe.
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
## PathStructure constructor

Initialise une nouvelle instance du[`PathStructure`](../) classe.

```csharp
public PathStructure(ClassID keyName)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| keyName | ClassID | Le nom de la clé. |

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

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* Assemblée [Aspose.PSD](../../../)


