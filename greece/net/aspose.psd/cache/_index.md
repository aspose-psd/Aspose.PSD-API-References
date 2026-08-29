---
title: "Κλάση Cache"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.Cache κλάση. Περιέχει ρυθμίσεις κρυφής μνήμης."
type: docs
weight: 240
url: /el/net/aspose.psd/cache/
---
{{< psd/tize >}}
## Cache class

Περιέχει ρυθμίσεις cache.

```csharp
public static class Cache
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | Λαμβάνει τον αριθμό των εκχωρημένων byte δίσκου. |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | Λαμβάνει τον αριθμό των εκχωρημένων byte στη μνήμη. |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | Λαμβάνει ή ορίζει το φάκελο κρυφής μνήμης. |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | Λαμβάνει ή ορίζει το σχήμα κρυφής μνήμης που χρησιμοποιείται. |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν η επανακατανομή πρέπει να είναι ακριβής ή όχι. Εάν η επανακατανομή δεν είναι ακριβής, η απόδοση θα πρέπει να είναι υψηλότερη. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | Λαμβάνει ή ορίζει το μέγιστο διαθέσιμο χώρο δίσκου για την κρυφή μνήμη. Η καθορισμένη τιμή είναι αριθμός megabytes. |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | Λαμβάνει ή ορίζει τη μέγιστη διαθέσιμη μνήμη για την κρυφή μνήμη στη μνήμη. Η καθορισμένη τιμή είναι αριθμός megabytes. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | Ορίζει τις ρυθμίσεις του `Cache` στις προεπιλογές. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει τη χρήση του Aspose.PSD.Cache

```csharp
[C#]

// Από προεπιλογή, ο φάκελος κρυφής μνήμης ορίζεται στον τοπικό προσωρινό φάκελο του χρήστη.
// Μπορείτε επίσης να ορίσετε διαφορετικό φάκελο κρυφής μνήμης από την προεπιλογή, όπως το παρακάτω:
// Cache.CacheFolder = @\"D:\\\\MyTemp\";

string path = "C:\\temp\\image.psd";

// Η αυτόματη λειτουργία είναι ευέλικτη και αποδοτική
Cache.CacheType = CacheType.Auto;

// Η προεπιλεγμένη τιμή είναι 0, που σημαίνει ότι δεν υπάρχει ανώτερο όριο
Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// Δεν συνιστάται η αλλαγή της παρακάτω ιδιότητας, καθώς μπορεί να επηρεάσει σημαντικά την απόδοση
Cache.ExactReallocateOnly = false;

// Οποιαδήποτε στιγμή μπορείτε να ελέγξετε πόσα byte είναι αυτή τη στιγμή εκχωρημένα στη μνήμη ή στο δίσκο
// την κρυφή μνήμη εξετάζοντας τις παρακάτω ιδιότητες
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// Κάντε κάποια επεξεργασία εικόνας όπως παρακάτω
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // Μετά την εκτέλεση του παραπάνω κώδικα, θα εκχωρηθούν 40000 byte στη μνήμη.
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// Οι ιδιότητες κατανομής μπορούν να χρησιμοποιηθούν για να ελεγχθεί αν όλα τα αντικείμενα Aspose.PSD έχουν αποδεσμευτεί σωστά.
// Σε περίπτωση που ξεχάσατε να καλέσετε dispose σε κάποιο αντικείμενο, οι τιμές της κρυφής μνήμης θα είναι διαφορετικές από 0.
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### Δείτε επίσης

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


