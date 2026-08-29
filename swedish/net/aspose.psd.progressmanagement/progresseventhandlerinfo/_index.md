---
title: "Klass ProgressEventHandlerInfo"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.ProgressManagement.ProgressEventHandlerInfo class. Denna klass representerar information om framsteg för bildladdning/-sparning/-exportoperationer som kan användas i ett externt program för att visa konverteringsframsteg för slutanvändaren"
type: docs
weight: 5800
url: /sv/net/aspose.psd.progressmanagement/progresseventhandlerinfo/
---
{{< psd/tize >}}
## ProgressEventHandlerInfo class

Denna klass representerar information om framsteg för bildladdning/sparning/exportoperationer, som kan användas i en extern applikation för att visa konverteringsframsteg för slutanvändaren.

```csharp
public class ProgressEventHandlerInfo
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Description](../../aspose.psd.progressmanagement/progresseventhandlerinfo/description/) { get; } | Hämtar beskrivningen av händelsen |
| [EventType](../../aspose.psd.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | Hämtar typen av händelsen. |
| [MaxValue](../../aspose.psd.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | Hämtar det övre gränsvärdet för framsteg. |
| [Value](../../aspose.psd.progressmanagement/progresseventhandlerinfo/value/) { get; } | Hämtar aktuellt framstegsvärde. |

## Exempel

Följande exempel visar att dokumentkonverteringsframsteg fungerar korrekt och utan undantag.

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

### Se även

* namespace [Aspose.PSD.ProgressManagement](../../aspose.psd.progressmanagement/)
* assembly [Aspose.PSD](../../)


