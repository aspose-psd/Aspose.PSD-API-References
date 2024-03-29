---
title: Class ProgressEventHandlerInfo
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.ProgressManagement.ProgressEventHandlerInfo klas. Diese Klasse stellt Informationen über den Fortschritt von Lade/Speicher/Exportvorgängen für Bilder dar die in externen Anwendungen verwendet werden können um dem Endbenutzer den Konvertierungsfortschritt anzuzeigen
type: docs
weight: 5300
url: /de/net/aspose.psd.progressmanagement/progresseventhandlerinfo/
---
## ProgressEventHandlerInfo class

Diese Klasse stellt Informationen über den Fortschritt von Lade-/Speicher-/Exportvorgängen für Bilder dar, die in externen Anwendungen verwendet werden können, um dem Endbenutzer den Konvertierungsfortschritt anzuzeigen

```csharp
public class ProgressEventHandlerInfo
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Description](../../aspose.psd.progressmanagement/progresseventhandlerinfo/description/) { get; } | Ruft die Beschreibung des Ereignisses ab |
| [EventType](../../aspose.psd.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | Ruft den Typ des Ereignisses ab. |
| [MaxValue](../../aspose.psd.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | Ruft die obere Fortschrittswertgrenze ab. |
| [Value](../../aspose.psd.progressmanagement/progresseventhandlerinfo/value/) { get; } | Ruft den aktuellen Fortschrittswert ab. |

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

* namensraum [Aspose.PSD.ProgressManagement](../../aspose.psd.progressmanagement/)
* Montage [Aspose.PSD](../../)


