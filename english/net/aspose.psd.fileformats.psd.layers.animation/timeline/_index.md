---
title: Class Timeline
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.Timeline class. The time line options model
type: docs
weight: 1950
url: /net/aspose.psd.fileformats.psd.layers.animation/timeline/
---
{{< psd/tize >}}
## Timeline class

The time line options model.

```csharp
public sealed class Timeline
```

## Constructors

| Name | Description |
| --- | --- |
| [Timeline](timeline/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ActiveFrameIndex](../../aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/) { get; } | Gets the active frame index. |
| [AFSt](../../aspose.psd.fileformats.psd.layers.animation/timeline/afst/) { get; set; } | Gets or sets the AFSt value. |
| [Frames](../../aspose.psd.fileformats.psd.layers.animation/timeline/frames/) { get; set; } | Gets the list of frames. |
| [FsID](../../aspose.psd.fileformats.psd.layers.animation/timeline/fsid/) { get; set; } | Gets or sets the FsID value. |
| [LoopesCount](../../aspose.psd.fileformats.psd.layers.animation/timeline/loopescount/) { get; set; } | Gets or sets the count of loops. |

## Methods

| Name | Description |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd.layers.animation/timeline/save/#save)(Stream, ImageOptionsBase) | Saves the PsdImage's and Timeline data to the specified stream in the specified format according to save options. |
| [Save](../../aspose.psd.fileformats.psd.layers.animation/timeline/save/#save_1)(string, ImageOptionsBase) | Saves the PsdImage's and Timeline data to the specified file location in the specified format according to save options. |
| [SwitchActiveFrame](../../aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/)(int) | Switches the active frame to targeted. |

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


