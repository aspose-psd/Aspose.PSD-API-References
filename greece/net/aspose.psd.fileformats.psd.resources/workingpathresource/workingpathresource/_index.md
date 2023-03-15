---
title: WorkingPathResource.WorkingPathResource
second_title: Aspose.PSD για Αναφορά API .NET
description: WorkingPathResource κατασκευαστής. Αρχικοποιεί μια νέα παρουσία τουWorkingPathResource τάξη.
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.resources/workingpathresource/workingpathresource/
---
## WorkingPathResource constructor

Αρχικοποιεί μια νέα παρουσία του[`WorkingPathResource`](../) τάξη.

```csharp
public WorkingPathResource(byte[] dataBytes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataBytes | Byte[] | Τα δεδομένα της διανυσματικής διαδρομής. |

### Παραδείγματα

Αυτό το παράδειγμα δείχνει την υποστήριξη του πόρου "WorkingPathResource" στο PsdImage.ImageResources για τη σωστή λειτουργία της λειτουργίας Crop.

```csharp
[C#]

// Περικοπή εικόνας και αποθήκευση.
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // Αναζήτηση πόρου WorkingPathResource.
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

    // Περικοπή και αποθήκευση.
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// Φορτώστε την αποθηκευμένη εικόνα και ελέγξτε τις αλλαγές.
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // Αναζήτηση πόρου WorkingPathResource.
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
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Resources](../../workingpathresource/)
* συνέλευση [Aspose.PSD](../../../)


