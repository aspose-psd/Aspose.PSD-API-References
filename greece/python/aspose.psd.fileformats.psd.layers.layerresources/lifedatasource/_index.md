---
title: "LiFeDataSource Κλάση"
type: docs
weight: 520
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/
---

**Summary:** Defines the LnkeDataSource class that contains information about external linked file.<br/>            This is part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LiFeDataSource

**Inheritance:** LinkDataSource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [LiFeDataSource()](#LiFeDataSource__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/). |
| [LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator)](#LiFeDataSource_version_unique_id_original_file_name_file_type_file_creator_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| adobe_stock_id | string | r/w | Λαμβάνει ή ορίζει το AdobeStockId της βιβλιοθήκης γραφικών, για τις βιβλιοθήκες Adobe® Photoshop® CC. |
| adobe_stock_license_state | string | r | Λαμβάνει την κατάσταση της άδειας adobe stock εάν είναι διαθέσιμη, για τις βιβλιοθήκες Adobe® Photoshop® CC. |
| asset_locked_state | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το περιουσιακό στοιχείο PSD είναι κλειδωμένο.<br/>            Η κατάσταση κλειδώματος του περιουσιακού στοιχείου, για τα περιουσιακά στοιχεία των βιβλιοθηκών Adobe® Photoshop® СС. |
| asset_mod_time | double | r/w | Λαμβάνει ή ορίζει την ώρα τροποποίησης του περιουσιακού στοιχείου, για τα περιουσιακά στοιχεία των βιβλιοθηκών Adobe® Photoshop® СС. |
| child_doc_id | string | r/w | Λαμβάνει ή ορίζει το αναγνωριστικό του θυγατρικού εγγράφου στην πηγή δεδομένων liFE ή liFD του πόρου Lnk2 / LnkE Adobe® Photoshop®. |
| comp_id | int | r/w | Λαμβάνει ή ορίζει το ID του τρέχοντος επιλεγμένου comp για το θυγατρικό έγγραφο, το οποίο θα είναι -1 εάν δεν υπάρχει επιλογή.<br/>            Τα comps είναι συνθέσεις μιας διάταξης σελίδας που μπορούν να δημιουργήσουν οι σχεδιαστές. Χρησιμοποιώντας layer comps, μπορείτε να δημιουργήσετε, να διαχειριστείτε και να προβάλετε πολλαπλές εκδόσεις<br/>            μιας διάταξης σε ένα ενιαίο αρχείο Adobe® Photoshop®. Ένα layer comp είναι μια στιγμιότυπο μιας κατάστασης του πίνακα Layers. Τα layer comps αποθηκεύουν τρεις τύπους επιλογών στρώσεων, αλλά<br/>            αυτή η ιδιότητα λαμβάνει το αναγνωριστικό επιλογής Layer Comp για Smart Objects.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| date | datetime | r/w | Λαμβάνει ή ορίζει την ημερομηνία και ώρα τελευταίας εγγραφής του εξωτερικού αρχείου στην πηγή δεδομένων LiFE του πόρου PSD LnkE. |
| element_name | string | r/w | Λαμβάνει ή ορίζει το όνομα του στοιχείου της βιβλιοθήκης γραφικών, για τις βιβλιοθήκες Adobe® Photoshop® CC. |
| element_ref | string | r/w | Λαμβάνει ή ορίζει την αναφορά του στοιχείου της βιβλιοθήκης γραφικών, για τις βιβλιοθήκες Adobe® Photoshop® CC. |
| file_creator | string | r/w | Λαμβάνει ή ορίζει τον δημιουργό του αρχείου στη μορφή PSD του πόρου LnkE / Lnk2. |
| file_name | string | r/w | Λαμβάνει ή ορίζει το όνομα του εξωτερικού ή ενσωματωμένου αρχείου στον πόρο σύνδεσης PSD . |
| file_size | long | r/w | Λαμβάνει ή ορίζει το μέγεθος του εξωτερικού αρχείου στην πηγή δεδομένων LiFE του πόρου PSD LnkE. |
| file_type | string | r/w | Λαμβάνει ή ορίζει τον τύπο του ενσωματωμένου ή εξωτερικού αρχείου που περιέχει ή συνδέει ο πόρος Adobe® Photoshop® Lnk2 / LnkE. |
| full_path | string | r/w | Gets or sets the full path of the external file in the LiFE data source of the PSD LnkE resource. |
| has_file_open_descriptor | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η πηγή δεδομένων συνδέσμου έχει τον περιγραφέα ανοικτού αρχείου: CompId και OriginalCompId. |
| is_library_link | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η πηγή δεδομένων συνδέσμου PSD συνδέεται με το στοιχείο της βιβλιοθήκης Adobe® Photoshop® СС. |
| μήκος | long | r | Λαμβάνει το μήκος της πηγής δεδομένων του συνδέσμου σε byte. |
| original_comp_id | int | r | Λαμβάνει το αρχικό ID του τρέχοντος επιλεγμένου Comp για το υπο-έγγραφο, το οποίο θα είναι -1 εάν δεν υπάρχει επιλογή.<br/>            Αυτή η ιδιότητα λαμβάνει το αρχικό αναγνωριστικό επιλογής layer Comp για Smart Objects.<br/>            <see href=\"https://helpx.adobe.com/photoshop/using/layer-comps.html\">Layer comps in Smart Objects</see> |
| original_file_name | string | r | Λαμβάνει το αρχικό όνομα αρχείου της πηγής δεδομένων στον παγκόσμιο πόρο συνδέσμου του Adobe® Photoshop®. |
| relative_path | string | r/w | Λαμβάνει ή ορίζει τη σχετική διαδρομή του εξωτερικού αρχείου στην πηγή δεδομένων LiFE του πόρου PSD LnkE. |
| type | [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype) | r | Λαμβάνει τον τύπο της παγκόσμιας πηγής δεδομένων συνδέσμου του Adobe® Photoshop® που μπορεί να είναι ένας από τους παρακάτω ή κανένας:<br/>            Το ενσωματωμένο συνδεδεμένο αρχείο liFD που αντιστοιχεί στο PSD Lnk2Resource<br/>            Το εξωτερικό συνδεδεμένο αρχείο liFE που αντιστοιχεί στο PSD LnkeResource<br/>            Το ψευδώνυμο συνδεδεμένου αρχείου liFA |
| unique_id | Guid | r | Λαμβάνει το παγκόσμιο μοναδικό αναγνωριστικό της πηγής δεδομένων στον πόρο συνδέσμου PSD. |
| version | int | r | Λαμβάνει την έκδοση της πηγής δεδομένων στον πόρο PSD LnkE / Lnk2. |


### Constructor: LiFeDataSource() {#LiFeDataSource__1}


```
 LiFeDataSource() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/).

### Constructor: LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator) {#LiFeDataSource_version_unique_id_original_file_name_file_type_file_creator_2}


```
 LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| version | int | Η έκδοση. |
| unique_id | Guid | Το μοναδικό αναγνωριστικό. |
| original_file_name | string | Όνομα του αρχικού αρχείου. |
| file_type | string | Τύπος του αρχείου. |
| file_creator | string | Ο δημιουργός του αρχείου. |

