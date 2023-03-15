---
title: Image.Create
second_title: Aspose.PSD για Αναφορά API .NET
description: Image μέθοδος. Δημιουργεί μια νέα εικόνα χρησιμοποιώντας τις καθορισμένες επιλογές δημιουργίας.
type: docs
weight: 10
url: /el/net/aspose.psd/image/create/
---
## Image.Create method

Δημιουργεί μια νέα εικόνα χρησιμοποιώντας τις καθορισμένες επιλογές δημιουργίας.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | Οι επιλογές εικόνας. |
| width | Int32 | Το πλάτος. |
| height | Int32 | Το ύψος. |

### Επιστρεφόμενη Αξία

Η νέα εικόνα.

### Παραδείγματα

Αυτό το παράδειγμα δημιουργεί ένα νέο αρχείο εικόνας σε κάποια θέση δίσκου, όπως καθορίζεται από την ιδιότητα Source της παρουσίας PsdOptions. Ορίζονται πολλές ιδιότητες για την παρουσία PsdOptions πριν από τη δημιουργία της πραγματικής εικόνας. Ειδικά η ιδιότητα Source, που αναφέρεται στην πραγματική θέση του δίσκου σε αυτήν την περίπτωση.

```csharp
[C#]

//Δημιουργήστε μια παρουσία του PsdOptions και ορίστε τις διάφορες ιδιότητές του
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Δημιουργήστε μια παρουσία του FileCreateSource και αντιστοιχίστε την ως πηγή για την παρουσία του PsdOptions
//Δεύτερη παράμετρος Boolean καθορίζει εάν το αρχείο που θα δημιουργηθεί είναι Temporal ή όχι
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Δημιουργήστε μια παρουσία της εικόνας και αρχικοποιήστε την με την παρουσία της PsdOptions καλώντας τη μέθοδο Δημιουργία
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //Κάνε κάποια επεξεργασία εικόνας

    // αποθήκευση όλων των αλλαγών
    image.Save();
}
```

### Δείτε επίσης

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* χώρος ονομάτων [Aspose.PSD](../../image/)
* συνέλευση [Aspose.PSD](../../../)


