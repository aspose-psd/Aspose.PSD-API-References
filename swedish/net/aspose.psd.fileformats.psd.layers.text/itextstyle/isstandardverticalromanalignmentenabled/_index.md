---
title: ITextStyle.IsStandardVerticalRomanAlignmentEnabled
second_title: Aspose.PSD för .NET API-referens
description: ITextStyle fast egendom. Hämtar eller ställer in standard vertikal romersk justering. Detta baserat på BaselineDirection resursvärde gäller endast när textorienteringen ärVertical .
type: docs
weight: 170
url: /sv/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

Hämtar eller ställer in standard vertikal romersk justering. Detta baserat på BaselineDirection resursvärde gäller endast när textorienteringen ärVertical .

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

### Exempel

Följande kod visar stödet för den nya egenskapen IsStandardVerticalRomanAlignmentEnabled.

```csharp
[C#]

// Följande kod visar möjligheten att redigera den nya egenskapen IsStandardVerticalRomanAlignmentEnabled.
// Detta påverkar inte renderingen för tillfället, utan låter dig bara redigera egenskapsvärdet.

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
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* hopsättning [Aspose.PSD](../../../)


