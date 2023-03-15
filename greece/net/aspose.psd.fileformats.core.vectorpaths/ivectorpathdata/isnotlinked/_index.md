---
title: IVectorPathData.IsNotLinked
second_title: Aspose.PSD για Αναφορά API .NET
description: IVectorPathData ιδιοκτησία. Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία δεν είναι συνδεδεμένη.
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/
---
## IVectorPathData.IsNotLinked property

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία δεν είναι συνδεδεμένη.

```csharp
public bool IsNotLinked { get; set; }
```

### Αξία περιουσίας

`αληθής` εάν αυτή η περίπτωση δεν είναι συνδεδεμένη. σε διαφορετική περίπτωση,`ψευδής` .

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

* interface [IVectorPathData](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Core.VectorPaths](../../ivectorpathdata/)
* συνέλευση [Aspose.PSD](../../../)


