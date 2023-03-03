---
title: Image.RotateFlip
second_title: Aspose.PSD για Αναφορά API .NET
description: Image μέθοδος. Περιστρέφει αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα.
type: docs
weight: 220
url: /el/net/aspose.psd/image/rotateflip/
---
## Image.RotateFlip method

Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Τύπος περιστροφής. |

### Παραδείγματα

Αυτό το παράδειγμα δείχνει τη χρήση της λειτουργίας Περιστροφή σε μια εικόνα. Το Παράδειγμα φορτώνει ένα υπάρχον αρχείο εικόνας από κάποια θέση δίσκου και εκτελεί τη λειτουργία Περιστροφή στην εικόνα σύμφωνα με την τιμή του Enum Aspose.PSD.RotateFlipType

```csharp
[C#]

//Δημιουργήστε μια παρουσία κλάσης εικόνας και αρχικοποιήστε την με ένα υπάρχον αρχείο εικόνας μέσω της διαδρομής αρχείου
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Περιστροφή της εικόνας κατά 180 μοίρες γύρω από τον άξονα Χ
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // αποθήκευση όλων των αλλαγών.
    image.Save();
}
```

### Δείτε επίσης

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* χώρος ονομάτων [Aspose.PSD](../../image/)
* συνέλευση [Aspose.PSD](../../../)


