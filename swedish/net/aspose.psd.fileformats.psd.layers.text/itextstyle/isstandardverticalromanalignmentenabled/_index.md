---
title: "ITextStyle.IsStandardVerticalRomanAlignmentEnabled"
second_title: "Aspose.PSD för .NET API‑referens"
description: "ITextStyle egenskap. Hämtar eller anger den standardvertikala romerska justeringen. Detta, baserat på BaselineDirection-resursvärdet, tillämpas endast när textorienteringen är vertikal"
type: docs
weight: 170
url: /sv/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
{{< psd/tize >}}
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

Hämtar eller anger den standardvertikala romerska justeringen. Detta, baserat på BaselineDirection-resursvärdet, gäller endast när textorienteringen är vertikal.

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

## Exempel

Följande kod demonstrerar stödet för den nya egenskapen IsStandardVerticalRomanAlignmentEnabled.

```csharp
[C#]

// Följande kod demonstrerar möjligheten att redigera den nya egenskapen IsStandardVerticalRomanAlignmentEnabled.
// Detta påverkar inte rendering för närvarande, utan tillåter bara att du redigerar egenskapsvärdet.

string src = "1346test.psd";
string output = "out_1346test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // Korrekt läsning
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }

    textPortion.Style.IsStandardVerticalRomanAlignmentEnabled = false;
    textLayer.TextData.UpdateLayerData();

    image.Save(output);
}

using (var image = (PsdImage)Image.Load(output))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (!textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // Korrekt läsning
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }
}
```

### Se även

* interface [ITextStyle](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


