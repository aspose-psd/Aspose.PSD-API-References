---
title: Image.Create
second_title: Aspose.PSD per riferimento API .NET
description: Image metodo. Crea una nuova immagine utilizzando le opzioni di creazione specificate.
type: docs
weight: 10
url: /it/net/aspose.psd/image/create/
---
## Image.Create method

Crea una nuova immagine utilizzando le opzioni di creazione specificate.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | Le opzioni dell'immagine. |
| width | Int32 | La larghezza. |
| height | Int32 | L'altezza. |

### Valore di ritorno

L'immagine appena creata.

### Esempi

Questo esempio crea un nuovo file immagine in una posizione del disco come specificato dalla proprietà Source dell'istanza PsdOptions. Diverse proprietà per l'istanza PsdOptions vengono impostate prima di creare l'immagine effettiva. Soprattutto la proprietà Source, che in questo caso fa riferimento alla posizione effettiva del disco.

```csharp
[C#]

//Crea un'istanza di PsdOptions e imposta le sue varie proprietà
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Crea un'istanza di FileCreateSource e assegnala come origine per l'istanza di PsdOptions
//Il secondo parametro booleano determina se il file da creare è IsTemporal o meno
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Crea un'istanza di Image e inizializzala con un'istanza di PsdOptions chiamando il metodo Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //fai un po' di elaborazione delle immagini

    // salva tutte le modifiche
    image.Save();
}
```

### Guarda anche

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* spazio dei nomi [Aspose.PSD](../../image/)
* assemblea [Aspose.PSD](../../../)


