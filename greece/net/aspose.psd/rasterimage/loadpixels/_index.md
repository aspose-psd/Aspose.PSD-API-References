---
title: RasterImage.LoadPixels
second_title: Aspose.PSD για Αναφορά API .NET
description: RasterImage μέθοδος. Φορτώνει pixel.
type: docs
weight: 400
url: /el/net/aspose.psd/rasterimage/loadpixels/
---
## RasterImage.LoadPixels method

Φορτώνει pixel.

```csharp
public Color[] LoadPixels(Rectangle rectangle)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | Rectangle | Το ορθογώνιο από το οποίο φορτώνονται τα εικονοστοιχεία. |

### Επιστρεφόμενη Αξία

Ο φορτωμένος πίνακας pixel.

### Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς μπορείτε να φορτώσετε πληροφορίες εικονοστοιχείων σε έναν πίνακα τύπου χρώματος, να χειριστείτε τον πίνακα και να τον επαναφέρετε στην εικόνα. Για να εκτελέσετε αυτές τις λειτουργίες, αυτό το παράδειγμα δημιουργεί ένα νέο αρχείο εικόνας (σε μορφή PSD) χρησιμοποιώντας το αντικείμενο MemoryStream.

```csharp
[C#]

//Δημιουργήστε μια παρουσία του MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Δημιουργήστε μια παρουσία του PsdOptions και ορίστε τις διάφορες ιδιότητές του, συμπεριλαμβανομένης της ιδιότητας Source
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Δημιουργία μιας παρουσίας εικόνας
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Λάβετε τα pixel της εικόνας καθορίζοντας την περιοχή ως όριο εικόνας
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Κάντε βρόχο πάνω από τον πίνακα και ορίζει το χρώμα του εναλλακτικού εικονοστοιχείου με ευρετήριο
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Ρυθμίστε το χρώμα του εικονοστοιχείου με ευρετήριο σε κίτρινο
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Ρυθμίστε το χρώμα του εικονοστοιχείου με ευρετήριο σε μπλε
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Εφαρμογή των αλλαγών pixel στην εικόνα
        image.SavePixels(image.Bounds, pixels);

        // αποθήκευση όλων των αλλαγών.
        image.Save();
    }

    //Εγγραφή MemoryStream σε Αρχείο
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Δείτε επίσης

* struct [Color](../../color/)
* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* χώρος ονομάτων [Aspose.PSD](../../rasterimage/)
* συνέλευση [Aspose.PSD](../../../)


