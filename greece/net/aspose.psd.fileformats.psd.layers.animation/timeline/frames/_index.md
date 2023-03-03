---
title: TimeLine.Frames
second_title: Aspose.PSD για Αναφορά API .NET
description: TimeLine ιδιοκτησία. Λαμβάνει τη λίστα των πλαισίων.
type: docs
weight: 50
url: /el/net/aspose.psd.fileformats.psd.layers.animation/timeline/frames/
---
## TimeLine.Frames property

Λαμβάνει τη λίστα των πλαισίων.

```csharp
public Frame[] Frames { get; set; }
```

### Παραδείγματα

Η κλάση TimeLine παρέχει μια υψηλού επιπέδου ικανότητα χειρισμού της γραμμής χρόνου του PsdImage, όπως η αλλαγή της καθυστέρησης καρέ ή η επεξεργασία της κατάστασης του επιπέδου σε ένα συγκεκριμένο πλαίσιο.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // Αλλαγή της μεθόδου διάθεσης του πλαισίου 1
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Αλλαγή καθυστέρησης καρέ 2
    timeLine.Frames[1].Delay = 15;

    // Αλλαγή της αδιαφάνειας του 'Layer 1' στο πλαίσιο 2
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // μετακινήστε το 'Layer 1' στην κάτω αριστερή γωνία στο πλαίσιο 3
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // Προσθέτει νέο πλαίσιο
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // Αλλαγή blendMode του 'Layer 1' στο πλαίσιο 4
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Εφαρμογή αλλαγών πίσω στην παρουσία PsdImage
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### Δείτε επίσης

* class [Frame](../../frame/)
* class [TimeLine](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* συνέλευση [Aspose.PSD](../../../)


