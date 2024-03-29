---
title: Class WorkingPathResource
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Resources.WorkingPathResource klas. Arbeitspfadressource.
type: docs
weight: 3980
url: /de/net/aspose.psd.fileformats.psd.resources/workingpathresource/
---
## WorkingPathResource class

Arbeitspfadressource.

```csharp
public sealed class WorkingPathResource : ResourceBlock, IVectorPathData
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [WorkingPathResource](workingpathresource/)(byte[]) | Initialisiert eine neue Instanz von`WorkingPathResource` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/workingpathresource/datasize/) { get; } | Ruft die Ressourcendatengröße in Byte ab. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Ruft die eindeutige Kennung für die Ressource ab oder legt sie fest. |
| [IsDisabled](../../aspose.psd.fileformats.psd.resources/workingpathresource/isdisabled/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob diese Instanz deaktiviert ist. |
| [IsInverted](../../aspose.psd.fileformats.psd.resources/workingpathresource/isinverted/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob diese Instanz invertiert ist. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.resources/workingpathresource/isnotlinked/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob diese Instanz nicht verknüpft ist. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/workingpathresource/minimalversion/) { get; } | Ruft die minimal erforderliche PSD-Version ab. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Ruft den Ressourcennamen ab oder legt ihn fest. Pascal-String, aufgefüllt, um die Größe gleichmäßig zu machen (ein Nullname besteht aus zwei Bytes von 0). |
| [Paths](../../aspose.psd.fileformats.psd.resources/workingpathresource/paths/) { get; set; } | Ruft die Pfaddatensätze ab oder legt sie fest. |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Ruft die Ressourcensignatur ab. Sollte immer '8BIM' sein. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Ruft die Ressourcenblockgröße in Byte ab, einschließlich seiner Daten. |
| [Version](../../aspose.psd.fileformats.psd.resources/workingpathresource/version/) { get; set; } | Ruft die Version ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Speichert den Ressourcenblock im angegebenen Stream. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Validiert die Ressourcenwerte. |

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

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* namensraum [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* Montage [Aspose.PSD](../../)


