---
title: WorkingPathResource.Paths
second_title: Aspose.PSD für .NET-API-Referenz
description: WorkingPathResource eigendom. Ruft die Pfaddatensätze ab oder legt sie fest.
type: docs
weight: 70
url: /de/net/aspose.psd.fileformats.psd.resources/workingpathresource/paths/
---
## WorkingPathResource.Paths property

Ruft die Pfaddatensätze ab oder legt sie fest.

```csharp
public VectorPathRecord[] Paths { get; set; }
```

### Eigentumswert

Die Pfade.

### Beispiele

Dieses Beispiel demonstriert die Unterstützung der Ressource „WorkingPathResource“ in PsdImage.ImageResources für das korrekte Funktionieren des Crop-Vorgangs.

```csharp
[C#]

// Bild zuschneiden und speichern.
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // WorkingPathResource-Ressource durchsuchen.
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

// Gespeichertes Bild laden und die Änderungen überprüfen.
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // WorkingPathResource-Ressource durchsuchen.
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
* namensraum [Aspose.PSD.FileFormats.Psd.Resources](../../workingpathresource/)
* Montage [Aspose.PSD](../../../)


