---
title: Class LclrResource
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LclrResource klass. Klass LclrResource. Denna resurs innehåller information om färgen på lagret i lagerlistan är PS. Det är bara
type: docs
weight: 2620
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---
## LclrResource class

Klass LclrResource. Denna resurs innehåller information om färgen på lagret i lagerlistan är PS. Det är bara

```csharp
public class LclrResource : LayerResource
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [LclrResource](lclrresource/#constructor)() | Initierar en ny instans av`LclrResource` class. |
| [LclrResource](lclrresource/#constructor_2)(byte[]) | Initierar en ny instans av`LclrResource` class. |
| [LclrResource](lclrresource/#constructor_1)(SheetColorHighlightEnum) | Initierar en ny instans av`LclrResource` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/) { get; set; } | Hämtar eller ställer in färgen på lagret. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/key/) { get; } | Hämtar lagerresursnyckeln. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/length/) { get; } | Hämtar lagerresurslängden i byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/psdversion/) { get; } | Hämtar psd-versionen. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/signature/) { get; } | Får signaturen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/save/)(StreamContainer, int) | Sparar resursen till den angivna strömbehållaren. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar enString som representerar denna instans. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/typetoolkey/) | Typverktygets infonyckel. |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* hopsättning [Aspose.PSD](../../)


