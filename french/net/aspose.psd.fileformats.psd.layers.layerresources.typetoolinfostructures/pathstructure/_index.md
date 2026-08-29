---
title: "Classe PathStructure"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.PathStructure classe. La structure de chemin"
type: docs
weight: 3610
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/
---
{{< psd/tize >}}
## PathStructure class

La structure de chemin.

```csharp
public sealed class PathStructure : OSTypeStructure
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PathStructure](pathstructure/)(ClassID) | Initialise une nouvelle instance de la classe `PathStructure`. |

## Propriétés

| Nom | Description |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/) { get; } | Obtient la clé de structure. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Obtient ou définit le nom de la clé. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/) { get; } | Obtient la longueur en octets du [`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| [Path](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/) { get; set; } | Obtient ou définit le chemin. |
| [Prefix](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/) { get; set; } | Obtient ou définit le préfixe du chemin. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Obtient la longueur de l'en-tête. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Enregistre la structure dans le conteneur de flux spécifié. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Enregistre la structure dans le conteneur de flux spécifié. |

## Champs

| Nom | Description |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/structurekey/) | Identifie la clé de structure. |

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

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../)


