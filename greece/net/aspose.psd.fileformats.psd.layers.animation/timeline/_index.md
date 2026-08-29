---
title: "Κλάση Timeline"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.Timeline κλάση. Το μοντέλο επιλογών χρονογραμμής."
type: docs
weight: 1980
url: /el/net/aspose.psd.fileformats.psd.layers.animation/timeline/
---
{{< psd/tize >}}
## Timeline class

Το μοντέλο επιλογών χρονογραμμής.

```csharp
public sealed class Timeline
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Timeline](timeline/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ActiveFrameIndex](../../aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/) { get; } | Λαμβάνει τον δείκτη του ενεργού πλαισίου. |
| [AFSt](../../aspose.psd.fileformats.psd.layers.animation/timeline/afst/) { get; set; } | Λαμβάνει ή ορίζει την τιμή AFSt. |
| [Frames](../../aspose.psd.fileformats.psd.layers.animation/timeline/frames/) { get; set; } | Λαμβάνει τη λίστα των πλαισίων. |
| [FsID](../../aspose.psd.fileformats.psd.layers.animation/timeline/fsid/) { get; set; } | Λαμβάνει ή ορίζει την τιμή FsID. |
| [LoopesCount](../../aspose.psd.fileformats.psd.layers.animation/timeline/loopescount/) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό των επαναλήψεων. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd.layers.animation/timeline/save/#save)(Stream, ImageOptionsBase) | Αποθηκεύει τα δεδομένα του PsdImage και του Timeline στο καθορισμένο ρεύμα στην καθορισμένη μορφή σύμφωνα με τις επιλογές αποθήκευσης. |
| [Save](../../aspose.psd.fileformats.psd.layers.animation/timeline/save/#save_1)(string, ImageOptionsBase) | Αποθηκεύει τα δεδομένα του PsdImage και του Timeline στην καθορισμένη τοποθεσία αρχείου στην καθορισμένη μορφή σύμφωνα με τις επιλογές αποθήκευσης. |
| [SwitchActiveFrame](../../aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/)(int) | Αλλάζει το ενεργό πλαίσιο στο στοχευόμενο. |

## Παραδείγματα

Η κλάση Timeline παρέχει μια υψηλού επιπέδου δυνατότητα να χειρίζεται τη χρονογραμμή του PsdImage, όπως η αλλαγή καθυστέρησης πλαισίου ή η επεξεργασία της κατάστασης στρώσης σε συγκεκριμένο πλαίσιο.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    // Αλλαγή μεθόδου αποδέσμευσης του πλαισίου 1
    timeline.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Αλλαγή καθυστέρησης του πλαισίου 2
    timeline.Frames[1].Delay = 15;

    // Αλλαγή αδιαφάνειας του 'Layer 1' στο πλαίσιο 2
    LayerState layerState11 = timeline.Frames[1].LayerStates[1];
    layerState11.Opacity = 50;

    // μετακίνηση του 'Layer 1' στην αριστερή-κάτω γωνία στο πλαίσιο 3
    LayerState layerState21 = timeline.Frames[2].LayerStates[1];
    layerState21.PositionOffset = new Point(-50, 230);

    // Προσθέτει νέο πλαίσιο
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    // Αλλάξτε το blendMode του 'Layer 1' στο καρέ 4
    LayerState layerState31 = timeline.Frames[3].LayerStates[1];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Εφαρμόστε τις αλλαγές πίσω στο αντικείμενο PsdImage
    psdImage.Save(outputPsd);
}
```

### Δείτε επίσης

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../)


