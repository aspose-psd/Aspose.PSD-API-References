---
title: Class LayerState
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState class. The options of time line layer state
type: docs
weight: 1950
url: /net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
{{< psd/tize >}}
## LayerState class

The options of time line layer state.

```csharp
public sealed class LayerState
```

## Constructors

| Name | Description |
| --- | --- |
| [LayerState](layerstate/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | Gets or sets the blending mode. |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | Gets or sets the enabled state. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | Gets or sets the fill opacity value. |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | Gets or sets the HorizontalFXRf value. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | Gets or sets the layer id. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | Gets or sets the opacity value. |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | Gets or sets the layer position offset related to the actual layer position. |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | Gets the layer state effects. |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | Gets or sets the VerticalFXRf value. |

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


