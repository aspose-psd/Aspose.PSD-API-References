---
title: IVectorPathData.IsNotLinked
second_title: Aspose.PSD per riferimento API .NET
description: IVectorPathData proprietà. Ottiene o imposta un valore che indica se questa istanza non è collegata.
type: docs
weight: 30
url: /it/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/
---
## IVectorPathData.IsNotLinked property

Ottiene o imposta un valore che indica se questa istanza non è collegata.

```csharp
public bool IsNotLinked { get; set; }
```

### Valore della proprietà

`VERO` se questa istanza non è collegata; Altrimenti,`falso` .

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

* interface [IVectorPathData](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Core.VectorPaths](../../ivectorpathdata/)
* assemblea [Aspose.PSD](../../../)


