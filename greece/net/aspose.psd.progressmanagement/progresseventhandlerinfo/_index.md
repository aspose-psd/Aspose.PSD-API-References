---
title: "Κλάση ProgressEventHandlerInfo"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.ProgressManagement.ProgressEventHandlerInfo κλάση. Αυτή η κλάση αντιπροσωπεύει πληροφορίες σχετικά με την πρόοδο των λειτουργιών φόρτωσης/αποθήκευσης/εξαγωγής εικόνας που μπορούν να χρησιμοποιηθούν σε εξωτερική εφαρμογή για την εμφάνιση της προόδου μετατροπής στον τελικό χρήστη"
type: docs
weight: 5800
url: /el/net/aspose.psd.progressmanagement/progresseventhandlerinfo/
---
{{< psd/tize >}}
## ProgressEventHandlerInfo class

Αυτή η κλάση αντιπροσωπεύει πληροφορίες σχετικά με την πρόοδο των λειτουργιών φόρτωσης/αποθήκευσης/εξαγωγής εικόνας, οι οποίες μπορούν να χρησιμοποιηθούν σε εξωτερική εφαρμογή για να εμφανίσουν την πρόοδο της μετατροπής στον τελικό χρήστη

```csharp
public class ProgressEventHandlerInfo
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Description](../../aspose.psd.progressmanagement/progresseventhandlerinfo/description/) { get; } | Λαμβάνει την περιγραφή του συμβάντος |
| [EventType](../../aspose.psd.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | Λαμβάνει τον τύπο του συμβάντος. |
| [MaxValue](../../aspose.psd.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | Λαμβάνει το ανώτερο όριο τιμής προόδου. |
| [Value](../../aspose.psd.progressmanagement/progresseventhandlerinfo/value/) { get; } | Λαμβάνει την τρέχουσα τιμή προόδου. |

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει ότι η πρόοδος μετατροπής εγγράφου λειτουργεί σωστά και χωρίς εξαίρεση.

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

* namespace [Aspose.PSD.ProgressManagement](../../aspose.psd.progressmanagement/)
* assembly [Aspose.PSD](../../)


