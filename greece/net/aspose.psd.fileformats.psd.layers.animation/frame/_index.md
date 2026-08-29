---
title: "Κλάση Frame"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.Frame class. Οι επιλογές του στοιχείου πλαισίου χρονοδιαγράμματος"
type: docs
weight: 1940
url: /el/net/aspose.psd.fileformats.psd.layers.animation/frame/
---
{{< psd/tize >}}
## Frame class

Οι επιλογές του στοιχείου πλαισίου χρονογραμμής.

```csharp
public sealed class Frame
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Frame](frame/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Delay](../../aspose.psd.fileformats.psd.layers.animation/frame/delay/) { get; set; } | Λαμβάνει ή ορίζει την τιμή καθυστέρησης του πλαισίου σε κεντα-δευτερόλεπτα. Για παράδειγμα, σε 1 δευτερόλεπτο περιέχονται 100 κεντα-δευτερόλεπτα. |
| [DisposalMethod](../../aspose.psd.fileformats.psd.layers.animation/frame/disposalmethod/) { get; set; } | Λαμβάνει ή ορίζει τη μέθοδο απόρριψης του πλαισίου. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/frame/id/) { get; set; } | Λαμβάνει ή ορίζει το αναγνωριστικό του πλαισίου. |
| [LayerStates](../../aspose.psd.fileformats.psd.layers.animation/frame/layerstates/) { get; set; } | Λαμβάνει ή ορίζει τις καταστάσεις των στρωμάτων του πλαισίου. |

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


