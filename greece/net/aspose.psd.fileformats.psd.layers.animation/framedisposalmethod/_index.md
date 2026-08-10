---
title: "Απαρίθμηση FrameDisposalMethod"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod enum. Η μέθοδος απόρριψης του πλαισίου καθορίζει εάν θα απορριφθεί το τρέχον πλαίσιο πριν την εμφάνιση του επόμενου πλαισίου. Επιλέγετε μια μέθοδο απόρριψης για κινούμενα σχέδια που περιλαμβάνουν διαφάνεια φόντου ώστε να καθορίσετε εάν το τρέχον πλαίσιο θα είναι ορατό μέσω των διαφανών περιοχών του επόμενου πλαισίου."
type: docs
weight: 1950
url: /el/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
{{< psd/tize >}}
## FrameDisposalMethod enumeration

Η μέθοδος απόρριψης πλαισίου καθορίζει εάν θα απορριφθεί το τρέχον πλαίσιο πριν από την εμφάνιση του επόμενου πλαισίου. Επιλέγετε μια μέθοδο απόρριψης για κινούμενα σχέδια που περιλαμβάνουν διαφάνεια φόντου ώστε να καθορίσετε εάν το τρέχον πλαίσιο θα είναι ορατό μέσω των διαφανών περιοχών του επόμενου πλαισίου.

```csharp
public enum FrameDisposalMethod
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Automatic | `0` | Καθορίζει αυτόματα μια μέθοδο απόρριψης για το τρέχον πλαίσιο, απορρίπτοντας το τρέχον πλαίσιο εάν το επόμενο πλαίσιο περιέχει διαφάνεια στρώματος. Για τα περισσότερα κινούμενα σχέδια, η επιλογή Αυτόματη (προεπιλογή) παρέχει τα επιθυμητά αποτελέσματα. |
| DoNotDispose | `1` | Διατηρεί το τρέχον πλαίσιο καθώς προστίθεται το επόμενο πλαίσιο στην οθόνη. Το τρέχον πλαίσιο (και τα προηγούμενα πλαίσια) μπορεί να φαίνεται μέσω των διαφανών περιοχών του επόμενου πλαισίου. |
| Dispose | `2` | Απορρίπτει το τρέχον πλαίσιο από την οθόνη πριν εμφανιστεί το επόμενο πλαίσιο. Μόνο ένα πλαίσιο εμφανίζεται κάθε φορά (και το τρέχον πλαίσιο δεν εμφανίζεται μέσω των διαφανών περιοχών του επόμενου πλαισίου). |

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


