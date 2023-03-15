---
title: Delegate ProgressEventHandler
second_title: Aspose.PSD για Αναφορά API .NET
description: Αναφορά συνάρτησης χειριστή συμβάντων προόδου
type: docs
weight: 5280
url: /el/net/aspose.psd/progresseventhandler/
---
## ProgressEventHandler delegate

Αναφορά συνάρτησης χειριστή συμβάντων προόδου

```csharp
public delegate void ProgressEventHandler(ProgressEventHandlerInfo info);
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| info | ProgressEventHandlerInfo | Τα δεδομένα του χειριστή συμβάντων προόδου. |

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

* class [ProgressEventHandlerInfo](../../aspose.psd.progressmanagement/progresseventhandlerinfo/)
* χώρος ονομάτων [Aspose.PSD](../../aspose.psd/)
* συνέλευση [Aspose.PSD](../../)


