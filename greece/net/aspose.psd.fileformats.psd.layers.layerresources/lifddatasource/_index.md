---
title: "Κλάση LiFdDataSource"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LiFdDataSource κλάση. Ορίζει την κλάση πηγής δεδομένων liFD στο αρχείο PSD που περιέχει πληροφορίες για ένα ενσωματωμένο αρχείο. Αυτό είναι μέρος του API Διαχείρισης Μορφής Αρχείου PSD που βοηθά στην τροποποίηση αρχείων Adobe Photoshop"
type: docs
weight: 2970
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/
---
{{< psd/tize >}}
## LiFdDataSource class

Ορίζει την κλάση πηγής δεδομένων liFD στο αρχείο PSD που περιέχει πληροφορίες σχετικά με ένα ενσωματωμένο αρχείο. Αυτό αποτελεί μέρος του API Διαχείρισης Μορφής Αρχείου PSD που βοηθά στην τροποποίηση αρχείων Adobe® Photoshop®.

```csharp
public class LiFdDataSource : LinkDataSource
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [LiFdDataSource](lifddatasource/#constructor)() | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `LiFdDataSource`. |
| [LiFdDataSource](lifddatasource/#constructor_1)(int, Guid, string, string, string) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `LiFdDataSource`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το στοιχείο PSD είναι κλειδωμένο. Η κατάσταση κλειδώματος του στοιχείου, για στοιχεία Adobe® Photoshop® СС Libraries. |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime/) { get; set; } | Λαμβάνει ή ορίζει την ώρα τροποποίησης του στοιχείου, για στοιχεία Adobe® Photoshop® СС Libraries. |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid/) { get; set; } | Λαμβάνει ή ορίζει το αναγνωριστικό του θυγατρικού εγγράφου στην πηγή δεδομένων liFE ή liFD του πόρου Lnk2 / LnkE Adobe® Photoshop®. |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid/) { get; set; } | Λαμβάνει ή ορίζει το αναγνωριστικό του τρέχοντος επιλεγμένου comp για το θυγατρικό έγγραφο, το οποίο θα είναι -1 εάν δεν υπάρχει επιλογή. Τα comps είναι συνθέσεις μιας διάταξης σελίδας που μπορούν να δημιουργήσουν οι σχεδιαστές. Χρησιμοποιώντας layer comps, μπορείτε να δημιουργήσετε, να διαχειριστείτε και να προβάλετε πολλαπλές εκδόσεις μιας διάταξης σε ένα μόνο αρχείο Adobe® Photoshop®. Ένα layer comp είναι ένα στιγμιότυπο μιας κατάστασης του πίνακα Layers. Τα layer comps αποθηκεύουν τρεις τύπους επιλογών στρώσης, αλλά αυτή η ιδιότητα λαμβάνει το αναγνωριστικό επιλογής Layer Comp για Smart Objects. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Data](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) { get; set; } | Ανακτά ή ορίζει τα ενσωματωμένα δεδομένα έξυπνου αντικειμένου σε αρχείο PSD. |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator/) { get; set; } | Λαμβάνει ή ορίζει τον δημιουργό του αρχείου στη μορφή PSD πόρου LnkE / Lnk2. |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο του ενσωματωμένου ή εξωτερικού αρχείου που περιέχει ή συνδέει ο πόρος Adobe® Photoshop® Lnk2 / LnkE. |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η πηγή δεδομένων σύνδεσης έχει τον περιγραφέα ανοικτού αρχείου: CompId και OriginalCompId. |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η πηγή δεδομένων σύνδεσης PSD συνδέεται με το στοιχείο Adobe® Photoshop® СС Library. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length/) { get; } | Λαμβάνει το μήκος της πηγής δεδομένων σύνδεσης σε bytes. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid/) { get; } | Λαμβάνει το αρχικό αναγνωριστικό του τρέχοντος επιλεγμένου Comp για το θυγατρικό έγγραφο, το οποίο θα είναι -1 εάν δεν υπάρχει επιλογή. Αυτή η ιδιότητα λαμβάνει το αρχικό αναγνωριστικό επιλογής layer Comp για Smart Objects. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename/) { get; } | Λαμβάνει το αρχικό όνομα αρχείου της πηγής δεδομένων στον παγκόσμιο πόρο σύνδεσης Adobe® Photoshop®. |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type/) { get; } | Λαμβάνει τον τύπο της παγκόσμιας πηγής δεδομένων σύνδεσης Adobe® Photoshop® που μπορεί να είναι ένας από τους παρακάτω ή κανένας: Το ενσωματωμένο συνδεδεμένο αρχείο liFD που αντιστοιχεί στον πόρο PSD Lnk2Resource, Το εξωτερικό συνδεδεμένο αρχείο liFE που αντιστοιχεί στον πόρο PSD LnkeResource, Το ψευδώνυμο συνδεδεμένου αρχείου liFA. |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid/) { get; } | Λαμβάνει το παγκόσμιο μοναδικό αναγνωριστικό της πηγής δεδομένων στον πόρο σύνδεσης PSD. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version/) { get; } | Λαμβάνει την έκδοση της πηγής δεδομένων στον πόρο PSD LnkE / Lnk2. |

### Δείτε επίσης

* class [LinkDataSource](../linkdatasource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


