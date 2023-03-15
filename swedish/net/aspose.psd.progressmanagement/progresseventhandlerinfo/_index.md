---
title: Class ProgressEventHandlerInfo
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.ProgressManagement.ProgressEventHandlerInfo klass. Den här klassen representerar information om bildladdnings/spara/exportens framsteg som kan användas i extern applikation för att visa konverteringsförloppet till slutanvändaren
type: docs
weight: 5300
url: /sv/net/aspose.psd.progressmanagement/progresseventhandlerinfo/
---
## ProgressEventHandlerInfo class

Den här klassen representerar information om bildladdnings/spara/exportens framsteg, som kan användas i extern applikation för att visa konverteringsförloppet till slutanvändaren

```csharp
public class ProgressEventHandlerInfo
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Description](../../aspose.psd.progressmanagement/progresseventhandlerinfo/description/) { get; } | Hämtar beskrivningen av händelsen |
| [EventType](../../aspose.psd.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | Hämtar typen av händelse. |
| [MaxValue](../../aspose.psd.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | Hämtar den övre gränsen för förloppsvärde. |
| [Value](../../aspose.psd.progressmanagement/progresseventhandlerinfo/value/) { get; } | Får aktuellt förloppsvärde. |

### Exempel

Följande exempel visar att dokumentkonverteringen fungerar korrekt och utan undantag.

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

* namnutrymme [Aspose.PSD.ProgressManagement](../../aspose.psd.progressmanagement/)
* hopsättning [Aspose.PSD](../../)


