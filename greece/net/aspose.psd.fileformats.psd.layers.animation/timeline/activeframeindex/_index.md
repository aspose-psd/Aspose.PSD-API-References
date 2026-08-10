---
title: "Timeline.ActiveFrameIndex"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Timeline property. Παίρνει τον δείκτη του ενεργού καρέ"
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/
---
{{< psd/tize >}}
## Timeline.ActiveFrameIndex property

Λαμβάνει τον δείκτη του ενεργού πλαισίου.

```csharp
public int ActiveFrameIndex { get; }
```

## Παραδείγματα

Ο παρακάτω κώδικας παρουσιάζει μια νέα προσέγγιση για εργασία με το Timeline.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output_edited.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;
    
    // Προσθέστε ένα ακόμη καρέ
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    timeline.SwitchActiveFrame(4);

    psdImage.Save(outputFile);
}
```

### Δείτε επίσης

* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


