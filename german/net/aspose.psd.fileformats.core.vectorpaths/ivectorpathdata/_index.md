---
title: "Schnittstelle IVectorPathData"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.IVectorPathData Schnittstelle. Die Schnittstelle für den Zugriff auf die Vektorpfaddaten"
type: docs
weight: 1360
url: /de/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/
---
{{< psd/tize >}}
## IVectorPathData interface

Die Schnittstelle für den Zugriff auf die Vektorpfaddaten.

```csharp
public interface IVectorPathData
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/) { get; set; } | Liest oder legt einen Wert fest, der angibt, ob diese Instanz deaktiviert ist. |
| [IsInverted](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/) { get; set; } | Liest oder legt einen Wert fest, der angibt, ob diese Instanz invertiert ist. |
| [IsNotLinked](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/) { get; set; } | Liest oder legt einen Wert fest, der angibt, ob diese Instanz nicht verknüpft ist. |
| [Paths](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/paths/) { get; set; } | Liest oder legt die Pfad-Datensätze fest. |
| [Version](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/version/) { get; set; } | Ruft die Version ab oder legt sie fest. |

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

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


