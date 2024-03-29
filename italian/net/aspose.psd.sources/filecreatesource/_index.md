---
title: Class FileCreateSource
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.Sources.FileCreateSource classe. Rappresenta unorigine file per la creazione.
type: docs
weight: 5590
url: /it/net/aspose.psd.sources/filecreatesource/
---
## FileCreateSource class

Rappresenta un'origine file per la creazione.

```csharp
public sealed class FileCreateSource : FileSource
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | Inizializza una nuova istanza di`FileCreateSource` classe. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | Inizializza una nuova istanza di`FileCreateSource` classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | Ottiene il percorso del file da creare. |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | Ottiene un valore che indica se il file sarà temporaneo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | Ottiene il contenitore del flusso. |

### Esempi

Questo esempio dimostra l'uso della classe Font e SolidBrush per disegnare stringhe sulla superficie dell'immagine. L'esempio crea una nuova immagine Image e disegna forme usando Figures e GraphicsPath

```csharp
[C#]

//Crea un'istanza di Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crea e inizializza un'istanza della classe Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Cancella la superficie grafica
    graphics.Clear(Color.Wheat);

    //Crea un'istanza di Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Crea un'istanza di SolidBrush con colore rosso
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    // Disegna una stringa
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // crea opzioni di esportazione.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // salva tutte le modifiche
    image.Save("C:\\temp\\output.gif", options);
}
```

### Guarda anche

* class [FileSource](../filesource/)
* spazio dei nomi [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assemblea [Aspose.PSD](../../)


