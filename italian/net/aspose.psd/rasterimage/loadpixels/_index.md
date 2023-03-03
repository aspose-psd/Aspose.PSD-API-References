---
title: RasterImage.LoadPixels
second_title: Aspose.PSD per riferimento API .NET
description: RasterImage metodo. Carica i pixel.
type: docs
weight: 400
url: /it/net/aspose.psd/rasterimage/loadpixels/
---
## RasterImage.LoadPixels method

Carica i pixel.

```csharp
public Color[] LoadPixels(Rectangle rectangle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | Rectangle | Il rettangolo da cui caricare i pixel. |

### Valore di ritorno

L'array di pixel caricati.

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

* struct [Color](../../color/)
* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* spazio dei nomi [Aspose.PSD](../../rasterimage/)
* assemblea [Aspose.PSD](../../../)


