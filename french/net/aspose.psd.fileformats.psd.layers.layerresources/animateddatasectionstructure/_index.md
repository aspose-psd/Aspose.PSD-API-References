---
title: "Classe AnimatedDataSectionStructure"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.AnimatedDataSectionStructure classe. La section contenant des données animées."
type: docs
weight: 2510
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/
---
{{< psd/tize >}}
## AnimatedDataSectionStructure class

La section contenant les données animées.

```csharp
public class AnimatedDataSectionStructure : OSTypeStructure
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/items/) { get; } | Obtient ou définit les structures de sections de données animées. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/key/) { get; } | Obtient la clé de structure. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Obtient ou définit le nom de la clé. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/length/) { get; } | Obtient la longueur en octets du [`OSTypeStructure`](../ostypestructure/). |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Obtient la longueur de l'en-tête. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Enregistre la structure dans le conteneur de flux spécifié. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Enregistre la structure dans le conteneur de flux spécifié. |

## Champs

| Nom | Description |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/structurekey/) | Identifie la clé de structure de AnDs. |

## Exemples

Le code suivant montre comment définir/mettre à jour le temps de retard dans la trame de la chronologie des données animées.

```csharp
[C#]

string sourceFile = "3_animated.psd";
string outputPsd = "output_3_animated.psd";

T FindStructure<T>(IEnumerable<OSTypeStructure> structures, string keyName) where T : OSTypeStructure
{
    foreach (var structure in structures)
    {
        if (structure.KeyName.ClassName == keyName)
        {
            return structure as T;
        }
    }

    return null;
}

OSTypeStructure[] AddOrReplaceStructure(IEnumerable<OSTypeStructure> structures, OSTypeStructure newStructure)
{
    List<OSTypeStructure> listOfStructures = new List<OSTypeStructure>(structures);

    for (int i = 0; i < listOfStructures.Count; i++)
    {
        OSTypeStructure structure = listOfStructures[i];
        if (structure.KeyName.ClassName == newStructure.KeyName.ClassName)
        {
            listOfStructures.RemoveAt(i);
            break;
        }
    }

    listOfStructures.Add(newStructure);

    return listOfStructures.ToArray();
}

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    foreach (var imageResource in image.ImageResources)
    {
        if (imageResource is AnimatedDataSectionResource)
        {
            var animatedData =
                (AnimatedDataSectionStructure) (imageResource as AnimatedDataSectionResource).AnimatedDataSection;
            var framesList = FindStructure<ListStructure>(animatedData.Items, "FrIn");

            var frame1 = (DescriptorStructure)framesList.Types[1];

            // Crée l'enregistrement de retard de trame avec la valeur 100 centi-secondes, équivalente à 1 seconde.
            var frameDelay = new IntegerStructure(new ClassID("FrDl"));
            frameDelay.Value = 100; // set time in centi-seconds.

            frame1.Structures = AddOrReplaceStructure(frame1.Structures, frameDelay);

            break;
        }
    }

    image.Save(outputPsd);
}
```

### Voir aussi

* class [OSTypeStructure](../ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


