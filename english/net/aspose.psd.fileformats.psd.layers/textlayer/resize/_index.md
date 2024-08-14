---
title: TextLayer.Resize
second_title: Aspose.PSD for .NET API Reference
description: TextLayer method. Resizes the image. The default LeftTopToLeftTop is used
type: docs
weight: 100
url: /net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
{{< psd/tize >}}
## TextLayer.Resize method

Resizes the image. The default LeftTopToLeftTop is used.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | The new width. |
| newHeight | Int32 | The new height. |
| resizeType | ResizeType | The type of resize transformation [`ResizeType`](../../../aspose.psd/resizetype/) |

## Examples

The following code demonstrates the TextLayer.Resize function with the parameter to choose the mechanism of resizing.

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // It sets new size of text layer
    const int NewWidth = 250;
    const int NewHeight = 250;

    // It sets the mechanism for how the resize function will resize the layer (default value)
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // New mechanism of resizing for text layer using here
    // Not only the layer but also the transformation matrix of text layer will be changed
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // Reason of delta is different default font
    if (txtLayer.TransformMatrix[4] >= 65 
        && txtLayer.TransformMatrix[4] <= 67
        && txtLayer.TransformMatrix[5] >= 234
        && txtLayer.TransformMatrix[5] <= 237)
    {
        // All is OK
    }
    else
    {
        throw new Exception("Location point is wrong");
    }
}
```

### See Also

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


