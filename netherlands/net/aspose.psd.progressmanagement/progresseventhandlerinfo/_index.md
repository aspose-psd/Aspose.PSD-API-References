---
title: Class ProgressEventHandlerInfo
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.ProgressManagement.ProgressEventHandlerInfo klas. Deze klasse vertegenwoordigt informatie over de voortgang van het laden/opslaan/exporteren van afbeeldingen die kan worden gebruikt in een externe toepassing om de voortgang van de conversie naar de eindgebruiker te tonen
type: docs
weight: 5300
url: /nl/net/aspose.psd.progressmanagement/progresseventhandlerinfo/
---
## ProgressEventHandlerInfo class

Deze klasse vertegenwoordigt informatie over de voortgang van het laden/opslaan/exporteren van afbeeldingen, die kan worden gebruikt in een externe toepassing om de voortgang van de conversie naar de eindgebruiker te tonen

```csharp
public class ProgressEventHandlerInfo
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Description](../../aspose.psd.progressmanagement/progresseventhandlerinfo/description/) { get; } | Krijgt de beschrijving van de gebeurtenis |
| [EventType](../../aspose.psd.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | Haalt het type gebeurtenis op. |
| [MaxValue](../../aspose.psd.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | Haalt de bovenste voortgangswaardelimiet op. |
| [Value](../../aspose.psd.progressmanagement/progresseventhandlerinfo/value/) { get; } | Krijgt huidige voortgangswaarde. |

### Voorbeelden

Het volgende voorbeeld laat zien dat de voortgang van de documentconversie correct en zonder uitzondering werkt.

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

### Zie ook

* naamruimte [Aspose.PSD.ProgressManagement](../../aspose.psd.progressmanagement/)
* montage [Aspose.PSD](../../)


