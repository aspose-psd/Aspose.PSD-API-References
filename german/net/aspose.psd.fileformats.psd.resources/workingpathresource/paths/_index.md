---
title: "WorkingPathResource.Paths"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "WorkingPathResource-Eigenschaft. Gibt die Pfaddatensätze zurück oder legt sie fest"
type: docs
weight: 70
url: /de/net/aspose.psd.fileformats.psd.resources/workingpathresource/paths/
---
{{< psd/tize >}}
## WorkingPathResource.Paths property

Liest oder legt die Pfad-Datensätze fest.

```csharp
public VectorPathRecord[] Paths { get; set; }
```

### Property Value

Die Pfade.

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

* class [VectorPathRecord](../../../aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/)
* class [WorkingPathResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


