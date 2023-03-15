---
title: Class Cache
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.Cache τάξη. Περιέχει ρυθμίσεις κρυφής μνήμης.
type: docs
weight: 240
url: /el/net/aspose.psd/cache/
---
## Cache class

Περιέχει ρυθμίσεις κρυφής μνήμης.

```csharp
public static class Cache
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | Λαμβάνει τον εκχωρημένο αριθμό byte του δίσκου. |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | Λαμβάνει τον εκχωρημένο αριθμό byte στη μνήμη. |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | Λαμβάνει ή ορίζει το φάκελο της προσωρινής μνήμης. |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | Λαμβάνει ή ορίζει το χρησιμοποιούμενο σχήμα κρυφής μνήμης. |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η ανακατανομή πρέπει να είναι ακριβής ή όχι. Εάν η ανακατανομή δεν είναι ακριβής, η απόδοση θα πρέπει να είναι υψηλότερη. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | Λαμβάνει ή ορίζει το μέγιστο διαθέσιμο χώρο στο δίσκο για την προσωρινή μνήμη. Η τιμή που καθορίστηκε είναι πλήθος megabyte. |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | Λαμβάνει ή ορίζει τη μέγιστη διαθέσιμη μνήμη για προσωρινή μνήμη στη μνήμη. Η τιμή που καθορίστηκε είναι πλήθος megabyte. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | Ορίζει το`Cache` ρυθμίσεις στις προεπιλογές. |

### Παραδείγματα

Αυτό το παράδειγμα δείχνει τη χρήση του Aspose.PSD.Cache

```csharp
[C#]

// Από προεπιλογή ο φάκελος της προσωρινής μνήμης έχει οριστεί στον τοπικό προσωρινό κατάλογο του χρήστη.
// Μπορείτε επίσης να καθορίσετε έναν άλλο φάκελο κρυφής μνήμης από τον προεπιλεγμένο, όπως το ακόλουθο:
// Cache.CacheFolder = @"D:\\MyTemp";

string path = "C:\\temp\\image.psd";

// Η αυτόματη λειτουργία είναι ευέλικτη και αποτελεσματική
Cache.CacheType = CacheType.Auto;

// Η προεπιλεγμένη τιμή είναι 0, που σημαίνει ότι δεν υπάρχει ανώτατο όριο
Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// Δεν συνιστάται η αλλαγή της ακόλουθης ιδιότητας, καθώς μπορεί να επηρεάσει σημαντικά την απόδοση
Cache.ExactReallocateOnly = false;

// Ανά πάσα στιγμή μπορείτε να ελέγξετε πόσα byte έχουν εκχωρηθεί για τη μνήμη ή το δίσκο 
// cache εξετάζοντας τις ακόλουθες ιδιότητες
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

    // μετά την εκτέλεση του παραπάνω κώδικα θα εκχωρηθούν 40000 byte στη μνήμη.
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// Οι ιδιότητες εκχώρησης μπορούν να χρησιμοποιηθούν για να ελεγχθεί εάν όλα τα αντικείμενα Aspose.PSD διατέθηκαν σωστά.
// Σε περίπτωση που ξεχάσατε να καλέσετε το dispose σε κάποιο αντικείμενο, οι τιμές της κρυφής μνήμης θα είναι διαφορετικές από 0.            
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD](../../aspose.psd/)
* συνέλευση [Aspose.PSD](../../)


