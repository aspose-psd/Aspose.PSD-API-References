---
title: "Classe ObjectArrayStructure"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.ObjectArrayStructure classe. Définit la classe ObjectArrayStructure qui contient généralement un tableau UnitArrayStructure. Elle est utilisée dans les ressources de fichiers PSD telles que la ressource PlLd et la ressource SoLd."
type: docs
weight: 3590
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/
---
{{< psd/tize >}}
## ObjectArrayStructure class

Définit la classe ObjectArrayStructure qui contient généralement un tableau [`UnitArrayStructure`](../unitarraystructure/). Elle est utilisée dans les ressources de fichiers PSD, telles que la ressource PlLd et la ressource SoLd.

```csharp
public sealed class ObjectArrayStructure : OSTypeStructure
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ObjectArrayStructure](objectarraystructure/#constructor_1)(string, string, OSTypeStructure[]) | Initialise une nouvelle instance de la classe `ObjectArrayStructure`. |
| [ObjectArrayStructure](objectarraystructure/#constructor)(int, ClassID, ClassID, string, OSTypeStructure[]) | Initialise une nouvelle instance de la classe `ObjectArrayStructure`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ClassID](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/classid/) { get; set; } | Obtient ou définit l'ID de la classe du tableau d'objets. |
| [ClassName](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/classname/) { get; set; } | Obtient ou définit le nom de la classe du tableau d'objets. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/key/) { get; } | Obtient la clé de la structure du tableau d'objets. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Obtient ou définit le nom de la clé. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/length/) { get; } | Obtient la longueur en octets du [`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| [StructureCount](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structurecount/) { get; } | Obtient le nombre de sous-structures du tableau d'objets. |
| [Structures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structures/) { get; set; } | Obtient ou définit une copie d'un tableau de structures. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Obtient la longueur de l'en-tête. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Enregistre la structure dans le conteneur de flux spécifié. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Enregistre la structure dans le conteneur de flux spécifié. |

## Champs

| Nom | Description |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structurekey/) | Identifie la clé de structure 'ObAr'. |

## Exemples

Le code suivant montre la prise en charge des signatures ObAr et UnFl.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

var sourceFilePath = "LayeredSmartObjects8bit2.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    UnitArrayStructure verticalStructure = null;
    foreach (Layer imageLayer in image.Layers)
    {
        foreach (var imageResource in imageLayer.Resources)
        {
            var resource = imageResource as PlLdResource;
            if (resource != null && resource.IsCustom)
            {
                foreach (OSTypeStructure structure in resource.Items)
                {
                    if (structure.KeyName.ClassName == "customEnvelopeWarp")
                    {
                        AssertAreEqual(typeof(DescriptorStructure), structure.GetType());
                        var custom = (DescriptorStructure)structure;
                        AssertAreEqual(custom.Structures.Length, 1);
                        var mesh = custom.Structures[0];
                        AssertAreEqual(typeof(ObjectArrayStructure), mesh.GetType());
                        var meshObjectArray = (ObjectArrayStructure)mesh;
                        AssertAreEqual(meshObjectArray.Structures.Length, 2);
                        var vertical = meshObjectArray.Structures[1];
                        AssertAreEqual(typeof(UnitArrayStructure), vertical.GetType());
                        verticalStructure = (UnitArrayStructure)vertical;
                        AssertAreEqual(verticalStructure.UnitType, UnitTypes.Pixels);
                        AssertAreEqual(verticalStructure.ValueCount, 16);

                        break;
                    }
                }
            }
        }
    }

    AssertAreEqual(true, verticalStructure != null);
}
```

### Voir aussi

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../)


