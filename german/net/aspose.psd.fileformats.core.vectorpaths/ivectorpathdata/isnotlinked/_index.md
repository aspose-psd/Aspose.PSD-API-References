---
title: "IVectorPathData.IsNotLinked"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "IVectorPathData Eigenschaft. Liest einen Wert aus oder legt ihn fest, der angibt, ob diese Instanz nicht verknüpft ist"
type: docs
weight: 30
url: /de/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/
---
{{< psd/tize >}}
## IVectorPathData.IsNotLinked property

Liest oder legt einen Wert fest, der angibt, ob diese Instanz nicht verknüpft ist.

```csharp
public bool IsNotLinked { get; set; }
```

### Property Value

`true`, wenn diese Instanz nicht verknüpft ist; andernfalls `false`.

## Beispiele

Dieses Beispiel demonstriert die Unterstützung der 'WorkingPathResource'-Ressource in PsdImage.ImageResources für das korrekte Funktionieren der Zuschneide-Operation.

```csharp
[C#]

// Bild zuschneiden und speichern.
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // Suche WorkingPathResource-Ressource.
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

    // Zuschneiden und speichern.
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// Lade das gespeicherte Bild und prüfe die Änderungen.
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // Suche WorkingPathResource-Ressource.
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

### Siehe auch

* interface [IVectorPathData](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


