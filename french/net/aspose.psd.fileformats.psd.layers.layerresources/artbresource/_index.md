---
title: "Classe ArtBResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.ArtBResource classe. Les données d'information du plan de travail pour les Resources"
type: docs
weight: 2520
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/
---
{{< psd/tize >}}
## ArtBResource class

Les données d'information du Artboard pour [`Resources`](../../aspose.psd.fileformats.psd.layers/layer/resources/).

```csharp
public sealed class ArtBResource : BaseArtboardInfoResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ArtBResource](artbresource/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ArtboardBackgroundType](../../aspose.psd.fileformats.psd.layers.layerresources/artbresource/artboardbackgroundtype/) { get; set; } | Obtient ou définit le [`ArtboardBackgroundType`](./artboardbackgroundtype/) |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/artbresource/color/) { get; set; } | Obtient ou définit le [`Color`](./color/) |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/items/) { get; set; } | Obtient ou définit les éléments [`OSTypeStructure`](../ostypestructure/). |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/length/) { get; } |  |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/artbresource/typetoolkey/) | La clé d'information de l'outil de type. |

## Exemples

Le code suivant démontre la prise en charge des ressources de plan de travail.

```csharp
[C#]

string srcFile = "artboard1.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(srcFile))
{
    ArtDResource artDResource = (ArtDResource)psdImage.GlobalLayerResources[2];

    ArtBResource artBResource1 = (ArtBResource)psdImage.Layers[2].Resources[7];
    ArtBResource artBResource2 = (ArtBResource)psdImage.Layers[5].Resources[7];

    LyvrResource lyvrResource1 = (LyvrResource)psdImage.Layers[2].Resources[9];
    LyvrResource lyvrResource2 = (LyvrResource)psdImage.Layers[5].Resources[9];

    var countStruct = (IntegerStructure)artDResource.Items[0];
    AssertAreEqual(2, countStruct.Value);

    var presetNameStruct1 = (StringStructure)artBResource1.Items[2];
    AssertAreEqual("iPhone X\0", presetNameStruct1.Value);

    var presetNameStruct2 = (StringStructure)artBResource2.Items[2];
    AssertAreEqual("iPhone X\0", presetNameStruct2.Value);

    AssertAreEqual(160, lyvrResource1.Version);
    AssertAreEqual(160, lyvrResource2.Version);
}

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}
```

### Voir aussi

* class [BaseArtboardInfoResource](../baseartboardinforesource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


