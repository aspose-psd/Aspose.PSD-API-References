---
title: "PathStructure.PathStructure"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Constructeur PathStructure. Initialise une nouvelle instance de la classe PathStructure"
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
{{< psd/tize >}}
## PathStructure constructor

Initialise une nouvelle instance de la classe [`PathStructure`](../).

```csharp
public PathStructure(ClassID keyName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| keyName | ClassID | Le nom de la clé. |

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

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


