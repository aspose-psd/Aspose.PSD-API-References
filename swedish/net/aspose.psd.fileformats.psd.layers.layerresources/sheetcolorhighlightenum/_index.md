---
title: "Enum SheetColorHighlightEnum"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SheetColorHighlightEnum enum. Möjliga färger för Sheet-färginställning. Dess UI-dekorativa färg för lager i lagerlistan i PS"
type: docs
weight: 3320
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/
---
{{< psd/tize >}}
## SheetColorHighlightEnum enumeration

Möjliga färger för Sheet‑färginställningen. Det är ett UI‑dekorativt färg för lager i lagerlistan i PS.

```csharp
public enum SheetColorHighlightEnum : short
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| NoColor | `0` | Färgen är inte specificerad. |
| Red | `1` | Den röda färgen. |
| Orange | `2` | Den orangea färgen. |
| Yellow | `3` | Den gula färgen. |
| Green | `4` | Den gröna färgen. |
| Blue | `5` | Den blå färgen. |
| Violet | `6` | Den violetta färgen. |
| Gray | `7` | Den grå färgen. |

## Exempel

Följande exempel visar hur du kan ändra bladfärgsmarkering i Aspose.PSD (inställning för bladfärg)

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// I filen är färgerna för lagrens markering i följande ordning
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

// Lagrets bladfärg används för att visuellt markera lager.
// Till exempel kan du uppdatera vissa lager i PSD och sedan markera med färg det lager du vill uppmärksamma.
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // Färgerna bör vändas
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
            // lcrl-resursen finns alltid i PSD-filens resurslista.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // Omvändning av stilarksfärger. Inställning av lagerfärgsmarkering.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### Se även

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


