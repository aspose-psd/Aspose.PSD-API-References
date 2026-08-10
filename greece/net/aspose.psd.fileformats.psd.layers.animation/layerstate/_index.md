---
title: "Κλάση LayerState"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState class. Οι επιλογές της κατάστασης στρώματος χρονοδιαγράμματος."
type: docs
weight: 1960
url: /el/net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
{{< psd/tize >}}
## LayerState class

Οι επιλογές της κατάστασης στρώματος χρονογραμμής.

```csharp
public sealed class LayerState
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [LayerState](layerstate/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης. |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | Λαμβάνει ή ορίζει την ενεργοποιημένη κατάσταση. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | Λαμβάνει ή ορίζει την τιμή αδιαφάνειας γεμίσματος. |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | Λαμβάνει ή ορίζει την τιμή HorizontalFXRf. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | Λαμβάνει ή ορίζει το αναγνωριστικό του στρώματος. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | Λαμβάνει ή ορίζει την τιμή αδιαφάνειας. |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | Λαμβάνει ή ορίζει την μετατόπιση θέσης του στρώματος σε σχέση με την πραγματική θέση του στρώματος. |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | Λαμβάνει τα εφέ κατάστασης του στρώματος. |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | Λαμβάνει ή ορίζει την τιμή VerticalFXRf. |

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


