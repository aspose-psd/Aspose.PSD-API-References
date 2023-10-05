---
title: Class Frame
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.Frame class. The options of time line frame item
type: docs
weight: 1920
url: /net/aspose.psd.fileformats.psd.layers.animation/frame/
---
{{< psd/tize >}}
## Frame class

The options of time line frame item.

```csharp
public sealed class Frame
```

## Constructors

| Name | Description |
| --- | --- |
| [Frame](frame/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Delay](../../aspose.psd.fileformats.psd.layers.animation/frame/delay/) { get; set; } | Gets or sets the frame delay value in centa-seconds. For example, in 1 second contains 100 centa-seconds. |
| [DisposalMethod](../../aspose.psd.fileformats.psd.layers.animation/frame/disposalmethod/) { get; set; } | Gets or sets the disposal method of frame. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/frame/id/) { get; set; } | Gets or sets the frame id. |
| [LayerStates](../../aspose.psd.fileformats.psd.layers.animation/frame/layerstates/) { get; set; } | Gets ot sets the layer states of frame. |

## Examples

The Timeline class gives a high-level ability to manipulate the timeline of PsdImage, like changing frame delay or editing layer state on a specific frame.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    // Change dispose method of frame 1
    timeline.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Change delay of frame 2
    timeline.Frames[1].Delay = 15;

    // Change opacity of 'Layer 1' on frame 2
    LayerState layerState11 = timeline.Frames[1].LayerStates[1];
    layerState11.Opacity = 50;

    // move 'Layer 1' to left-bottom corner on frame 3
    LayerState layerState21 = timeline.Frames[2].LayerStates[1];
    layerState21.PositionOffset = new Point(-50, 230);

    // Adds new frame
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    // Change blendMode of 'Layer 1' on frame 4
    LayerState layerState31 = timeline.Frames[3].LayerStates[1];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Apply changes back to PsdImage instance
    psdImage.Save(outputPsd);
}
```

### See Also

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../)


