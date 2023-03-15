---
title: RasterImage.SavePixels
second_title: Aspose.PSD per riferimento API .NET
description: RasterImage metodo. Salva i pixel.
type: docs
weight: 520
url: /it/net/aspose.psd/rasterimage/savepixels/
---
## RasterImage.SavePixels method

Salva i pixel.

```csharp
public void SavePixels(Rectangle rectangle, Color[] pixels)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | Rectangle | Rettangolo in cui salvare i pixel. |
| pixels | Color[] | La matrice di pixel. |

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

* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [RasterImage](../)
* spazio dei nomi [Aspose.PSD](../../rasterimage/)
* assemblea [Aspose.PSD](../../../)


