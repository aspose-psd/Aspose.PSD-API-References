---
title: Class UnitArrayStructure
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.UnitArrayStructure classe. Définit la classe UnitArrayStructure qui contientDouble tableau de valeurs et leur unité de mesure. Il est utilisé dans les ressources du fichier PSD généralement parObjectArrayStructure .
type: docs
weight: 3270
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/
---
## UnitArrayStructure class

Définit la classe UnitArrayStructure qui contientDouble tableau de valeurs et leur unité de mesure. Il est utilisé dans les ressources du fichier PSD, généralement par[`ObjectArrayStructure`](../objectarraystructure/) .

```csharp
public sealed class UnitArrayStructure : OSTypeStructure
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [UnitArrayStructure](unitarraystructure/)(ClassID, UnitTypes, double[]) | Initialise une nouvelle instance du`UnitArrayStructure` classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/key/) { get; } | Obtient cette clé de structure de tableau d'unités. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Obtient ou définit le nom de la clé. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/length/) { get; } | Obtient le[`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) longueur en octets. |
| [UnitType](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/unittype/) { get; set; } | Obtient ou définit le type d'unité de mesure du`UnitArrayStructure` valeurs. |
| [ValueCount](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/valuecount/) { get; } | Obtient le nombre de valeurs. |
| [Values](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/values/) { get; set; } | Obtient ou définit les valeurs de structure de tableau d'unités. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Obtient la longueur de l'en-tête. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Enregistre la structure dans le conteneur de flux spécifié. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Enregistre la structure dans le conteneur de flux spécifié. |

## Des champs

| Nom | La description |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/structurekey/) | Définit le 'UnFl'`UnitArrayStructure` clé. |

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

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* Assemblée [Aspose.PSD](../../)


