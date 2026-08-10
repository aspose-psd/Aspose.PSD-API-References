---
title: "AiImage.ActivePageIndex"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "AiImage property. Λαμβάνει ή ορίζει το δείκτη της ενεργής σελίδας"
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.ai/aiimage/activepageindex/
---
{{< psd/tize >}}
## AiImage.ActivePageIndex property

Λαμβάνει ή ορίζει το δείκτη της ενεργής σελίδας.

```csharp
public int ActivePageIndex { get; set; }
```

### Property Value

Αυτή η ιδιότητα ισχύει μόνο για εικόνα AI σε μορφή PDF. Εάν η εικόνα δεν είναι σε μορφή PDF ή δεν υπάρχουν σελίδες, η ιδιότητα θα είναι -1. Αυτή η ιδιότητα δείχνει ποια σελίδα της εικόνας AI θα χρησιμοποιηθεί ως βάση για την απόδοση.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη της δυνατότητας αλλαγής της ενεργής σελίδας σε εικόνες Ai.

```csharp
[C#]

string sourceFile = "threePages.ai";
string firstPageOutputPng = "firstPageOutput.png";
string secondPageOutputPng = "secondPageOutput.png";
string thirdPageOutputPng = "thirdPageOutput.png";

// Φορτώστε την εικόνα AI.
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    // Από προεπιλογή, το ActivePageIndex είναι 0.
    // Έτσι, εάν αποθηκεύσετε την εικόνα AI χωρίς να αλλάξετε αυτή την ιδιότητα, η πρώτη σελίδα θα αποδοθεί και θα αποθηκευτεί.
    image.Save(firstPageOutputPng, new PngOptions());

    // Αλλάξτε το δείκτη της ενεργής σελίδας στη δεύτερη σελίδα.
    image.ActivePageIndex = 1;

    // Αποθηκεύστε τη δεύτερη σελίδα της εικόνας AI ως εικόνα PNG.
    image.Save(secondPageOutputPng, new PngOptions());

    // Αλλάξτε το δείκτη της ενεργής σελίδας στην τρίτη σελίδα.
    image.ActivePageIndex = 2;

    // Αποθηκεύστε την τρίτη σελίδα της εικόνας AI ως εικόνα PNG.
    image.Save(thirdPageOutputPng, new PngOptions());
}
```

### Δείτε επίσης

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


