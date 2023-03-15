---
title: Class WorkingPathResource
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Resources.WorkingPathResource τάξη. Πόρος διαδρομής εργασίας.
type: docs
weight: 3980
url: /el/net/aspose.psd.fileformats.psd.resources/workingpathresource/
---
## WorkingPathResource class

Πόρος διαδρομής εργασίας.

```csharp
public sealed class WorkingPathResource : ResourceBlock, IVectorPathData
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [WorkingPathResource](workingpathresource/)(byte[]) | Αρχικοποιεί μια νέα παρουσία του`WorkingPathResource` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/workingpathresource/datasize/) { get; } | Λαμβάνει το μέγεθος δεδομένων πόρων σε byte. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό για τον πόρο. |
| [IsDisabled](../../aspose.psd.fileformats.psd.resources/workingpathresource/isdisabled/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι απενεργοποιημένη. |
| [IsInverted](../../aspose.psd.fileformats.psd.resources/workingpathresource/isinverted/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ανεστραμμένη. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.resources/workingpathresource/isnotlinked/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία δεν είναι συνδεδεμένη. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/workingpathresource/minimalversion/) { get; } | Αποκτά την ελάχιστη απαιτούμενη έκδοση PSD. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα του πόρου. Συμβολοσειρά Pascal, με επένδυση για να κάνει το μέγεθος ίσο (ένα null όνομα αποτελείται από δύο byte του 0). |
| [Paths](../../aspose.psd.fileformats.psd.resources/workingpathresource/paths/) { get; set; } | Λαμβάνει ή ορίζει τις εγγραφές διαδρομής. |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Λαμβάνει την υπογραφή του πόρου. Θα πρέπει να είναι πάντα '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Λαμβάνει το μέγεθος του μπλοκ πόρων σε byte συμπεριλαμβανομένων των δεδομένων του. |
| [Version](../../aspose.psd.fileformats.psd.resources/workingpathresource/version/) { get; set; } | Λαμβάνει ή ορίζει την έκδοση. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Αποθηκεύει το μπλοκ πόρων στην καθορισμένη ροή. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Επικυρώνει τις τιμές των πόρων. |

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

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* συνέλευση [Aspose.PSD](../../)


