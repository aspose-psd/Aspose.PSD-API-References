---
title: StreamSource.StreamSource
second_title: Aspose.PSD per riferimento API .NET
description: StreamSource costruttore. Inizializza una nuova istanza diStreamSource classe.
type: docs
weight: 10
url: /it/net/aspose.psd.sources/streamsource/streamsource/
---
## StreamSource(Stream) {#constructor}

Inizializza una nuova istanza di[`StreamSource`](../) classe.

```csharp
public StreamSource(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso da aprire. |

### Esempi

Questo esempio mostra come caricare le informazioni sui pixel in un array di tipo colore, manipolare l'array e reimpostarlo sull'immagine. Per eseguire queste operazioni, questo esempio crea un nuovo file immagine (in formato PSD) utilizzando l'oggetto MemoryStream.

```csharp
[C#]

//Crea un'istanza di MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Crea un'istanza di PsdOptions e imposta le sue varie proprietà, inclusa la proprietà Source
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Crea un'istanza di Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Ottiene i pixel dell'immagine specificando l'area come confine dell'immagine
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Esegui il loop sull'array e imposta il colore del pixel indicizzato alternativo
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Imposta il colore del pixel indicizzato su giallo
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Imposta il colore del pixel indicizzato su blu
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Applica le modifiche dei pixel all'immagine
        image.SavePixels(image.Bounds, pixels);

        // salva tutte le modifiche.
        image.Save();
    }

    //Scrivi MemoryStream su file
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Guarda anche

* class [StreamSource](../)
* spazio dei nomi [Aspose.PSD.Sources](../../streamsource/)
* assemblea [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

Inizializza una nuova istanza di[`StreamSource`](../) classe.

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso da aprire. |
| disposeStream | Boolean | se impostato su`VERO` il flusso verrà eliminato. |

### Esempi

Questo esempio dimostra l'uso di System.IO.Stream per creare un nuovo file di immagine

```csharp
[C#]

//Crea un'istanza di PsdOptions e ne imposta le varie proprietà
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Crea un'istanza di System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Definire la proprietà di origine per l'istanza di PsdOptions
//Il secondo parametro booleano determina se lo Stream viene eliminato una volta uscito dall'ambito
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Crea un'istanza di Image e chiama il metodo Create con PsdOptions come parametro per inizializzare l'oggetto Image   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //fai un po' di elaborazione delle immagini
}
```

### Guarda anche

* class [StreamSource](../)
* spazio dei nomi [Aspose.PSD.Sources](../../streamsource/)
* assemblea [Aspose.PSD](../../../)


