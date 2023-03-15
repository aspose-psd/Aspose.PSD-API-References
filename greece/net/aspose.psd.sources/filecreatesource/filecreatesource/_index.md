---
title: FileCreateSource.FileCreateSource
second_title: Aspose.PSD για Αναφορά API .NET
description: FileCreateSource κατασκευαστής. Αρχικοποιεί μια νέα παρουσία τουFileCreateSource τάξη.
type: docs
weight: 10
url: /el/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
## FileCreateSource(string) {#constructor}

Αρχικοποιεί μια νέα παρουσία του[`FileCreateSource`](../) τάξη.

```csharp
public FileCreateSource(string filePath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου προς δημιουργία. |

### Παραδείγματα

Αυτό το παράδειγμα δημιουργεί ένα νέο αρχείο εικόνας σε κάποια θέση δίσκου, όπως καθορίζεται από την ιδιότητα Source της παρουσίας BmpOptions. Εάν η δεύτερη παράμετρος δεν μεταβιβαστεί στον κατασκευαστή του FileCreateSource, τότε από προεπιλογή το αρχείο που θα δημιουργηθεί έχει την ιδιότητα IsTemporal που έχει οριστεί σε True. Όταν το IsTemporal έχει οριστεί σε True, κανένα αρχείο δεν θα αποθηκευτεί στο δίσκο στο τέλος της εκτέλεσης.

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//Δημιουργεί μια παρουσία του PsdOptions και ορίζει τις διάφορες ιδιότητές του
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Δημιουργήστε μια παρουσία του FileCreateSource και αντιστοιχίστε την ως πηγή για την παρουσία του PsdOptions
//Εάν η δεύτερη παράμετρος δεν μεταβιβαστεί, τότε από προεπιλογή το αρχείο έχει IsTemporal οριστεί σε True
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

//Δημιουργεί μια παρουσία εικόνας 
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //Κάνε κάποια επεξεργασία εικόνας
}
```

### Δείτε επίσης

* class [FileCreateSource](../)
* χώρος ονομάτων [Aspose.PSD.Sources](../../filecreatesource/)
* συνέλευση [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

Αρχικοποιεί μια νέα παρουσία του[`FileCreateSource`](../) τάξη.

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου προς δημιουργία. |
| isTemporal | Boolean | Εάν έχει οριστεί σε`αληθής` το αρχείο που δημιουργήθηκε θα είναι προσωρινό. |

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

* class [FileCreateSource](../)
* χώρος ονομάτων [Aspose.PSD.Sources](../../filecreatesource/)
* συνέλευση [Aspose.PSD](../../../)


