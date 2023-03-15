---
title: Enum FrameDisposalMethod
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod αρίθμηση. Η μέθοδος απόρριψης πλαισίου καθορίζει εάν θα απορριφθεί το τρέχον πλαίσιο πριν από την εμφάνιση του επόμενου καρέ. Επιλέγετε μια μέθοδο απόρριψης για κινούμενες εικόνες που περιλαμβάνουν διαφάνεια φόντου για να καθορίσετε εάν το πλαίσιο τρέχον θα είναι ορατό μέσα από τις διαφανείς περιοχές του επόμενου καρέ.
type: docs
weight: 1850
url: /el/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
## FrameDisposalMethod enumeration

Η μέθοδος απόρριψης πλαισίου καθορίζει εάν θα απορριφθεί το τρέχον πλαίσιο πριν από την εμφάνιση του επόμενου καρέ. Επιλέγετε μια μέθοδο απόρριψης για κινούμενες εικόνες που περιλαμβάνουν διαφάνεια φόντου για να καθορίσετε εάν το πλαίσιο τρέχον θα είναι ορατό μέσα από τις διαφανείς περιοχές του επόμενου καρέ.

```csharp
public enum FrameDisposalMethod
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| Automatic | `0` | Καθορίζει αυτόματα μια μέθοδο απόρριψης για το τρέχον πλαίσιο, απορρίπτοντας το τρέχον πλαίσιο εάν το επόμενο πλαίσιο περιέχει διαφάνεια επιπέδου. Για τα περισσότερα κινούμενα σχέδια, η επιλογή Αυτόματη (προεπιλογή) δίνει τα επιθυμητά αποτελέσματα. |
| DoNotDispose | `1` | Διατηρεί το τρέχον πλαίσιο καθώς προστίθεται το επόμενο πλαίσιο στην οθόνη. Το τρέχον πλαίσιο (και τα προηγούμενα καρέ) μπορεί να εμφανίζονται μέσα από διαφανείς περιοχές του επόμενου καρέ. |
| Dispose | `2` | Απορρίπτει το τρέχον πλαίσιο από την οθόνη πριν εμφανιστεί το επόμενο καρέ. Εμφανίζεται μόνο ένα καρέ ανά πάσα στιγμή (και το τρέχον πλαίσιο δεν εμφανίζεται μέσα από τις διαφανείς περιοχές του επόμενου καρέ). |

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

* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* συνέλευση [Aspose.PSD](../../)


