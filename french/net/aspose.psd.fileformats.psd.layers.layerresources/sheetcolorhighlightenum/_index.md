---
title: Enum SheetColorHighlightEnum
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SheetColorHighlightEnum énumération. Couleurs possibles du paramètre de couleur de feuille. Cest la couleur décorative de linterface utilisateur du calque dans la liste des calques dans PS
type: docs
weight: 2970
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/
---
## SheetColorHighlightEnum enumeration

Couleurs possibles du paramètre de couleur de feuille. C'est la couleur décorative de l'interface utilisateur du calque dans la liste des calques dans PS

```csharp
public enum SheetColorHighlightEnum : short
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| NoColor | `0` | La couleur n'est pas spécifiée. |
| Red | `1` | La couleur rouge. |
| Orange | `2` | La couleur orange. |
| Yellow | `3` | La couleur jaune. |
| Green | `4` | La couleur verte. |
| Blue | `5` | La couleur bleue. |
| Violet | `6` | La couleur violette. |
| Gray | `7` | La couleur grise. |

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

* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Assemblée [Aspose.PSD](../../)


