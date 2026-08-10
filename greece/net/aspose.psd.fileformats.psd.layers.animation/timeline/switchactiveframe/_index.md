---
title: "Timeline.SwitchActiveFrame"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος Timeline. Αλλάζει το ενεργό πλαίσιο στο στοχευμένο"
type: docs
weight: 80
url: /el/net/aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/
---
{{< psd/tize >}}
## Timeline.SwitchActiveFrame method

Αλλάζει το ενεργό πλαίσιο στο στοχευόμενο.

```csharp
public void SwitchActiveFrame(int targetActiveFrameIndex)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| targetActiveFrameIndex | Int32 | Ο δείκτης του στοχευμένου πλαισίου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IndexOutOfRangeException | Ο νέος δείκτης του ενεργού πλαισίου πρέπει να βρίσκεται εντός του εύρους του αριθμού πλαισίων. |

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


