---
title: WorkingPathResource.WorkingPathResource
second_title: Aspose.PSD per riferimento API .NET
description: WorkingPathResource costruttore. Inizializza una nuova istanza diWorkingPathResource classe.
type: docs
weight: 10
url: /it/net/aspose.psd.fileformats.psd.resources/workingpathresource/workingpathresource/
---
## WorkingPathResource constructor

Inizializza una nuova istanza di[`WorkingPathResource`](../) classe.

```csharp
public WorkingPathResource(byte[] dataBytes)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataBytes | Byte[] | I dati del percorso vettoriale. |

### Esempi

Questo esempio dimostra il supporto della risorsa 'WorkingPathResource' in PsdImage.ImageResources per il corretto funzionamento dell'operazione Crop.

```csharp
[C#]

// Ritaglia l'immagine e salva.
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // Cerca la risorsa WorkingPathResource.
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 2572506 || record.Points[0].Y != 8535408)
    {
        throw new Exception("Values is incorrect.");
    }

    // Ritaglia e salva.
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// Carica l'immagine salvata e controlla le modifiche.
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // Cerca la risorsa WorkingPathResource.
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 4630510 || record.Points[0].Y != 22761088)
    {
        throw new Exception("Values is incorrect.");
    }
}
```

### Guarda anche

* class [WorkingPathResource](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Resources](../../workingpathresource/)
* assemblea [Aspose.PSD](../../../)


