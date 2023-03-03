---
title: LclrResource.Color
second_title: Référence de l'API Aspose.PSD pour .NET
description: LclrResource propriété. Obtient ou définit la couleur du calque.
type: docs
weight: 20
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/
---
## LclrResource.Color property

Obtient ou définit la couleur du calque.

```csharp
public SheetColorHighlightEnum Color { get; set; }
```

### Valeur de la propriété

La couleur.

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

* enum [SheetColorHighlightEnum](../../sheetcolorhighlightenum/)
* class [LclrResource](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../lclrresource/)
* Assemblée [Aspose.PSD](../../../)


