---
title: IText.TextOrientation
second_title: Aspose.PSD for .NET API Reference
description: IText property. Gets or sets the text orientation
type: docs
weight: 30
url: /net/aspose.psd.fileformats.psd.layers.text/itext/textorientation/
---
{{< psd/tize >}}
## IText.TextOrientation property

Gets or sets the text orientation.

```csharp
public TextOrientation TextOrientation { get; set; }
```

### Property Value

The text orientation.

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

* enum [TextOrientation](../../../aspose.psd.fileformats.psd/textorientation/)
* interface [IText](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* assembly [Aspose.PSD](../../../)


