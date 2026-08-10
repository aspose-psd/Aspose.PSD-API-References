---
title: "WarpSettings.ProcessingArea"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα WarpSettings. Λαμβάνει ή ορίζει την τιμή του μεγέθους της περιοχής επεξεργασίας. Η προεπιλεγμένη τιμή είναι 10. Το εύρος είναι 240"
type: docs
weight: 40
url: /el/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/processingarea/
---
{{< psd/tize >}}
## WarpSettings.ProcessingArea property

Λαμβάνει ή ορίζει την τιμή του μεγέθους της περιοχής επεξεργασίας. Η προεπιλεγμένη τιμή είναι 10. Το εύρος είναι [2;40]

```csharp
public int ProcessingArea { get; set; }
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την ιδιότητα WarpSettings.ProcessingArea για τη διαμόρφωση της παραμόρφωσης.

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

int[] areaValues = { 5, 10, 25, 40 };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // Λαμβάνει το WarpSettings από το Smart Layer
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Ορίζει το μέγεθος της περιοχής επεξεργασίας του warp
        warpSettings.ProcessingArea = areaValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + areaValues[i] + ".png";
        outputFiles.Add(outputFile);

        // Δεν θα πρέπει να υπάρχει σφάλμα εδώ
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Δείτε επίσης

* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


