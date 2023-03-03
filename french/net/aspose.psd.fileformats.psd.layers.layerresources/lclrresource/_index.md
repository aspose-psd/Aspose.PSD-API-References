---
title: Class LclrResource
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LclrResource classe. Classe LclrResource. Cette ressource contient des informations sur la couleur du calque dans la liste des calques est PS. Cest seulement
type: docs
weight: 2620
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---
## LclrResource class

Classe LclrResource. Cette ressource contient des informations sur la couleur du calque dans la liste des calques est PS. C'est seulement

```csharp
public class LclrResource : LayerResource
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [LclrResource](lclrresource/#constructor)() | Initialise une nouvelle instance du`LclrResource` classe. |
| [LclrResource](lclrresource/#constructor_2)(byte[]) | Initialise une nouvelle instance du`LclrResource` classe. |
| [LclrResource](lclrresource/#constructor_1)(SheetColorHighlightEnum) | Initialise une nouvelle instance du`LclrResource` classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/) { get; set; } | Obtient ou définit la couleur du calque. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/key/) { get; } | Obtient la clé de ressource de couche. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/length/) { get; } | Obtient la longueur de la ressource de couche en octets. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/psdversion/) { get; } | Obtient la version psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/signature/) { get; } | Obtient la signature. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie unString qui représente cette instance. |

## Des champs

| Nom | La description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/typetoolkey/) | La clé d'informations sur l'outil de type. |

### Exemples

L'exemple suivant montre comment vous pouvez modifier la surbrillance de la couleur de feuille dans Aspose.PSD (paramètre de couleur de feuille)

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// Dans le fichier, les couleurs de surbrillance des calques sont dans cet ordre
SheetColorHighlightEnum[] sheetColorsArr = new SheetColorHighlightEnum[] {
    SheetColorHighlightEnum.Red,
    SheetColorHighlightEnum.Orange,
    SheetColorHighlightEnum.Yellow,
    SheetColorHighlightEnum.Green,
    SheetColorHighlightEnum.Blue,
    SheetColorHighlightEnum.Violet,
    SheetColorHighlightEnum.Gray,
    SheetColorHighlightEnum.NoColor
};

// La couleur de la feuille de calque est utilisée pour mettre en surbrillance visuellement les calques. 
// Par exemple, vous pouvez mettre à jour certains calques dans PSD, puis mettre en surbrillance par couleur le calque sur lequel vous souhaitez attirer l'attention.
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // Les couleurs doivent être inversées
    Array.Reverse(sheetColorsArr);
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
}

void CheckSheetColorsAndRerverse(SheetColorHighlightEnum[] sheetColors, PsdImage img)
{
    int layersCount = img.Layers.Length;
    for (int layerIndex = 0; layerIndex < layersCount; layerIndex++)
    {
        Layer layer = img.Layers[layerIndex];
        LayerResource[] resources = layer.Resources;
        foreach (LayerResource layerResource in resources)
        {
            // La ressource lcrl est toujours présente dans la liste des ressources du fichier psd.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // Inverser les couleurs de la feuille de style. Configuration de la surbrillance de la couleur du calque.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### Voir également

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Assemblée [Aspose.PSD](../../)


