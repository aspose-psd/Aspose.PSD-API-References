---
title: PsdImage.AddLayer
second_title: Aspose.PSD for .NET API Reference
description: PsdImage method. Adds the layer
type: docs
weight: 380
url: /net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
{{< psd/tize >}}
## PsdImage.AddLayer method

Adds the layer.

```csharp
public void AddLayer(Layer layer)
```

| Parameter | Type | Description |
| --- | --- | --- |
| layer | Layer | The layer. |

## Examples

The following example demonstrates how you can draw on a newly created layer if the simple constructor version is used in Aspose.PSD

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // draw a rectangle with Pen tool
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // draw another rectangle with Solid Brush in Blue color
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### See Also

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* assembly [Aspose.PSD](../../../)


