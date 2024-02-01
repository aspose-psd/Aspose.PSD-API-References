---
title: Timeline.SwitchActiveFrame
second_title: Aspose.PSD for .NET API Reference
description: Timeline method. Switches the active frame to targeted
type: docs
weight: 80
url: /net/aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/
---
{{< psd/tize >}}
## Timeline.SwitchActiveFrame method

Switches the active frame to targeted.

```csharp
public void SwitchActiveFrame(int targetActiveFrameIndex)
```

| Parameter | Type | Description |
| --- | --- | --- |
| targetActiveFrameIndex | Int32 | The target frame index. |

### Exceptions

| exception | condition |
| --- | --- |
| IndexOutOfRangeException | The new index of the active frame should be in the frame count range. |

## Examples

The following code demonstrates a new approach to work with the Timeline.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output_edited.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;
    
    // Add one more frame
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    timeline.SwitchActiveFrame(4);

    psdImage.Save(outputFile);
}
```

### See Also

* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


