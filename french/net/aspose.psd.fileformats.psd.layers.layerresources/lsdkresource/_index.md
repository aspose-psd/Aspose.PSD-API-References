---
title: "Classe LsdkResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LsdkResource class. La ressource de couche lsdk, ressource de section de couche imbriquée"
type: docs
weight: 3110
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/lsdkresource/
---
{{< psd/tize >}}
## LsdkResource class

La ressource de calque lsdk (ressource de section de calque imbriquée).

```csharp
public class LsdkResource : BaseLayerSectionResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [LsdkResource](lsdkresource/)() | Initialise une nouvelle instance de la classe `LsdkResource`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BlendModeKey](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/blendmodekey/) { get; set; } | Obtient ou définit la clé du mode de fusion. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/length/) { get; } | Obtient la longueur de la ressource du calque en octets. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| [SectionType](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/sectiontype/) { get; set; } | Obtient ou définit le type de section. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |
| [Subtype](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/subtype/) { get; set; } | Obtient ou définit le sous-type. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lsdkresource/typetoolkey/) | La clé d'information de l'outil de type. |

## Exemples

Le code suivant montre la prise en charge de LsdkResource.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

string srcFile = "123 1.psd";
string outFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    AssertAreEqual((psdImage.Layers[8].Resources[3] as LsdkResource).Length, 4);
    psdImage.Save(outFile);
}

// vérifier après l'enregistrement
using (var psdImage = (PsdImage)Image.Load(outFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    AssertAreEqual((psdImage.Layers[8].Resources[3] as LsdkResource).Length, 4);
}
```

### Voir aussi

* class [BaseLayerSectionResource](../baselayersectionresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


