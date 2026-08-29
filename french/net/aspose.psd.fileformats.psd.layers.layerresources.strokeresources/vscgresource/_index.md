---
title: "Classe VscgResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.VscgResource classe. Ressource de données de contenu de contour vectoriel"
type: docs
weight: 3430
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/
---
{{< psd/tize >}}
## VscgResource class

Ressource de données de contenu de contour vectoriel.

```csharp
public class VscgResource : LayerResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [VscgResource](vscgresource/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/items/) { get; } | Obtient ou définit le tableau des éléments de structure. **Warning:** Les valeurs du tableau `Items` doivent correspondre à la propriété `KeyForData`, qui détermine le type de paramètres de remplissage stockés dans les structures du tableau `Items`. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| [KeyForData](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/keyfordata/) { get; } | Obtient la clé entière qui définit le type de paramètres de remplissage stockés dans la ressource : * Color - 0x536f436f - SoCoResource.TypeToolKey * Gradient - 0x4764466c - GdFlResource.TypeToolKey * Pattern - 0x5074466c - PtFlResource.TypeToolKey Attention ! La valeur de la propriété KeyForData doit correspondre au type des paramètres de remplissage stockés dans les structures Items. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/length/) { get; } | Obtient la longueur de la ressource du calque en octets. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/typetoolkey/) | La clé d'information de l'outil de type. |

## Exemples

Le code suivant démontre la prise en charge de VscgResource.

```csharp
[C#]

string sourceFile = "StrokeInternalFill_src.psd";
string outputFile = "StrokeInternalFill_res.psd";

void AreEqual(double expected, double current, double tolerance = 0.1)
{
    if (Math.Abs(expected - current) > tolerance)
    {
        throw new Exception(
            $"Values is not equal.\nExpected:{expected}\nResult:{current}\nDifference:{expected - current}");
    }
}

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    VscgResource vscgResource = (VscgResource)image.Layers[1].Resources[0];
    DescriptorStructure rgbColorStructure = (DescriptorStructure)vscgResource.Items[0];

    AreEqual(89.8, ((DoubleStructure)rgbColorStructure.Structures[0]).Value);
    AreEqual(219.6, ((DoubleStructure)rgbColorStructure.Structures[1]).Value);
    AreEqual(34.2, ((DoubleStructure)rgbColorStructure.Structures[2]).Value);

    ((DoubleStructure)rgbColorStructure.Structures[0]).Value = 255d; // Red
    ((DoubleStructure)rgbColorStructure.Structures[1]).Value = 0d; // Green
    ((DoubleStructure)rgbColorStructure.Structures[2]).Value = 0d; // Blue

    image.Save(outputFile);
}

// vérification des modifications
using (PsdImage image = (PsdImage)Image.Load(outputFile))
{
    VscgResource vscgResource = (VscgResource)image.Layers[1].Resources[0];
    DescriptorStructure rgbColorStructure = (DescriptorStructure)vscgResource.Items[0];

    AreEqual(255, ((DoubleStructure)rgbColorStructure.Structures[0]).Value);
    AreEqual(0, ((DoubleStructure)rgbColorStructure.Structures[1]).Value);
    AreEqual(0, ((DoubleStructure)rgbColorStructure.Structures[2]).Value);
}
```

### Voir aussi

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


