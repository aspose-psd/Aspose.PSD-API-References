---
title: "WarpSettings.GridSize"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα WarpSettings. Λαμβάνει ή ορίζει το μέγεθος του πλέγματος παραμόρφωσης. Η προεπιλογή είναι 1"
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/gridsize/
---
{{< psd/tize >}}
## WarpSettings.GridSize property

Λαμβάνει ή ορίζει το μέγεθος του πλέγματος παραμόρφωσης. Η προεπιλογή είναι 1.

```csharp
public Size GridSize { get; set; }
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη της ιδιότητας WarpSettings.GridSize.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Αποκτήστε ρυθμίσεις παραμόρφωσης
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Ορίστε νέο μέγεθος
    // Για το Photoshop η τιμή μπορεί να είναι μεταξύ 1 και 50 και δεν μπορείτε να αποθηκεύσετε σωστά το αρχείο PSD.
    warpSettings.GridSize = new Size(100, 100);

    // Ορίστε έγκυρη τιμή
    warpSettings.GridSize = new Size(3, 3);

    // Αποδώστε το παράδειγμα αρχείου με πλέγμα x3
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Δείτε επίσης

* struct [Size](../../../aspose.psd/size/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


