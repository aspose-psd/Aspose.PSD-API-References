---
title: Delegate ProgressEventHandler
second_title: Aspose.PSD für .NET-API-Referenz
description: FortschrittsereignisHandlerFunktionsreferenz
type: docs
weight: 5280
url: /de/net/aspose.psd/progresseventhandler/
---
## ProgressEventHandler delegate

Fortschrittsereignis-Handler-Funktionsreferenz

```csharp
public delegate void ProgressEventHandler(ProgressEventHandlerInfo info);
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| info | ProgressEventHandlerInfo | Die Fortschrittsereignis-Handlerdaten. |

### Beispiele

Das folgende Beispiel zeigt, dass der Dokumentkonvertierungsfortschritt korrekt und ohne Ausnahme funktioniert.

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

### Siehe auch

* class [ProgressEventHandlerInfo](../../aspose.psd.progressmanagement/progresseventhandlerinfo/)
* namensraum [Aspose.PSD](../../aspose.psd/)
* Montage [Aspose.PSD](../../)


