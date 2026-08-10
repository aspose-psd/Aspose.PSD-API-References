---
title: "StreamSource.StreamSource"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κατασκευαστής StreamSource. Αρχικοποιεί ένα νέο αντικείμενο της κλάσης StreamSource"
type: docs
weight: 10
url: /el/net/aspose.psd.sources/streamsource/streamsource/
---
{{< psd/tize >}}
## StreamSource(Stream) {#constructor}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`StreamSource`](../).

```csharp
public StreamSource(Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή προς άνοιγμα. |

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

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`StreamSource`](../).

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή προς άνοιγμα. |
| disposeStream | Boolean | αν οριστεί σε `true` η ροή θα απορριφθεί. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει τη χρήση του System.IO.Stream για τη δημιουργία ενός νέου αρχείου Image.

```csharp
[C#]

//Δημιουργεί μια παρουσία του PsdOptions και ορίζει τις διάφορες ιδιότητές του.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Δημιουργήστε μια παρουσία του System.IO.Stream.
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Ορίστε την ιδιότητα source για την παρουσία του PsdOptions.
//Η δεύτερη παράμετρος boolean καθορίζει εάν το Stream θα απελευθερωθεί μόλις βγει εκτός εμβέλειας.
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Δημιουργεί μια παρουσία του Image και καλεί τη μέθοδο Create με το PsdOptions ως παράμετρο για την αρχικοποίηση του αντικειμένου Image.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //κάντε κάποια επεξεργασία εικόνας
}
```

### Δείτε επίσης

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


