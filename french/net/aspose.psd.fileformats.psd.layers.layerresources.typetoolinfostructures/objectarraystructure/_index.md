---
title: ObjectArrayStructure
second_title: Référence de l'API Aspose.PSD pour .NET
description: Définit la classe ObjectArrayStructure qui contient généralementUnitArrayStructure./unitarraystructure array. Il est utilisé dans les ressources du fichier PSD telles que PlLd Resource et SoLd Resource.
type: docs
weight: 3140
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/
---
## ObjectArrayStructure class

Définit la classe ObjectArrayStructure qui contient généralement[`UnitArrayStructure`](../unitarraystructure) array. Il est utilisé dans les ressources du fichier PSD, telles que PlLd Resource et SoLd Resource.

```csharp
public sealed class ObjectArrayStructure : OSTypeStructure
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ObjectArrayStructure](objectarraystructure#constructor_1)(string, string, OSTypeStructure[]) | Initialise une nouvelle instance du[`ObjectArrayStructure`](../objectarraystructure) classe. |
| [ObjectArrayStructure](objectarraystructure#constructor)(int, ClassID, ClassID, string, OSTypeStructure[]) | Initialise une nouvelle instance du[`ObjectArrayStructure`](../objectarraystructure) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [ClassID](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/classid) { get; set; } | Obtient ou définit l'ID de classe de tableau d'objets. |
| [ClassName](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/classname) { get; set; } | Obtient ou définit le nom de la classe de tableau d'objets. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/key) { get; } | Obtient la clé de structure du tableau d'objets. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname) { get; set; } | Obtient ou définit le nom de la clé. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/length) { get; } | Obtient le[`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) longueur en octets. |
| [StructureCount](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structurecount) { get; } | Obtient le nombre de sous-structures de tableau d'objets. |
| [Structures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structures) { get; set; } | Obtient ou définit une copie d'un tableau de structures. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength)() | Obtient la longueur de l'en-tête. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save)(StreamContainer) | Enregistre la structure dans le conteneur de flux spécifié. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname)(StreamContainer) | Enregistre la structure dans le conteneur de flux spécifié. |

## Des champs

| Nom | La description |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structurekey) | Identifie la clé de structure 'ObAr'. |

### Exemples

Le code suivant illustre la prise en charge des signatures ObAr et UnFl.

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

### Voir également

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures)
* Assemblée [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
