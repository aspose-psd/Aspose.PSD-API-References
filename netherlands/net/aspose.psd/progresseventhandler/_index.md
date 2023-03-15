---
title: Delegate ProgressEventHandler
second_title: Aspose.PSD voor .NET API-referentie
description: Functiereferentie handler voortgangsgebeurtenis
type: docs
weight: 5280
url: /nl/net/aspose.psd/progresseventhandler/
---
## ProgressEventHandler delegate

Functiereferentie handler voortgangsgebeurtenis

```csharp
public delegate void ProgressEventHandler(ProgressEventHandlerInfo info);
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| info | ProgressEventHandlerInfo | De gegevens van de voortgangsgebeurtenishandler. |

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

* class [ProgressEventHandlerInfo](../../aspose.psd.progressmanagement/progresseventhandlerinfo/)
* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


