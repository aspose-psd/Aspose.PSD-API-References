---
title: Class PathStructure
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.PathStructure classe. La structure du chemin.
type: docs
weight: 3220
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/
---
## PathStructure class

La structure du chemin.

```csharp
public sealed class PathStructure : OSTypeStructure
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PathStructure](pathstructure/)(ClassID) | Initialise une nouvelle instance du`PathStructure` classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/) { get; } | Obtient la clé de structure. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Obtient ou définit le nom de la clé. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/) { get; } | Obtient le[`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) longueur en octets. |
| [Path](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/) { get; set; } | Obtient ou définit le chemin. |
| [Prefix](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/) { get; set; } | Obtient ou définit le préfixe du chemin. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Obtient la longueur de l'en-tête. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Enregistre la structure dans le conteneur de flux spécifié. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Enregistre la structure dans le conteneur de flux spécifié. |

## Des champs

| Nom | La description |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/structurekey/) | Identifie la clé de structure. |

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

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* Assemblée [Aspose.PSD](../../)


