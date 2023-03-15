---
title: Image.RotateFlip
second_title: Aspose.PSD per riferimento API .NET
description: Image metodo. Ruota capovolge o ruota e capovolge limmagine.
type: docs
weight: 220
url: /it/net/aspose.psd/image/rotateflip/
---
## Image.RotateFlip method

Ruota, capovolge o ruota e capovolge l'immagine.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Tipo di rotazione flip. |

### Esempi

Questo esempio dimostra l'uso dell'operazione Ruota su un'immagine. L'esempio carica un file immagine esistente da una posizione del disco ed esegue l'operazione Ruota sull'immagine in base al valore di Enum Aspose.PSD.RotateFlipType

```csharp
[C#]

//Crea un'istanza della classe immagine e inizializzala con un file immagine esistente tramite Percorso file
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Ruota l'immagine di 180 gradi attorno all'asse X
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // salva tutte le modifiche.
    image.Save();
}
```

### Guarda anche

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* spazio dei nomi [Aspose.PSD](../../image/)
* assemblea [Aspose.PSD](../../../)


