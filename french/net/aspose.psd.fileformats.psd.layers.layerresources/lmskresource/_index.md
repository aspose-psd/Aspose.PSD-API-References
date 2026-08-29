---
title: "Classe LmskResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LmskResource class. La ressource LMsk"
type: docs
weight: 3020
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---
{{< psd/tize >}}
## LmskResource class

La ressource LMsk.

```csharp
public class LmskResource : LayerResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [LmskResource](lmskresource/)() | Initialise une nouvelle instance de la classe `LmskResource`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ColorComponent1](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent1/) { get; set; } | Obtient le composant couleur 1. |
| [ColorComponent2](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent2/) { get; set; } | Obtient le composant couleur 2. |
| [ColorComponent3](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent3/) { get; set; } | Obtient le composant couleur 3. |
| [ColorComponent4](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent4/) { get; set; } | Obtient le composant couleur 4. |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorspace/) { get; set; } | Obtient l'espace colorimétrique. |
| [Flag](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/flag/) { get; } | Obtient le drapeau. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/length/) { get; } | Obtient la longueur de la ressource du calque en octets. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/opacity/) { get; set; } | Obtient l'opacité. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/typetoolkey/) | La clé d'information de l'outil de type. |

## Remarques

Cette ressource contient l'ID d'espace colorimétrique, qui fait référence à un type d'espace colorimétrique spécifique, ainsi que 4 composants couleur. Selon l'ID, les composants couleur ont des significations différentes. Si le type d'espace colorimétrique ne nécessite pas quatre valeurs, les composants supplémentaires sont indéfinis et toujours écrits comme des zéros. Composants couleur selon les types d'espace colorimétrique : RGB – les trois premiers composants sont rouge, vert et bleu. HSB – les trois premiers composants sont teinte, saturation et luminosité. CMYK – les quatre composants sont cyan, magenta, jaune et noir. Lab – les trois premiers composants sont clarté, chrominance a et chrominance b. Niveaux de gris – le premier composant est la valeur de gris, de 0…10000.

## Exemples

Le code suivant montre comment modifier les options d'affichage du masque de calque sur des images 16 bits en modifiant les propriétés LmskResource.

```csharp
[C#]

string sourceFile = "sourceFile.psd";
string outputPsd = "sourceFile_output.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// Charger l'image 16 bits.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // Trouver LmskResource.
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // Vérifier les propriétés de LmskResource.
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // Modifier les propriétés de LmskResource.
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // Enregistrer l'image.
    image.Save(outputPsd);
}
```

### Voir aussi

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


