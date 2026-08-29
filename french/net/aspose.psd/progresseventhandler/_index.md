---
title: "Délégué ProgressEventHandler"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Référence de fonction de gestionnaire d’événement de progression"
type: docs
weight: 5780
url: /fr/net/aspose.psd/progresseventhandler/
---
{{< psd/tize >}}
## ProgressEventHandler delegate

Référence de fonction de gestionnaire d’événement de progression

```csharp
public delegate void ProgressEventHandler(ProgressEventHandlerInfo info);
```

| Paramètre | Type | Description |
| --- | --- | --- |
| info | ProgressEventHandlerInfo | Les données du gestionnaire d'événement de progression. |

## Exemples

L'exemple suivant montre que la progression de la conversion de document fonctionne correctement et sans exception.

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

### Voir aussi

* class [ProgressEventHandlerInfo](../../aspose.psd.progressmanagement/progresseventhandlerinfo/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


