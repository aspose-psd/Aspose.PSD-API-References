---
title: "FileCreateSource.FileCreateSource"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "FileCreateSource κατασκευαστής. Αρχικοποιεί μια νέα παρουσία της κλάσης FileCreateSource"
type: docs
weight: 10
url: /el/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource(string) {#constructor}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`FileCreateSource`](../).

```csharp
public FileCreateSource(string filePath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου για δημιουργία. |

## Παραδείγματα

Αυτό το παράδειγμα δημιουργεί ένα νέο αρχείο Image σε κάποια θέση δίσκου όπως ορίζεται από την ιδιότητα Source της παρουσίας BmpOptions. Εάν δεν περαστεί το δεύτερο παράμετρος στον κατασκευαστή του FileCreateSource, τότε εξ ορισμού το αρχείο που θα δημιουργηθεί έχει την ιδιότητα IsTemporal ορισμένη σε True. Με το IsTemporal ορισμένο σε True, κανένα αρχείο δεν θα αποθηκευτεί στον δίσκο στο τέλος της εκτέλεσης.

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//Δημιουργεί μια παρουσία του PsdOptions και ορίζει τις διάφορες ιδιότητές του.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Δημιουργήστε ένα στιγμιότυπο του FileCreateSource και αναθέστε το ως Source για το στιγμιότυπο του PsdOptions
//Εάν δεν περαστεί το δεύτερο παράμετρος, τότε εξ ορισμού το αρχείο έχει το IsTemporal ορισμένο σε True
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

//Δημιουργεί μια παρουσία του Image 
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //κάντε κάποια επεξεργασία εικόνας
}
```

### Δείτε επίσης

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`FileCreateSource`](../).

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου για δημιουργία. |
| isTemporal | Boolean | Εάν οριστεί σε `true` το δημιουργημένο αρχείο θα είναι προσωρινό. |

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

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


