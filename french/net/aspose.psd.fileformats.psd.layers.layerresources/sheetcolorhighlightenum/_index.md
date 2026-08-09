---
title: "Énumération SheetColorHighlightEnum"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Énumération Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SheetColorHighlightEnum. Couleurs possibles du réglage de couleur de feuille. Sa couleur décorative UI du calque dans la liste des calques dans PS."
type: docs
weight: 3320
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/
---
{{< psd/tize >}}
## SheetColorHighlightEnum enumeration

Couleurs possibles du paramètre de couleur de la feuille. C'est la couleur décorative de l'interface utilisateur du calque dans la liste des calques dans PS.

```csharp
public enum SheetColorHighlightEnum : short
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| NoColor | `0` | La couleur n'est pas spécifiée. |
| Red | `1` | La couleur rouge. |
| Orange | `2` | La couleur orange. |
| Yellow | `3` | La couleur jaune. |
| Green | `4` | La couleur verte. |
| Blue | `5` | La couleur bleue. |
| Violet | `6` | La couleur violette. |
| Gray | `7` | La couleur grise. |

## Exemples

L'exemple suivant montre comment vous pouvez modifier la mise en évidence de la couleur de feuille dans Aspose.PSD (réglage de couleur de feuille).

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// Dans le fichier, les couleurs de mise en évidence des calques sont dans cet ordre
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

// La couleur de feuille du calque est utilisée pour mettre visuellement en évidence les calques.
// Par exemple, vous pouvez mettre à jour certains calques dans le PSD, puis mettre en évidence par couleur le calque que vous souhaitez attirer l'attention.
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
            // La ressource lcrl est toujours présente dans la liste des ressources du fichier PSD.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // Inversion des couleurs de la feuille de style. Configuration de la mise en évidence de la couleur du calque.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### Voir aussi

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


