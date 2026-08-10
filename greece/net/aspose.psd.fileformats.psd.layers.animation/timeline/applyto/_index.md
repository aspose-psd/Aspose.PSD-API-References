---
title: "TimeLine.ApplyTo"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "TimeLine method. Εφαρμόζει τις τρέχουσες τιμές της χρονογραμμής στο εισερχόμενο PsdImage"
type: docs
weight: 90
url: /el/net/aspose.psd.fileformats.psd.layers.animation/timeline/applyto/
---
{{< psd/tize >}}
## TimeLine.ApplyTo method

Εφαρμόζει τις τρέχουσες τιμές της χρονογραμμής στο εισερχόμενο [`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/).

```csharp
public void ApplyTo(PsdImage psdImage)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| psdImage | PsdImage | Η εικόνα psd. |

## Παραδείγματα

Η κλάση TimeLine παρέχει μια υψηλού επιπέδου δυνατότητα για τη διαχείριση της χρονογραμμής του PsdImage, όπως η αλλαγή της καθυστέρησης του καρέ ή η επεξεργασία της κατάστασης του επιπέδου σε ένα συγκεκριμένο καρέ.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // Αλλαγή μεθόδου αποδέσμευσης του πλαισίου 1
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Αλλαγή καθυστέρησης του πλαισίου 2
    timeLine.Frames[1].Delay = 15;

    // Αλλαγή αδιαφάνειας του 'Layer 1' στο πλαίσιο 2
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // μετακίνηση του 'Layer 1' στην αριστερή-κάτω γωνία στο πλαίσιο 3
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // Προσθέτει νέο πλαίσιο
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // Αλλάξτε το blendMode του 'Layer 1' στο καρέ 4
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Εφαρμόστε τις αλλαγές πίσω στο αντικείμενο PsdImage
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### Δείτε επίσης

* class [PsdImage](../../../aspose.psd.fileformats.psd/psdimage/)
* class [TimeLine](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* assembly [Aspose.PSD](../../../)


