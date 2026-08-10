---
title: "FillLayer.ReplaceNonTransparentColors"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος FillLayer. Αντικαθιστά όλα τα μη διαφανή χρώματα με νέο χρώμα και διατηρεί την αρχική τιμή άλφα για να διατηρηθούν οι ομαλές άκρες. Σημειώστε ότι εάν τη χρησιμοποιήσετε σε εικόνες χωρίς διαφάνεια, όλα τα χρώματα θα αντικατασταθούν με ένα ενιαίο."
type: docs
weight: 40
url: /el/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
{{< psd/tize >}}
## FillLayer.ReplaceNonTransparentColors method

Αντικαθιστά όλα τα μη διαφανή χρώματα με νέο χρώμα και διατηρεί την αρχική τιμή άλφα για τη διατήρηση ομαλών άκρων. Σημείωση: εάν το χρησιμοποιήσετε σε εικόνες χωρίς διαφάνεια, όλα τα χρώματα θα αντικατασταθούν με ένα ενιαίο.

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newColorArgb | Int32 | Νέα τιμή ARGB χρώματος για αντικατάσταση μη διαφανών χρωμάτων. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη της λειτουργίας χρώματος CMYK 16-bit και τη δυνατότητα σχεδίασης χρησιμοποιώντας την κλάση Aspose.PSD.Graphics.

```csharp
[C#]

string srcFile = "cub16bit_cmyk.psd";
string outputPsd = "output.psd";
string outputPng = "output.png";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### Δείτε επίσης

* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


