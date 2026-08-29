---
title: "Enum LeadingType"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.LeadingType enum. Photoshop ledningstyp avstånd mellan rader"
type: docs
weight: 4030
url: /sv/net/aspose.psd.fileformats.psd/leadingtype/
---
{{< psd/tize >}}
## LeadingType enumeration

Photoshop radavståndstyp (typ av avstånd mellan rader).

```csharp
public enum LeadingType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| BottomToBottom | `0` | Den botten‑till‑botten ledningen. |
| TopToTop | `1` | Den topp‑till‑topp ledningen. |

## Exempel

Följande kod demonstrerar stöd för botten‑till‑botten och topp‑till‑topp ledningslägen från styckeinställningarna.

```csharp
[C#]

string input = "leadingMode.psd";
string output = "output_leadingMode.png";

using (var psdImage = (PsdImage)Image.Load(input, new PsdLoadOptions()))
{
    IText text1 = ((TextLayer)psdImage.Layers[1]).TextData;
    foreach (var textPortion in text1.Items)
    {
        textPortion.Paragraph.LeadingType = LeadingType.TopToTop; // Change LeadingType value   
    }
    text1.Items[8].Text = "TopToTop";
    text1.Items[8].Style.FillColor = Color.ForestGreen;
    text1.UpdateLayerData();

    IText text2 = ((TextLayer)psdImage.Layers[2]).TextData;
    foreach (var textPortion in text2.Items)
    {
        textPortion.Paragraph.LeadingType = LeadingType.BottomToBottom; // Change LeadingType value   
    }
    text2.Items[8].Text = "BottomToBottom";
    text2.Items[8].Style.FillColor = Color.ForestGreen;
    text2.UpdateLayerData();

    psdImage.Save(output, new PngOptions());
}
```

### Se även

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


