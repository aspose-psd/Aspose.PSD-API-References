---
title: PsdImage.Timeline
second_title: Aspose.PSD for .NET API Reference
description: PsdImage property. Gets the Timeline of this PsdImage
type: docs
weight: 250
url: /net/aspose.psd.fileformats.psd/psdimage/timeline/
---
{{< psd/tize >}}
## PsdImage.Timeline property

Gets the `Timeline` of this [`PsdImage`](../).

```csharp
public Timeline Timeline { get; }
```

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

* class [Timeline](../../../aspose.psd.fileformats.psd.layers.animation/timeline/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


