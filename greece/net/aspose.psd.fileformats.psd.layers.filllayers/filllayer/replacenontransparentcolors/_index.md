---
title: FillLayer.ReplaceNonTransparentColors
second_title: Aspose.PSD για Αναφορά API .NET
description: FillLayer μέθοδος. Αντικαθιστά όλα τα αδιαφανή χρώματα με νέο χρώμα και διατηρεί την αρχική τιμή άλφα για εξοικονόμηση ομαλών άκρων. Σημείωση εάν το χρησιμοποιείτε σε εικόνες χωρίς διαφάνεια όλα τα χρώματα θα αντικατασταθούν με ένα.
type: docs
weight: 40
url: /el/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
## FillLayer.ReplaceNonTransparentColors method

Αντικαθιστά όλα τα αδιαφανή χρώματα με νέο χρώμα και διατηρεί την αρχική τιμή άλφα για εξοικονόμηση ομαλών άκρων. Σημείωση: εάν το χρησιμοποιείτε σε εικόνες χωρίς διαφάνεια, όλα τα χρώματα θα αντικατασταθούν με ένα.

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newColorArgb | Int32 | Νέα τιμή χρώματος ARGB για αντικατάσταση των μη διαφανών χρωμάτων. |

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη του CMYK ColorMode 16 bit και τη δυνατότητα σχεδίασης χρησιμοποιώντας την κλάση Aspose.PSD.Graphics.

```csharp
[C#]

using (PsdImage image = (PsdImage)Image.Load("cub16bit_cmyk.psd"))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save("output.psd");
    image.Save("output.png", new PngOptions());
}
```

### Δείτε επίσης

* class [FillLayer](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* συνέλευση [Aspose.PSD](../../../)


