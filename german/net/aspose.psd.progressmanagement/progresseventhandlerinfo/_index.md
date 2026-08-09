---
title: "Klasse ProgressEventHandlerInfo"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.ProgressManagement.ProgressEventHandlerInfo‑Klasse. Diese Klasse stellt Informationen über den Fortschritt von Bild‑Lade‑/Speicher‑/Export‑Operationen bereit, die in einer externen Anwendung verwendet werden können, um dem Endbenutzer den Konvertierungsfortschritt anzuzeigen."
type: docs
weight: 5800
url: /de/net/aspose.psd.progressmanagement/progresseventhandlerinfo/
---
{{< psd/tize >}}
## ProgressEventHandlerInfo class

Diese Klasse stellt Informationen über den Fortschritt von Bildlade-/Speicher-/Exportvorgängen bereit, die in einer externen Anwendung verwendet werden können, um dem Endbenutzer den Konvertierungsfortschritt anzuzeigen

```csharp
public class ProgressEventHandlerInfo
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Description](../../aspose.psd.progressmanagement/progresseventhandlerinfo/description/) { get; } | Liest die Beschreibung des Ereignisses |
| [EventType](../../aspose.psd.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | Liest den Typ des Ereignisses. |
| [MaxValue](../../aspose.psd.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | Liest die obere Grenze des Fortschrittswertes. |
| [Value](../../aspose.psd.progressmanagement/progresseventhandlerinfo/value/) { get; } | Liest den aktuellen Fortschrittswert. |

## Beispiele

Das folgende Beispiel demonstriert, dass der Dokumentkonvertierungsfortschritt korrekt funktioniert und ohne Ausnahme.

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

* namespace [Aspose.PSD.ProgressManagement](../../aspose.psd.progressmanagement/)
* assembly [Aspose.PSD](../../)


