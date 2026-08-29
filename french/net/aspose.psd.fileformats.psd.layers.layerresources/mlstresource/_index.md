---
title: "Classe MlstResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MlstResource. La ressource mlst. Cette classe, entre autres, contient des informations sur la position du calque sur la chronologie"
type: docs
weight: 3170
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/
---
{{< psd/tize >}}
## MlstResource class

La ressource mlst. Cette classe, entre autres, contient des informations sur la position du calque sur la chronologie.

```csharp
public class MlstResource : LayerResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MlstResource](mlstresource/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/descriptorversion/) { get; } | Obtient ou définit la version du descripteur. |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/) { get; } | Obtient ou définit les structures. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/length/) { get; } | Obtient la longueur de la ressource du calque en octets. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/save/)(StreamContainer, int) | Enregistre le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/typetoolkey/) | La clé d'information de l'outil de type. |

## Exemples

Le code suivant montre la prise en charge de la ressource MlstResource qui fournit un mécanisme de bas niveau pour manipuler les états du calque.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image1219.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    Layer layer1 = image.Layers[1];
    ShmdResource shmdResource = (ShmdResource)layer1.Resources[8];
    MlstResource mlstResource = (MlstResource)shmdResource.SubResources[0];

    ListStructure layerStatesList = (ListStructure)mlstResource.Items[1];
    DescriptorStructure layersStateOnFrame1 = (DescriptorStructure)layerStatesList.Types[1];
    BooleanStructure layerEnabled = (BooleanStructure)layersStateOnFrame1.Structures[0];

    // Désactiver le calque 1 sur la trame 1
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### Voir aussi

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


