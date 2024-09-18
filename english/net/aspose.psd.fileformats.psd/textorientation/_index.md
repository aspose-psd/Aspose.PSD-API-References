---
title: Enum TextOrientation
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.TextOrientation enum. Enumeration for text orientation mode
type: docs
weight: 4360
url: /net/aspose.psd.fileformats.psd/textorientation/
---
{{< psd/tize >}}
## TextOrientation enumeration

Enumeration for text orientation mode.

```csharp
public enum TextOrientation
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Horizontal | `0` | The horizontal text orientation. |
| Vertical | `2` | The vertical text orientation. |

## Examples

The following code demonstrates the ability to edit the new TextOrientation property. This does not affect rendering at the moment, but only allows you to edit the property value.

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // Correct reading
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }

    textLayer.TextData.TextOrientation = TextOrientation.Horizontal;
    textLayer.TextData.UpdateLayerData();

    image.Save(output);
}

using (var image = (PsdImage)Image.Load(output))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Horizontal)
    {
        // Correct reading
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### See Also

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


