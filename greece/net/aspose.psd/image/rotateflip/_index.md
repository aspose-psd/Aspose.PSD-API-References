---
title: "Image.RotateFlip"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος Image. Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα"
type: docs
weight: 230
url: /el/net/aspose.psd/image/rotateflip/
---
{{< psd/tize >}}
## Image.RotateFlip method

Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Τύπος της περιστροφής/αναστροφής. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει τη χρήση της λειτουργίας Rotate σε μια εικόνα. Το παράδειγμα φορτώνει ένα υπάρχον αρχείο εικόνας από κάποια τοποθεσία δίσκου και εκτελεί τη λειτουργία Rotate στην εικόνα σύμφωνα με την τιμή του Enum Aspose.PSD.RotateFlipType

```csharp
[C#]

//Δημιουργήστε μια παρουσία της κλάσης image και αρχικοποιήστε την με ένα υπάρχον αρχείο εικόνας μέσω της διαδρομής αρχείου
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Περιστρέψτε την εικόνα κατά 180 μοίρες γύρω από τον άξονα X
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // αποθηκεύστε όλες τις αλλαγές.
    image.Save();
}
```

### Δείτε επίσης

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


