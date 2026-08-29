---
title: "WorkingPathResource.WorkingPathResource"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κατασκευαστής WorkingPathResource. Αρχικοποιεί μια νέα παρουσία της κλάσης WorkingPathResource"
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.resources/workingpathresource/workingpathresource/
---
{{< psd/tize >}}
## WorkingPathResource constructor

Αρχικοποιεί μια νέα παρουσία της κλάσης [`WorkingPathResource`](../).

```csharp
public WorkingPathResource(byte[] dataBytes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataBytes | Byte[] | Τα δεδομένα της διανυσματικής διαδρομής. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει την υποστήριξη του πόρου 'WorkingPathResource' στο PsdImage.ImageResources για σωστή λειτουργία της λειτουργίας Κοπής.

```csharp
[C#]

// Κόψτε την εικόνα και αποθηκεύστε την.
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // Αναζητήστε τον πόρο WorkingPathResource.
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

    // Κόψτε και αποθηκεύστε.
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// Φορτώστε την αποθηκευμένη εικόνα και ελέγξτε τις αλλαγές.
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // Αναζητήστε τον πόρο WorkingPathResource.
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

### Δείτε επίσης

* class [WorkingPathResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


