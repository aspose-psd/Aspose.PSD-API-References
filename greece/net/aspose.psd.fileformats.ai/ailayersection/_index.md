---
title: Class AiLayerSection
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Ai.AiLayerSection τάξη. Τομέας επιπέδου με μορφή Ai
type: docs
weight: 1270
url: /el/net/aspose.psd.fileformats.ai/ailayersection/
---
## AiLayerSection class

Τομέας επιπέδου με μορφή Ai

```csharp
public sealed class AiLayerSection : AiDataSection
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Blue](../../aspose.psd.fileformats.ai/ailayersection/blue/) { get; set; } | Λαμβάνει ή ορίζει το στοιχείο μπλε χρώματος. |
| [ColorNumber](../../aspose.psd.fileformats.ai/ailayersection/colornumber/) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό χρώματος. -1 είναι η προσαρμοσμένη τιμή χρώματος από τις ιδιότητες Κόκκινο, Πράσινο, Μπλε. Καθορίζει τη ρύθμιση χρώματος του επιπέδου. |
| [DimValue](../../aspose.psd.fileformats.ai/ailayersection/dimvalue/) { get; set; } | Λαμβάνει ή ορίζει την τιμή dim ως ποσοστό. Μειώνει την ένταση των συνδεδεμένων εικόνων και των εικόνων bitmap που περιέχονται στο επίπεδο στο καθορισμένο ποσοστό. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διατεθεί. |
| [Green](../../aspose.psd.fileformats.ai/ailayersection/green/) { get; set; } | Λαμβάνει ή ορίζει το στοιχείο πράσινου χρώματος. |
| [IsImagesDimmed](../../aspose.psd.fileformats.ai/ailayersection/isimagesdimmed/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το επίπεδο είναι σκοτεινό. Μειώνει την ένταση των συνδεδεμένων εικόνων και των εικόνων bitmap που περιέχονται στο επίπεδο. |
| [IsLocked](../../aspose.psd.fileformats.ai/ailayersection/islocked/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το επίπεδο είναι κλειδωμένο. Αποτρέπει αλλαγές στο στοιχείο. |
| [IsPreview](../../aspose.psd.fileformats.ai/ailayersection/ispreview/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το επίπεδο είναι προεπισκόπηση. Εμφανίζει το έργο τέχνης που περιέχεται στο επίπεδο με χρώμα αντί για περιγράμματα. |
| [IsPrinted](../../aspose.psd.fileformats.ai/ailayersection/isprinted/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το επίπεδο έχει εκτυπωθεί. Κάνει το έργο τέχνης που περιέχεται στο επίπεδο εκτυπώσιμο εάν είναι αληθές. |
| [IsShown](../../aspose.psd.fileformats.ai/ailayersection/isshown/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το επίπεδο εμφανίζεται. Εμφανίζει όλα τα έργα τέχνης που περιέχονται στο επίπεδο στον πίνακα γραφικών, εάν είναι true. |
| [IsTemplate](../../aspose.psd.fileformats.ai/ailayersection/istemplate/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το επίπεδο είναι επίπεδο προτύπου. |
| [Name](../../aspose.psd.fileformats.ai/ailayersection/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα του επιπέδου. Καθορίζει το όνομα του στοιχείου όπως εμφανίζεται στον πίνακα "Επίπεδα". |
| [RasterImages](../../aspose.psd.fileformats.ai/ailayersection/rasterimages/) { get; } | Λαμβάνει τις εικόνες ράστερ. |
| [Red](../../aspose.psd.fileformats.ai/ailayersection/red/) { get; set; } | Λαμβάνει ή ορίζει το στοιχείο κόκκινου χρώματος. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddRasterImage](../../aspose.psd.fileformats.ai/ailayersection/addrasterimage/)(AiRasterImageSection) | Προσθέτει την εικόνα ράστερ. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Διαθέτει την τρέχουσα παρουσία. |
| [GetData](../../aspose.psd.fileformats.ai/aidatasection/getdata/)() | Λαμβάνει τα δεδομένα συμβολοσειράς. |

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει τον τρόπο φόρτωσης των ρυθμίσεων των εικόνων ράστερ σε αρχεία μορφής AI.

```csharp
[C#]

const double DefaultTolerance = 1e-6;

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}

string sourceFile = "sample.ai";
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AiLayerSection layer = image.Layers[0];

    AssertIsTrue(layer.RasterImages != null, "RasterImages property should be not null");
    AssertIsTrue(layer.RasterImages.Length == 1, "RasterImages property should contain exactly one item");

    AiRasterImageSection rasterImage = layer.RasterImages[0];
    AssertIsTrue(rasterImage.Pixels != null, "rasterImage.Pixels property should be not null");
    AssertIsTrue(rasterImage.Pixels.Length == 100, "rasterImage.Pixels property should contain exactly 100 items");
    AssertIsTrue((uint)rasterImage.Pixels[99] == 0xFFB21616, "rasterImage.Pixels[99] should be 0xFFB21616");
    AssertIsTrue((uint)rasterImage.Pixels[19] == 0xFF00FF00, "rasterImage.Pixels[19] should be 0xFF00FF00");
    AssertIsTrue((uint)rasterImage.Pixels[10] == 0xFF01FD00, "rasterImage.Pixels[10] should be 0xFF01FD00");
    AssertIsTrue((uint)rasterImage.Pixels[0] == 0xFF0000FF, "rasterImage.Pixels[0] should be 0xFF0000FF");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Width) < DefaultTolerance, "rasterImage.Width should be 0.99987");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Height) < DefaultTolerance, "rasterImage.Height should be 0.99987");
    AssertIsTrue(Math.Abs(387 - rasterImage.OffsetX) < DefaultTolerance, "rasterImage.OffsetX should be 387");
    AssertIsTrue(Math.Abs(379 - rasterImage.OffsetY) < DefaultTolerance, "rasterImage.OffsetY should be 379");
    AssertIsTrue(Math.Abs(0 - rasterImage.Angle) < DefaultTolerance, "rasterImage.Angle should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.LeftBottomShift) < DefaultTolerance, "rasterImage.LeftBottomShift should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.X) < DefaultTolerance, "rasterImage.ImageRectangle.X should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.Y) < DefaultTolerance, "rasterImage.ImageRectangle.Y should be 0");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Width) < DefaultTolerance, "rasterImage.ImageRectangle.Width should be 10");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Height) < DefaultTolerance, "rasterImage.ImageRectangle.Height should be 10");
}
```

### Δείτε επίσης

* class [AiDataSection](../aidatasection/)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* συνέλευση [Aspose.PSD](../../)


