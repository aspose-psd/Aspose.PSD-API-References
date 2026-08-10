---
title: "IVectorPathData.IsDisabled"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα IVectorPathData. Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι απενεργοποιημένη"
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/
---
{{< psd/tize >}}
## IVectorPathData.IsDisabled property

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι απενεργοποιημένη.

```csharp
public bool IsDisabled { get; set; }
```

### Property Value

`true` εάν αυτή η παρουσία είναι απενεργοποιημένη· διαφορετικά, `false`.

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

* interface [IVectorPathData](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


