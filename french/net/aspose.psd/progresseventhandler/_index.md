---
title: Delegate ProgressEventHandler
second_title: Référence de l'API Aspose.PSD pour .NET
description: Référence de la fonction de gestionnaire dévénements Progress
type: docs
weight: 5280
url: /fr/net/aspose.psd/progresseventhandler/
---
## ProgressEventHandler delegate

Référence de la fonction de gestionnaire d'événements Progress

```csharp
public delegate void ProgressEventHandler(ProgressEventHandlerInfo info);
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| info | ProgressEventHandlerInfo | Les données du gestionnaire d'événements de progression. |

### Exemples

L'exemple suivant montre que la progression de la conversion du document fonctionne correctement et sans exception.

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

### Voir également

* class [ProgressEventHandlerInfo](../../aspose.psd.progressmanagement/progresseventhandlerinfo/)
* espace de noms [Aspose.PSD](../../aspose.psd/)
* Assemblée [Aspose.PSD](../../)


