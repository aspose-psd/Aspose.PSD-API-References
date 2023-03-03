---
title: Class LayerState
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState τάξη. Οι επιλογές της κατάστασης του επιπέδου της γραμμής χρόνου.
type: docs
weight: 1860
url: /el/net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
## LayerState class

Οι επιλογές της κατάστασης του επιπέδου της γραμμής χρόνου.

```csharp
public sealed class LayerState
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [LayerState](layerstate/)(int) | Αρχικοποιεί μια νέα παρουσία του`LayerState` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | Λαμβάνει ή ρυθμίζει τη λειτουργία blen. |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | Λαμβάνει ή ορίζει την κατάσταση ενεργοποίησης. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | Λαμβάνει ή ορίζει την τιμή αδιαφάνειας πλήρωσης. |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | Λαμβάνει ή ορίζει την τιμή HorizontalFXRf. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | Λαμβάνει ή ορίζει το αναγνωριστικό. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | Λαμβάνει ή ορίζει την τιμή αδιαφάνειας. |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | Λαμβάνει ή ορίζει τη μετατόπιση της θέσης του στρώματος που σχετίζεται με την πραγματική θέση του στρώματος. |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | Λαμβάνει τα εφέ κατάστασης επιπέδου. |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | Λαμβάνει ή ορίζει την τιμή VerticalFXRf. |

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


