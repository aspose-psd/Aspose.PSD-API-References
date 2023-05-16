---
title: ITextStyle.IsStandardVerticalRomanAlignmentEnabled
second_title: Aspose.PSD for .NET API Reference
description: ITextStyle property. Gets or sets the standard vertical Roman alignment. This based on BaselineDirection resource value applies only when text orientation is Vertical
type: docs
weight: 170
url: /net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
{{< psd/tize >}}
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

Gets or sets the standard vertical Roman alignment. This based on BaselineDirection resource value applies only when text orientation is Vertical.

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

## Examples

The following code demonstrates the support of the new IsStandardVerticalRomanAlignmentEnabled property.

```csharp
[C#]

// The following code demonstrates the ability to edit the new IsStandardVerticalRomanAlignmentEnabled property.
// This does not affect rendering at the moment, but only allows you to edit the property value.

string src = "1346test.psd";
string output = "out_1346test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // Correct reading
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
        // Correct reading
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }
}
```

### See Also

* interface [ITextStyle](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* assembly [Aspose.PSD](../../../)


