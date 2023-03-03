---
title: Class ProgressEventHandlerInfo
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.ProgressManagement.ProgressEventHandlerInfo τάξη. Αυτή η κλάση αντιπροσωπεύει πληροφορίες σχετικά με την πρόοδο των λειτουργιών φόρτωσης/αποθήκευσης/εξαγωγής εικόνας που μπορεί να χρησιμοποιηθεί σε εξωτερική εφαρμογή για να δείξει την πρόοδο μετατροπής σε τελικό χρήστη
type: docs
weight: 5300
url: /el/net/aspose.psd.progressmanagement/progresseventhandlerinfo/
---
## ProgressEventHandlerInfo class

Αυτή η κλάση αντιπροσωπεύει πληροφορίες σχετικά με την πρόοδο των λειτουργιών φόρτωσης/αποθήκευσης/εξαγωγής εικόνας, που μπορεί να χρησιμοποιηθεί σε εξωτερική εφαρμογή για να δείξει την πρόοδο μετατροπής σε τελικό χρήστη

```csharp
public class ProgressEventHandlerInfo
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Description](../../aspose.psd.progressmanagement/progresseventhandlerinfo/description/) { get; } | Λαμβάνει την περιγραφή του συμβάντος |
| [EventType](../../aspose.psd.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | Λαμβάνει τον τύπο του συμβάντος. |
| [MaxValue](../../aspose.psd.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | Λαμβάνει το ανώτερο όριο τιμής προόδου. |
| [Value](../../aspose.psd.progressmanagement/progresseventhandlerinfo/value/) { get; } | Λαμβάνει την τρέχουσα τιμή προόδου. |

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει ότι η πρόοδος μετατροπής του εγγράφου λειτουργεί σωστά και χωρίς εξαίρεση.

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD.ProgressManagement](../../aspose.psd.progressmanagement/)
* συνέλευση [Aspose.PSD](../../)


