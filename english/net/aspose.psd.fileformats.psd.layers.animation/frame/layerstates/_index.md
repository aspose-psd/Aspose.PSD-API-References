---
title: Frame.LayerStates
second_title: Aspose.PSD for .NET API Reference
description: Frame property. Gets ot sets the layer states of frame
type: docs
weight: 50
url: /net/aspose.psd.fileformats.psd.layers.animation/frame/layerstates/
---
{{< psd/tize >}}
## Frame.LayerStates property

Gets ot sets the layer states of frame.

```csharp
public Dictionary<int, LayerState> LayerStates { get; }
```

## Examples

The TimeLine class gives a high-level ability to manipulate the timeline of PsdImage, like changing frame delay or editing layer state on a specific frame.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // Change dispose method of frame 1
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Change delay of frame 2
    timeLine.Frames[1].Delay = 15;

    // Change opacity of 'Layer 1' on frame 2
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // move 'Layer 1' to left-bottom corner on frame 3
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // Adds new frame
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // Change blendMode of 'Layer 1' on frame 4
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Apply changes back to PsdImage instance
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### See Also

* class [LayerState](../../layerstate/)
* class [Frame](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../frame/)
* assembly [Aspose.PSD](../../../)


