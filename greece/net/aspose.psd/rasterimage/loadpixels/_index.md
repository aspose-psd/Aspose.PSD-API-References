---
title: "RasterImage.LoadPixels"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος RasterImage. Φορτώνει εικονοστοιχεία"
type: docs
weight: 410
url: /el/net/aspose.psd/rasterimage/loadpixels/
---
{{< psd/tize >}}
## RasterImage.LoadPixels method

Φορτώνει εικονοστοιχεία.

```csharp
public Color[] LoadPixels(Rectangle rectangle)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ορθογώνιο | Rectangle | Το ορθογώνιο από το οποίο θα φορτωθούν τα εικονοστοιχεία. |

### Τιμή Επιστροφής

Ο πίνακας φορτωμένων εικονοστοιχείων.

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να φορτώνει πληροφορίες Pixel σε έναν Πίνακα τύπου Color, να επεξεργάζεται τον πίνακα και να τον επαναφέρει στην εικόνα. Για την εκτέλεση αυτών των λειτουργιών, αυτό το παράδειγμα δημιουργεί ένα νέο αρχείο Image (σε μορφή PSD) χρησιμοποιώντας το αντικείμενο MemoryStream.

```csharp
[C#]

//Δημιουργήστε ένα στιγμιότυπο του MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Δημιουργήστε ένα στιγμιότυπο του PsdOptions και ορίστε τις διάφορες ιδιότητές του, συμπεριλαμβανομένης της ιδιότητας Source
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Δημιουργήστε ένα στιγμιότυπο του Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Αποκτήστε τα pixel της εικόνας καθορίζοντας την περιοχή ως όριο της εικόνας
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Επανάληψη πάνω στον πίνακα και ορίζει το χρώμα του εναλλακτικού ευρετηριασμένου pixel
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Ορίστε το χρώμα του ευρετηριασμένου pixel σε κίτρινο
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Ορίστε το χρώμα του ευρετηριασμένου pixel σε μπλε
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Εφαρμόστε τις αλλαγές pixel στην εικόνα
        image.SavePixels(image.Bounds, pixels);

        // αποθηκεύστε όλες τις αλλαγές.
        image.Save();
    }

    //Γράψτε το MemoryStream σε αρχείο
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Δείτε επίσης

* struct [Color](../../color/)
* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


