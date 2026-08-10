---
title: "PsdOptions.BackgroundContents"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα PsdOptions. Λαμβάνει ή ορίζει το χρώμα του φόντου. Μπορεί να φαίνεται κάτω από διαφανή αντικείμενα."
type: docs
weight: 20
url: /el/net/aspose.psd.imageoptions/psdoptions/backgroundcontents/
---
{{< psd/tize >}}
## PsdOptions.BackgroundContents property

Λαμβάνει ή ορίζει το χρώμα του φόντου. Μπορεί να φαίνεται κάτω από διαφανή αντικείμενα.

```csharp
public RawColor BackgroundContents { get; set; }
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη της ιδιότητας BackgroundContents στο PsdOptions.

```csharp
[C#]

// Η ημιδιαφάνεια επεξεργάζεται λανθασμένα στην προεπισκόπηση του αρχείου psd.
// Το BackgroundContents ορίζεται σε Λευκό. Οι διαφανείς περιοχές πρέπει να έχουν λευκό χρώμα.

string sourceFile = "frog_nosymb.psd";
string outputFile = "frog_nosymb_backgroundcontents_output.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    RawColor backgroundColor = new RawColor(PixelDataFormat.Rgb32Bpp);
    int argbValue = 255 << 24 | 255 << 16 | 255 << 8 | 255;
    backgroundColor.SetAsInt(argbValue); // White

    PsdOptions psdOptions = new PsdOptions(psdImage)
    {
        ColorMode = ColorModes.Rgb,
        CompressionMethod = CompressionMethod.RLE,
        ChannelsCount = 4,
        BackgroundContents = backgroundColor,
    };

    psdImage.Save(outputFile, psdOptions);
}
```

### Δείτε επίσης

* class [RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


