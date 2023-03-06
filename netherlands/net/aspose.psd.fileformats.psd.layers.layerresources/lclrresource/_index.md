---
title: Class LclrResource
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LclrResource klas. Klasse LclrResource. Deze bron bevat informatie over de kleur van de laag in de lagenlijst is PS. Het is slechts
type: docs
weight: 2620
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---
## LclrResource class

Klasse LclrResource. Deze bron bevat informatie over de kleur van de laag in de lagenlijst is PS. Het is slechts

```csharp
public class LclrResource : LayerResource
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [LclrResource](lclrresource/#constructor)() | Initialiseert een nieuw exemplaar van het`LclrResource` klasse. |
| [LclrResource](lclrresource/#constructor_2)(byte[]) | Initialiseert een nieuw exemplaar van het`LclrResource` klasse. |
| [LclrResource](lclrresource/#constructor_1)(SheetColorHighlightEnum) | Initialiseert een nieuw exemplaar van het`LclrResource` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/) { get; set; } | Haalt of stelt de kleur van de laag in. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/key/) { get; } | Haalt de laagbronsleutel op. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/length/) { get; } | Haalt de resourcelengte van de laag op in bytes. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/psdversion/) { get; } | Krijgt de psd-versie. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/signature/) { get; } | Krijgt de handtekening. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/save/)(StreamContainer, int) | Slaat de bron op in de opgegeven streamcontainer. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Geeft als resultaat eenString die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/typetoolkey/) | De infotoets voor het typen van gereedschap. |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* montage [Aspose.PSD](../../)


