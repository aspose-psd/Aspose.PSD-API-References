---
title: "Κλάση WorkingPathResource"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Resources.WorkingPathResource κλάση. Πόρος διαδρομής εργασίας"
type: docs
weight: 4450
url: /el/net/aspose.psd.fileformats.psd.resources/workingpathresource/
---
{{< psd/tize >}}
## WorkingPathResource class

Πόρος διαδρομής εργασίας.

```csharp
public sealed class WorkingPathResource : ResourceBlock, IVectorPathData
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [WorkingPathResource](workingpathresource/)(byte[]) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `WorkingPathResource`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/workingpathresource/datasize/) { get; } | Λαμβάνει το μέγεθος δεδομένων του πόρου σε byte. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό για τον πόρο. |
| [IsDisabled](../../aspose.psd.fileformats.psd.resources/workingpathresource/isdisabled/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι απενεργοποιημένη. |
| [IsInverted](../../aspose.psd.fileformats.psd.resources/workingpathresource/isinverted/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι ανεστραμμένη. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.resources/workingpathresource/isnotlinked/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτή η παρουσία δεν είναι συνδεδεμένη. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/workingpathresource/minimalversion/) { get; } | Λαμβάνει την ελάχιστη απαιτούμενη έκδοση PSD. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα του πόρου. Συμβολοσειρά Pascal, συμπληρωμένη ώστε το μέγεθος να είναι άρτιο (ένα κενό όνομα αποτελείται από δύο byte του 0). |
| [Paths](../../aspose.psd.fileformats.psd.resources/workingpathresource/paths/) { get; set; } | Λαμβάνει ή ορίζει τις εγγραφές διαδρομής. |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Λαμβάνει την υπογραφή του πόρου. Πρέπει πάντα να είναι '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Λαμβάνει το μέγεθος του μπλοκ πόρου σε byte, συμπεριλαμβανομένων των δεδομένων του. |
| [Version](../../aspose.psd.fileformats.psd.resources/workingpathresource/version/) { get; set; } | Λαμβάνει ή ορίζει την έκδοση. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Αποθηκεύει το μπλοκ πόρου στο καθορισμένο ρεύμα. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Επικυρώνει τις τιμές του πόρου. |

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

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


