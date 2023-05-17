---
title: Enum JustificationMode
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.JustificationMode enum. The text alignment mode
type: docs
weight: 1670
url: /net/aspose.psd.fileformats.psd/justificationmode/
---
{{< psd/tize >}}
## JustificationMode enumeration

The text alignment mode.

```csharp
public enum JustificationMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Left | `0` | The left align text. |
| Right | `1` | The right align text. |
| Center | `2` | The center text. |

## Examples

The following code demonstrates support of JustificationMode enum to set the text alignment for text portions.

```csharp
[C#]

string src = "source1107.psd";
string outputPsd = "output.psd";
string outputPng = "output.png";

using (var image = (PsdImage) Image.Load(src))
{
    var txtLayer = image.AddTextLayer("Text line1\rText line2\rText line3",
        new Rectangle(200, 200, 500, 500));
    var portions = txtLayer.TextData.Items;

    portions[0].Paragraph.Justification = JustificationMode.Left;
    portions[1].Paragraph.Justification = JustificationMode.Right;
    portions[2].Paragraph.Justification = JustificationMode.Center;

    foreach (var portion in portions)
    {
        portion.Style.FontSize = 24;
    }

    txtLayer.TextData.UpdateLayerData();

    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### See Also

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


