---
title: Enum LeadingType
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.LeadingType enum. Photoshop leading type type of distance between lines
type: docs
weight: 3910
url: /net/aspose.psd.fileformats.psd/leadingtype/
---
{{< psd/tize >}}
## LeadingType enumeration

Photoshop leading type (type of distance between lines).

```csharp
public enum LeadingType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| BottomToBottom | `0` | The bottom-to-bottom leading. |
| TopToTop | `1` | The top-to-top leading. |

## Examples

The following code demonstrates the support of Bottom-to-bottom and Top-to-Top leading modes from Paragraph settings.

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

### See Also

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


