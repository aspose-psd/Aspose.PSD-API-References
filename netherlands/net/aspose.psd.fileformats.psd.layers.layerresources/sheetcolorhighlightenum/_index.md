---
title: Enum SheetColorHighlightEnum
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SheetColorHighlightEnum opsomming. Mogelijke kleuren van bladkleurinstelling. Het is UI decoratieve kleur van laag in lagenlijst in PS
type: docs
weight: 2970
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/
---
## SheetColorHighlightEnum enumeration

Mogelijke kleuren van bladkleurinstelling. Het is UI decoratieve kleur van laag in lagenlijst in PS

```csharp
public enum SheetColorHighlightEnum : short
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| NoColor | `0` | Kleur is niet gespecificeerd. |
| Red | `1` | De rode kleur. |
| Orange | `2` | De oranje kleur. |
| Yellow | `3` | De gele kleur. |
| Green | `4` | De groene kleur. |
| Blue | `5` | De blauwe kleur. |
| Violet | `6` | De violette kleur. |
| Gray | `7` | De grijze kleur. |

### Voorbeelden

Het volgende voorbeeld laat zien hoe u Sheet Color Highlight In Aspose.PSD (Sheet colour setting) kunt wijzigen

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// In het bestand zijn de kleuren van de markering van lagen in deze volgorde
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

// Layer Sheet Color wordt gebruikt om lagen visueel te markeren. 
// U kunt bijvoorbeeld enkele lagen in PSD bijwerken en vervolgens met kleur de laag markeren die u de aandacht wilt trekken.
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // Kleuren moeten worden omgekeerd
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
            // De lcrl-resource wordt altijd weergegeven in de psd-bestandsresourcelijst.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // Omgekeerde stijlbladkleuren. Instelling van laagkleurmarkering.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### Zie ook

* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* montage [Aspose.PSD](../../)


