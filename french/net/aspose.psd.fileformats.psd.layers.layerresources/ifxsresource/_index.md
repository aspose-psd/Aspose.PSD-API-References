---
title: "Classe IfxsResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.IfxsResource class. Ressource de groupe d'effets de calque Ifxs"
type: docs
weight: 2840
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/
---
{{< psd/tize >}}
## IfxsResource class

Ressource Ifxs (ressource d'effets de calque de groupe)

```csharp
public sealed class IfxsResource : BaseFxResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [IfxsResource](ifxsresource/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/descriptorversion/) { get; } | Obtient la version du descripteur. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/length/) { get; } | Obtient la longueur de la ressource du calque en octets. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/) | La clé d'information de l'outil de type. |

## Exemples

Le code suivant montre la prise en charge de IfxsResource.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "export.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    // L'exemple comporte 2 calques de groupe avec effets
    // Calque de groupe avec un effet
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // Calque de groupe avec plusieurs effets
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // Obtenez le nombre d'effets et vérifiez leur quantité
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // Un effet dans le calque de groupe se trouve dans la ressource 'IfxsResource'
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // Deux effets ou plus dans un calque de groupe se trouvent dans la ressource 'ImfxResource'
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // Ajoutez une troisième ombre à un calque de groupe avec plusieurs effets
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### Voir aussi

* class [BaseFxResource](../basefxresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


