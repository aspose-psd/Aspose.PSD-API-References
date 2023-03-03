---
title: Class Frame
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.Frame τάξη. Οι επιλογές του στοιχείου χρονικού πλαισίου.
type: docs
weight: 1840
url: /el/net/aspose.psd.fileformats.psd.layers.animation/frame/
---
## Frame class

Οι επιλογές του στοιχείου χρονικού πλαισίου.

```csharp
public sealed class Frame
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [Frame](frame/)(TimeLine) | Αρχικοποιεί μια νέα παρουσία του`Frame` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Delay](../../aspose.psd.fileformats.psd.layers.animation/frame/delay/) { get; set; } | Λαμβάνει ή ορίζει την τιμή καθυστέρησης καρέ σε εκατοστά δευτερόλεπτα. Για παράδειγμα, σε 1 δευτερόλεπτο περιέχει 100 centa-seconds. |
| [DisposalMethod](../../aspose.psd.fileformats.psd.layers.animation/frame/disposalmethod/) { get; set; } | Λαμβάνει ή ορίζει τη μέθοδο απόρριψης του πλαισίου. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/frame/id/) { get; set; } | Λαμβάνει ή ορίζει το αναγνωριστικό πλαισίου. |
| [LayerStates](../../aspose.psd.fileformats.psd.layers.animation/frame/layerstates/) { get; } | Λαμβάνει ot ορίζει τις καταστάσεις στρώματος του πλαισίου. |

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


