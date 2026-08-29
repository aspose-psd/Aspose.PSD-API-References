---
title: "Image.Create"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος Image. Δημιουργεί μια νέα εικόνα χρησιμοποιώντας τις καθορισμένες επιλογές δημιουργίας"
type: docs
weight: 10
url: /el/net/aspose.psd/image/create/
---
{{< psd/tize >}}
## Image.Create method

Δημιουργεί μια νέα εικόνα χρησιμοποιώντας τις καθορισμένες επιλογές δημιουργίας.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | Οι επιλογές εικόνας. |
| πλάτος | Int32 | Το πλάτος. |
| ύψος | Int32 | Το ύψος. |

### Τιμή Επιστροφής

Η νεοδημιουργημένη εικόνα.

## Παραδείγματα

Αυτό το παράδειγμα δημιουργεί ένα νέο αρχείο Image σε κάποια θέση δίσκου όπως καθορίζεται από την ιδιότητα Source του αντικειμένου PsdOptions. Πολλές ιδιότητες του αντικειμένου PsdOptions ορίζονται πριν δημιουργηθεί η πραγματική εικόνα. Ιδιαίτερα η ιδιότητα Source, που αναφέρεται στην πραγματική θέση δίσκου σε αυτή την περίπτωση.

```csharp
[C#]

//Δημιουργήστε ένα στιγμιότυπο του PsdOptions και ορίστε τις διάφορες ιδιότητές του
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Δημιουργήστε ένα στιγμιότυπο του FileCreateSource και αναθέστε το ως Source για το στιγμιότυπο του PsdOptions
//Η δεύτερη παράμετρος Boolean καθορίζει εάν το αρχείο που θα δημιουργηθεί είναι IsTemporal ή όχι
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Δημιουργήστε ένα στιγμιότυπο του Image και αρχικοποιήστε το με το στιγμιότυπο του PsdOptions καλώντας τη μέθοδο Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //κάντε κάποια επεξεργασία εικόνας

    // αποθηκεύστε όλες τις αλλαγές
    image.Save();
}
```

### Δείτε επίσης

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


