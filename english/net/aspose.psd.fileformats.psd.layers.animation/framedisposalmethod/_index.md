---
title: Enum FrameDisposalMethod
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod enum. The frame disposal method specifies whether to discard the current frame before displaying the next frame. You select a disposal method for animations that include background transparency to specify whether the current frame will be visible through the transparent areas of the next frame
type: docs
weight: 1930
url: /net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
{{< psd/tize >}}
## FrameDisposalMethod enumeration

The frame disposal method specifies whether to discard the current frame before displaying the next frame. You select a disposal method for animations that include background transparency to specify whether the current frame will be visible through the transparent areas of the next frame.

```csharp
public enum FrameDisposalMethod
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Automatic | `0` | Determines a disposal method for the current frame automatically, discarding the current frame if the next frame contains layer transparency. For most animations, the Automatic option (default) yields the desired results. |
| DoNotDispose | `1` | Preserves the current frame as the next frame is added to the display. The current frame (and preceding frames) may show through transparent areas of the next frame. |
| Dispose | `2` | Discards the current frame from the display before the next frame is displayed. Only a single frame is displayed at any time (and the current frame does not appear through the transparent areas of the next frame). |

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


