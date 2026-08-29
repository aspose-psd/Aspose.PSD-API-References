---
title: "PsdImage.Timeline"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα PsdImage. Επιστρέφει το Timeline αυτού του PsdImage"
type: docs
weight: 250
url: /el/net/aspose.psd.fileformats.psd/psdimage/timeline/
---
{{< psd/tize >}}
## PsdImage.Timeline property

Επιστρέφει το `Timeline` αυτού του [`PsdImage`](../).

```csharp
public Timeline Timeline { get; }
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

* class [Timeline](../../../aspose.psd.fileformats.psd.layers.animation/timeline/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


