---
title: StreamSource.StreamSource
second_title: Aspose.PSD για Αναφορά API .NET
description: StreamSource κατασκευαστής. Αρχικοποιεί μια νέα παρουσία τουStreamSource τάξη.
type: docs
weight: 10
url: /el/net/aspose.psd.sources/streamsource/streamsource/
---
## StreamSource(Stream) {#constructor}

Αρχικοποιεί μια νέα παρουσία του[`StreamSource`](../) τάξη.

```csharp
public StreamSource(Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Το ρεύμα να ανοίξει. |

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

* class [StreamSource](../)
* χώρος ονομάτων [Aspose.PSD.Sources](../../streamsource/)
* συνέλευση [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

Αρχικοποιεί μια νέα παρουσία του[`StreamSource`](../) τάξη.

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Το ρεύμα να ανοίξει. |
| disposeStream | Boolean | εάν έχει οριστεί σε`αληθής` το ρέμα θα απορριφθεί. |

### Παραδείγματα

Αυτό το παράδειγμα δείχνει τη χρήση του System.IO.Stream για τη δημιουργία ενός νέου αρχείου εικόνας

```csharp
[C#]

//Δημιουργεί μια παρουσία του PsdOptions και ορίζει τις διάφορες ιδιότητές του
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Δημιουργήστε μια παρουσία του System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Ορίστε την ιδιότητα προέλευσης για την παρουσία του PsdOptions
//Η δεύτερη δυαδική παράμετρος καθορίζει εάν η ροή απορρίπτεται μόλις βγει από το πεδίο εφαρμογής
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Δημιουργεί μια παρουσία της εικόνας και καλεί τη μέθοδο Create με το PsdOptions ως παράμετρο για την προετοιμασία του αντικειμένου εικόνας   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //Κάνε κάποια επεξεργασία εικόνας
}
```

### Δείτε επίσης

* class [StreamSource](../)
* χώρος ονομάτων [Aspose.PSD.Sources](../../streamsource/)
* συνέλευση [Aspose.PSD](../../../)


