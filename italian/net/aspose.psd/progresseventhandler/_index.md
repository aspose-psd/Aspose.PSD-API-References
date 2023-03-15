---
title: Delegate ProgressEventHandler
second_title: Aspose.PSD per riferimento API .NET
description: Riferimento funzione gestore eventi di avanzamento
type: docs
weight: 5280
url: /it/net/aspose.psd/progresseventhandler/
---
## ProgressEventHandler delegate

Riferimento funzione gestore eventi di avanzamento

```csharp
public delegate void ProgressEventHandler(ProgressEventHandlerInfo info);
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| info | ProgressEventHandlerInfo | I dati del gestore dell'evento progress. |

### Esempi

L'esempio seguente dimostra che l'avanzamento della conversione del documento funziona correttamente e senza eccezioni.

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

### Guarda anche

* class [ProgressEventHandlerInfo](../../aspose.psd.progressmanagement/progresseventhandlerinfo/)
* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


