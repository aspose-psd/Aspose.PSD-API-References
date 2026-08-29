---
title: "Classe NameStructure"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.NameStructure classe. La clé de structure Name 0x6E616D65 qui correspond à « name » en ASCII est une structure simple utilisée pour stocker une chaîne Unicode ou de style Pascal représentant le nom d'un élément tel qu'un chemin de calque ou un réglage."
type: docs
weight: 3580
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/
---
{{< psd/tize >}}
## NameStructure class

La structure Name (clé : 0x6E616D65, qui correspond à "name" en ASCII) est une structure simple utilisée pour stocker une chaîne Unicode ou de style Pascal représentant le nom d'un élément, tel qu'un calque, un chemin ou un réglage.

```csharp
public sealed class NameStructure : OSTypeStructure
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [NameStructure](namestructure/)(ClassID) | Initialise une nouvelle instance de la classe `NameStructure`. |

## Propriétés

| Nom | Description |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/key/) { get; } | Obtient la clé. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Obtient ou définit le nom de la clé. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/length/) { get; } | Obtient la longueur en octets du [`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/value/) { get; set; } | Obtient ou définit la valeur d'une structure Name. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Obtient la longueur de l'en-tête. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Enregistre la structure dans le conteneur de flux spécifié. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Enregistre la structure dans le conteneur de flux spécifié. |

## Champs

| Nom | Description |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/structurekey/) | La clé de la structure Name. |

## Exemples

Le code suivant démontre la prise en charge de NameStructure.

```csharp
[C#]

string inputFile = "Mixer_ipad_Hand_W_crash.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(inputFile, new PsdLoadOptions { DataRecoveryMode = DataRecoveryMode.MaximalRecover }))
{
    //// Le fichier est chargé avec succès

    SmartObjectLayer layer = (SmartObjectLayer)psdImage.Layers[3];
    SoLdResource resource = (SoLdResource)layer.Resources[9];

    DescriptorStructure struct1 = (DescriptorStructure)resource.Items[15];
    ListStructure struct2 = (ListStructure)struct1.Structures[5];
    DescriptorStructure struct3 = (DescriptorStructure)struct2.Types[0];
    DescriptorStructure struct4 = (DescriptorStructure)struct3.Structures[6];
    ReferenceStructure struct5 = (ReferenceStructure)struct4.Structures[8];
    NameStructure nameStructure = (NameStructure)struct5.Items[0];

    AssertIsNotNull(nameStructure);
    AssertAreEqual(37, nameStructure.Length);
    AssertAreEqual("None\0", nameStructure.Value);

    // Enregistrez le fichier de test sans modifications
    psdImage.Save(outputFile);

    //// Le fichier doit être ouvert dans PS sans erreurs
}

// Vérifiez que les structures des effets d'éclairage sont enregistrées correctement
using (var psdImage = (PsdImage)Image.Load(
           outputFile,
           new PsdLoadOptions { DataRecoveryMode = DataRecoveryMode.MaximalRecover }))
{
    SmartObjectLayer layer = (SmartObjectLayer)psdImage.Layers[3];
    SoLdResource resource = (SoLdResource)layer.Resources[9];

    DescriptorStructure struct1 = (DescriptorStructure)resource.Items[15];
    ListStructure struct2 = (ListStructure)struct1.Structures[5];
    DescriptorStructure struct3 = (DescriptorStructure)struct2.Types[0];
    DescriptorStructure struct4 = (DescriptorStructure)struct3.Structures[6];
    ReferenceStructure struct5 = (ReferenceStructure)struct4.Structures[8];
    NameStructure nameStructure = (NameStructure)struct5.Items[0];

    AssertIsNotNull(nameStructure);
    AssertAreEqual(37, nameStructure.Length);
    AssertAreEqual("None\0", nameStructure.Value);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

void AssertIsNotNull(object actual)
{
    if (actual == null)
    {
        throw new Exception("Object is null.");
    }
}
```

### Voir aussi

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../)


