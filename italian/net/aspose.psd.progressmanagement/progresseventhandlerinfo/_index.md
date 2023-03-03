---
title: Class ProgressEventHandlerInfo
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.ProgressManagement.ProgressEventHandlerInfo classe. Questa classe rappresenta le informazioni sullavanzamento delle operazioni di caricamento/salvataggio/esportazione dellimmagine che possono essere utilizzate in unapplicazione esterna per mostrare allutente finale lavanzamento della conversione
type: docs
weight: 5300
url: /it/net/aspose.psd.progressmanagement/progresseventhandlerinfo/
---
## ProgressEventHandlerInfo class

Questa classe rappresenta le informazioni sull'avanzamento delle operazioni di caricamento/salvataggio/esportazione dell'immagine, che possono essere utilizzate in un'applicazione esterna per mostrare all'utente finale l'avanzamento della conversione

```csharp
public class ProgressEventHandlerInfo
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Description](../../aspose.psd.progressmanagement/progresseventhandlerinfo/description/) { get; } | Ottiene la descrizione dell'evento |
| [EventType](../../aspose.psd.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | Ottiene il tipo di evento. |
| [MaxValue](../../aspose.psd.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | Ottiene il limite superiore del valore di avanzamento. |
| [Value](../../aspose.psd.progressmanagement/progresseventhandlerinfo/value/) { get; } | Ottiene il valore di avanzamento corrente. |

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

* spazio dei nomi [Aspose.PSD.ProgressManagement](../../aspose.psd.progressmanagement/)
* assemblea [Aspose.PSD](../../)


