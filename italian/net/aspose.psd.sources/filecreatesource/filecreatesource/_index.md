---
title: FileCreateSource.FileCreateSource
second_title: Aspose.PSD per riferimento API .NET
description: FileCreateSource costruttore. Inizializza una nuova istanza diFileCreateSource classe.
type: docs
weight: 10
url: /it/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
## FileCreateSource(string) {#constructor}

Inizializza una nuova istanza di[`FileCreateSource`](../) classe.

```csharp
public FileCreateSource(string filePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file da creare. |

### Esempi

Questo esempio crea un nuovo file immagine in una posizione del disco come specificato dalla proprietà Source dell'istanza BmpOptions. Se il secondo parametro non viene passato al costruttore di FileCreateSource, per impostazione predefinita il file da creare ha la proprietà IsTemporal impostata su True. Con IsTemporal impostato su True, nessun file verrà salvato su disco al termine dell'esecuzione.

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//Crea un'istanza di PsdOptions e ne imposta le varie proprietà
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Crea un'istanza di FileCreateSource e assegnala come origine per l'istanza di PsdOptions
//Se il secondo parametro non viene passato, per impostazione predefinita il file ha IsTemporal impostato su True
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

//Crea un'istanza di Image 
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //fai un po' di elaborazione delle immagini
}
```

### Guarda anche

* class [FileCreateSource](../)
* spazio dei nomi [Aspose.PSD.Sources](../../filecreatesource/)
* assemblea [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

Inizializza una nuova istanza di[`FileCreateSource`](../) classe.

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file da creare. |
| isTemporal | Boolean | Se impostato su`VERO` il file creato sarà temporale. |

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

* class [FileCreateSource](../)
* spazio dei nomi [Aspose.PSD.Sources](../../filecreatesource/)
* assemblea [Aspose.PSD](../../../)


