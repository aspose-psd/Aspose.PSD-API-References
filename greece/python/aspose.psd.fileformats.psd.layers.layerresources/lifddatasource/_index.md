---
title: "Κλάση LiFdDataSource"
type: docs
weight: 510
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/
---

**Summary:** Defines the liFD data source class in PSD File that contains information about an embedded file.<br/>            This is part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LiFdDataSource

**Inheritance:** LinkDataSource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [LiFdDataSource()](#LiFdDataSource__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/). |
| [LiFdDataSource(version, unique_id, original_file_name, file_type, file_creator)](#LiFdDataSource_version_unique_id_original_file_name_file_type_file_creator_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| asset_locked_state | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το περιουσιακό στοιχείο PSD είναι κλειδωμένο.<br/>            Η κατάσταση κλειδώματος του περιουσιακού στοιχείου, για τα περιουσιακά στοιχεία των βιβλιοθηκών Adobe® Photoshop® СС. |
| asset_mod_time | double | r/w | Λαμβάνει ή ορίζει την ώρα τροποποίησης του περιουσιακού στοιχείου, για τα περιουσιακά στοιχεία των βιβλιοθηκών Adobe® Photoshop® СС. |
| child_doc_id | string | r/w | Λαμβάνει ή ορίζει το αναγνωριστικό του θυγατρικού εγγράφου στην πηγή δεδομένων liFE ή liFD του πόρου Lnk2 / LnkE Adobe® Photoshop®. |
| comp_id | int | r/w | Λαμβάνει ή ορίζει το ID του τρέχοντος επιλεγμένου comp για το θυγατρικό έγγραφο, το οποίο θα είναι -1 εάν δεν υπάρχει επιλογή.<br/>            Τα comps είναι συνθέσεις μιας διάταξης σελίδας που μπορούν να δημιουργήσουν οι σχεδιαστές. Χρησιμοποιώντας layer comps, μπορείτε να δημιουργήσετε, να διαχειριστείτε και να προβάλετε πολλαπλές εκδόσεις<br/>            μιας διάταξης σε ένα ενιαίο αρχείο Adobe® Photoshop®. Ένα layer comp είναι μια στιγμιότυπο μιας κατάστασης του πίνακα Layers. Τα layer comps αποθηκεύουν τρεις τύπους επιλογών στρώσεων, αλλά<br/>            αυτή η ιδιότητα λαμβάνει το αναγνωριστικό επιλογής Layer Comp για Smart Objects.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| δεδομένα | byte | r/w | Λαμβάνει ή ορίζει τα ενσωματωμένα δεδομένα έξυπνου αντικειμένου σε αρχείο PSD. |
| file_creator | string | r/w | Λαμβάνει ή ορίζει τον δημιουργό του αρχείου στη μορφή PSD του πόρου LnkE / Lnk2. |
| file_type | string | r/w | Λαμβάνει ή ορίζει τον τύπο του ενσωματωμένου ή εξωτερικού αρχείου που περιέχει ή συνδέει ο πόρος Adobe® Photoshop® Lnk2 / LnkE. |
| has_file_open_descriptor | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η πηγή δεδομένων συνδέσμου έχει τον περιγραφέα ανοικτού αρχείου: CompId και OriginalCompId. |
| is_library_link | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η πηγή δεδομένων συνδέσμου PSD συνδέεται με το στοιχείο της βιβλιοθήκης Adobe® Photoshop® СС. |
| μήκος | long | r | Λαμβάνει το μήκος της πηγής δεδομένων του συνδέσμου σε byte. |
| original_comp_id | int | r | Λαμβάνει το αρχικό ID του τρέχοντος επιλεγμένου Comp για το υπο-έγγραφο, το οποίο θα είναι -1 εάν δεν υπάρχει επιλογή.<br/>            Αυτή η ιδιότητα λαμβάνει το αρχικό αναγνωριστικό επιλογής layer Comp για Smart Objects.<br/>            <see href=\"https://helpx.adobe.com/photoshop/using/layer-comps.html\">Layer comps in Smart Objects</see> |
| original_file_name | string | r | Λαμβάνει το αρχικό όνομα αρχείου της πηγής δεδομένων στον παγκόσμιο πόρο συνδέσμου του Adobe® Photoshop®. |
| type | [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype) | r | Λαμβάνει τον τύπο της παγκόσμιας πηγής δεδομένων συνδέσμου του Adobe® Photoshop® που μπορεί να είναι ένας από τους παρακάτω ή κανένας:<br/>            Το ενσωματωμένο συνδεδεμένο αρχείο liFD που αντιστοιχεί στο PSD Lnk2Resource<br/>            Το εξωτερικό συνδεδεμένο αρχείο liFE που αντιστοιχεί στο PSD LnkeResource<br/>            Το ψευδώνυμο συνδεδεμένου αρχείου liFA |
| unique_id | Guid | r | Λαμβάνει το παγκόσμιο μοναδικό αναγνωριστικό της πηγής δεδομένων στον πόρο συνδέσμου PSD. |
| version | int | r | Λαμβάνει την έκδοση της πηγής δεδομένων στον πόρο PSD LnkE / Lnk2. |


### Constructor: LiFdDataSource() {#LiFdDataSource__1}


```
 LiFdDataSource() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/).

### Constructor: LiFdDataSource(version, unique_id, original_file_name, file_type, file_creator) {#LiFdDataSource_version_unique_id_original_file_name_file_type_file_creator_2}


```
 LiFdDataSource(version, unique_id, original_file_name, file_type, file_creator) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| version | int | Η έκδοση. |
| unique_id | Guid | Το μοναδικό αναγνωριστικό. |
| original_file_name | string | Όνομα του αρχικού αρχείου. |
| file_type | string | Τύπος του αρχείου. |
| file_creator | string | Ο δημιουργός του αρχείου. |

