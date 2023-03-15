---
title: LclrResource.Color
second_title: Aspose.PSD för .NET API-referens
description: LclrResource fast egendom. Hämtar eller ställer in färgen på lagret.
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/
---
## LclrResource.Color property

Hämtar eller ställer in färgen på lagret.

```csharp
public SheetColorHighlightEnum Color { get; set; }
```

### Fastighetsvärde

Färgen.

### Exempel

Följande exempel visar hur du kan ändra arkfärgsmarkering i Aspose.PSD (arkfärgsinställning)

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// I filen är färgerna på lagers markering i denna ordning
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

// Layer Sheet Color används för att visuellt markera lager. 
// Du kan till exempel uppdatera några lager i PSD och sedan markera efter färg det lager som du vill väcka uppmärksamhet.
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // Färgerna ska vara omvända
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
            // Lcrl-resursen presenteras alltid i resurslistan för psd-filer.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // Baksidan av stilmallsfärgerna. Konfigurera lagerfärgmarkering.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### Se även

* enum [SheetColorHighlightEnum](../../sheetcolorhighlightenum/)
* class [LclrResource](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../lclrresource/)
* hopsättning [Aspose.PSD](../../../)


