---
title: Interface IVectorPathData
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Core.VectorPaths.IVectorPathData interfaccia. Linterfaccia per laccesso ai dati del percorso vettoriale.
type: docs
weight: 1350
url: /it/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/
---
## IVectorPathData interface

L'interfaccia per l'accesso ai dati del percorso vettoriale.

```csharp
public interface IVectorPathData
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/) { get; set; } | Ottiene o imposta un valore che indica se questa istanza è disabilitata. |
| [IsInverted](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/) { get; set; } | Ottiene o imposta un valore che indica se questa istanza è invertita. |
| [IsNotLinked](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/) { get; set; } | Ottiene o imposta un valore che indica se questa istanza non è collegata. |
| [Paths](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/paths/) { get; set; } | Ottiene o imposta i record del percorso. |
| [Version](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/version/) { get; set; } | Ottiene o imposta la versione. |

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

* spazio dei nomi [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assemblea [Aspose.PSD](../../)


