---
title: "LinkDataSource"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ορίζει την κλάση LinkDataSource που περιέχει πληροφορίες για ένα συνδεδεμένο αρχείο ή ένα περιουσιακό στοιχείο στο αρχείο PSD."
type: docs
weight: 12
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource/
---

**Inheritance:**
java.lang.Object
```
public abstract class LinkDataSource
```

Ορίζει την κλάση LinkDataSource που περιέχει πληροφορίες για ένα συνδεδεμένο αρχείο ή ένα περιουσιακό στοιχείο στο αρχείο PSD.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [DescriptorVersion_internalized](#DescriptorVersion-internalized) | Η έκδοση του περιγραφέα. |
| [LatestVersion_internalized](#LatestVersion-internalized) | Η πιο πρόσφατη διαθέσιμη έκδοση της πηγής δεδομένων συνδέσμου |
| [UnexpectedLinkDataSourceTypeValue_internalized](#UnexpectedLinkDataSourceTypeValue-internalized) | Η μη αναμενόμενη τιμή τύπου πηγής δεδομένων συνδέσμου |
| [ZeroChar_internalized](#ZeroChar-internalized) | Ο χαρακτήρας μηδέν |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssetLockedState()](#getAssetLockedState--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το στοιχείο PSD είναι κλειδωμένο. |
| [getAssetModTime()](#getAssetModTime--) | Λαμβάνει ή ορίζει την ώρα τροποποίησης του στοιχείου, για τα στοιχεία των βιβλιοθηκών Adobe® Photoshop® \\u0421\\u0421. |
| [getChildDocId()](#getChildDocId--) | Λαμβάνει ή ορίζει το αναγνωριστικό του θυγατρικού εγγράφου στην πηγή δεδομένων liFE ή liFD του πόρου Lnk2 / LnkE του Adobe® Photoshop®. |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης του πόρου. |
| [getClassName_internalized()](#getClassName-internalized--) | Λαμβάνει ή ορίζει το όνομα της κλάσης πόρου. |
| [getCompId()](#getCompId--) | Λαμβάνει ή ορίζει το αναγνωριστικό (ID) του τρέχοντος επιλεγμένου comp για το υπο-έγγραφο, το οποίο θα είναι -1 εάν δεν υπάρχει κανένα επιλεγμένο. |
| [getCompInfoKeyName()](#getCompInfoKeyName--) |  |
| [getContentID_internalized()](#getContentID-internalized--) | Λαμβάνει ή ορίζει την ιδιότητα ContentID. |
| [getDataLength_Property_internalized()](#getDataLength-Property-internalized--) | Λαμβάνει το μήκος των πρόσθετων δεδομένων. |
| [getDataLength_internalized()](#getDataLength-internalized--) | Λαμβάνει το μήκος των δεδομένων πηγής του συνδέσμου. |
| [getFileCreator()](#getFileCreator--) | Λαμβάνει ή ορίζει τον δημιουργό του αρχείου στον πόρο PSD μορφής LnkE / Lnk2. |
| [getFileType()](#getFileType--) | Λαμβάνει ή ορίζει τον τύπο του ενσωματωμένου ή εξωτερικού αρχείου που περιέχει ή συνδέει ο πόρος Adobe® Photoshop® Lnk2 / LnkE. |
| [getItems_internalized()](#getItems-internalized--) | Λαμβάνει ή ορίζει τον πίνακα OSTypeStructure που ορίζει τις ιδιότητες του πόρου. |
| [getLength()](#getLength--) | Λαμβάνει το μήκος της πηγής δεδομένων του συνδέσμου σε bytes. |
| [getOriginalCompId()](#getOriginalCompId--) | Λαμβάνει το αρχικό ID του τρέχοντος επιλεγμένου Comp για το υπο-έγγραφο, το οποίο θα είναι -1 εάν δεν υπάρχει κανένα επιλεγμένο. |
| [getOriginalFileName()](#getOriginalFileName--) | Λαμβάνει το αρχικό όνομα αρχείου της πηγής δεδομένων στον παγκόσμιο πόρο συνδέσμου Adobe® Photoshop®. |
| [getType()](#getType--) | Λαμβάνει τον τύπο της παγκόσμιας πηγής δεδομένων Adobe® Photoshop® που μπορεί να είναι ένας από τους παρακάτω ή κανένας: Το ενσωματωμένο συνδεδεμένο αρχείο liFD που αντιστοιχεί στον πόρο PSD Lnk2Resource Το εξωτερικό συνδεδεμένο αρχείο liFE που αντιστοιχεί στον πόρο PSD LnkeResource Το ψευδώνυμο συνδεδεμένου αρχείου liFA |
| [getUniqueId()](#getUniqueId--) | Λαμβάνει το παγκόσμιο μοναδικό αναγνωριστικό (GUID) της πηγής δεδομένων στον πόρο συνδέσμου PSD. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getUnknownBytes_internalized()](#getUnknownBytes-internalized--) | Λαμβάνει ή ορίζει τα άγνωστα δεδομένα που προηγούνται των ιδιοτήτων Items OSTypeStructures. |
| [getVersion()](#getVersion--) | Λαμβάνει την έκδοση της πηγής δεδομένων στον πόρο PSD LnkE / Lnk2. |
| [hasFileOpenDescriptor()](#hasFileOpenDescriptor--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η πηγή δεδομένων συνδέσμου έχει τον περιγραφέα ανοικτού αρχείου: CompId και OriginalCompId. |
| [hashCode()](#hashCode--) |  |
| [isLibraryLink()](#isLibraryLink--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η πηγή δεδομένων συνδέσμου PSD συνδέεται με το στοιχείο Adobe® Photoshop® \u0421\u0421 Library. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Αποθηκεύει τα δεδομένα του μπλοκ πηγής δεδομένων του συνδέσμου. |
| [setAssetLockedState(boolean value)](#setAssetLockedState-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το στοιχείο PSD είναι κλειδωμένο. |
| [setAssetModTime(double value)](#setAssetModTime-double-) | Λαμβάνει ή ορίζει την ώρα τροποποίησης του στοιχείου, για τα στοιχεία των βιβλιοθηκών Adobe® Photoshop® \\u0421\\u0421. |
| [setChildDocId(String value)](#setChildDocId-java.lang.String-) | Λαμβάνει ή ορίζει το αναγνωριστικό του θυγατρικού εγγράφου στην πηγή δεδομένων liFE ή liFD του πόρου Lnk2 / LnkE του Adobe® Photoshop®. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης του πόρου. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα της κλάσης πόρου. |
| [setCompId(int value)](#setCompId-int-) | Λαμβάνει ή ορίζει το αναγνωριστικό (ID) του τρέχοντος επιλεγμένου comp για το υπο-έγγραφο, το οποίο θα είναι -1 εάν δεν υπάρχει κανένα επιλεγμένο. |
| [setContentID_internalized(String value)](#setContentID-internalized-java.lang.String-) | Λαμβάνει ή ορίζει την ιδιότητα ContentID. |
| [setFileCreator(String value)](#setFileCreator-java.lang.String-) | Λαμβάνει ή ορίζει τον δημιουργό του αρχείου στον πόρο PSD μορφής LnkE / Lnk2. |
| [setFileOpenDescriptor(boolean value)](#setFileOpenDescriptor-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η πηγή δεδομένων συνδέσμου έχει τον περιγραφέα ανοικτού αρχείου: CompId και OriginalCompId. |
| [setFileType(String value)](#setFileType-java.lang.String-) | Λαμβάνει ή ορίζει τον τύπο του ενσωματωμένου ή εξωτερικού αρχείου που περιέχει ή συνδέει ο πόρος Adobe® Photoshop® Lnk2 / LnkE. |
| [setItems_internalized(OSTypeStructure[] value)](#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Λαμβάνει ή ορίζει τον πίνακα OSTypeStructure που ορίζει τις ιδιότητες του πόρου. |
| [setLibraryLink(boolean value)](#setLibraryLink-boolean-) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η πηγή δεδομένων συνδέσμου PSD συνδέεται με το στοιχείο Adobe® Photoshop® \u0421\u0421 Library. |
| [setOriginalCompId(int value)](#setOriginalCompId-int-) | Λαμβάνει το αρχικό ID του τρέχοντος επιλεγμένου Comp για το υπο-έγγραφο, το οποίο θα είναι -1 εάν δεν υπάρχει κανένα επιλεγμένο. |
| [setOriginalFileName(String value)](#setOriginalFileName-java.lang.String-) | Λαμβάνει το αρχικό όνομα αρχείου της πηγής δεδομένων στον παγκόσμιο πόρο συνδέσμου Adobe® Photoshop®. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Ορίζει την τιμή της ιδιότητας με δομή τύπου. |
| [setUniqueId(UUID uuid)](#setUniqueId-java.util.UUID-) | Λαμβάνει το παγκόσμιο μοναδικό αναγνωριστικό (GUID) της πηγής δεδομένων στον πόρο συνδέσμου PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setUnknownBytes_internalized(byte[] value)](#setUnknownBytes-internalized-byte---) | Λαμβάνει ή ορίζει τα άγνωστα δεδομένα που προηγούνται των ιδιοτήτων Items OSTypeStructures. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DescriptorVersion_internalized {#DescriptorVersion-internalized}
```
public static final int DescriptorVersion_internalized
```


Η έκδοση του περιγραφέα.

### LatestVersion_internalized {#LatestVersion-internalized}
```
public static final int LatestVersion_internalized
```


Η πιο πρόσφατη διαθέσιμη έκδοση της πηγής δεδομένων συνδέσμου

### UnexpectedLinkDataSourceTypeValue_internalized {#UnexpectedLinkDataSourceTypeValue-internalized}
```
public static final String UnexpectedLinkDataSourceTypeValue_internalized
```


Η μη αναμενόμενη τιμή τύπου πηγής δεδομένων συνδέσμου

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


Ο χαρακτήρας μηδέν

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAssetLockedState() {#getAssetLockedState--}
```
public final boolean getAssetLockedState()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το στοιχείο PSD είναι κλειδωμένο. Η κατάσταση κλειδώματος του στοιχείου, για τα στοιχεία Adobe® Photoshop® \u0421\u0421 Libraries.

**Returns:**
boolean
### getAssetModTime() {#getAssetModTime--}
```
public final double getAssetModTime()
```


Λαμβάνει ή ορίζει την ώρα τροποποίησης του στοιχείου, για τα στοιχεία των βιβλιοθηκών Adobe® Photoshop® \\u0421\\u0421.

**Returns:**
double
### getChildDocId() {#getChildDocId--}
```
public final String getChildDocId()
```


Λαμβάνει ή ορίζει το αναγνωριστικό του θυγατρικού εγγράφου στην πηγή δεδομένων liFE ή liFD του πόρου Lnk2 / LnkE του Adobe® Photoshop®.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης του πόρου.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Λαμβάνει ή ορίζει το όνομα της κλάσης πόρου.

**Returns:**
java.lang.String
### getCompId() {#getCompId--}
```
public final int getCompId()
```


Λαμβάνει ή ορίζει το ID του τρέχοντος επιλεγμένου comp για το υπο-έγγραφο, το οποίο θα είναι -1 εάν δεν υπάρχει επιλογή. Τα comps είναι συνθέσεις μιας διάταξης σελίδας που μπορούν να δημιουργήσουν οι σχεδιαστές. Χρησιμοποιώντας layer comps, μπορείτε να δημιουργήσετε, να διαχειριστείτε και να προβάλετε πολλαπλές εκδόσεις μιας διάταξης σε ένα ενιαίο αρχείο Adobe® Photoshop®. Ένα layer comp είναι ένα στιγμιότυπο μιας κατάστασης του πίνακα Layers. Τα layer comps αποθηκεύουν τρεις τύπους επιλογών στρώσεων, αλλά αυτή η ιδιότητα λαμβάνει το αναγνωριστικό επιλογής Layer Comp για Smart Objects.  Layer comps in Smart Objects

**Returns:**
int
### getCompInfoKeyName() {#getCompInfoKeyName--}
```
public static String getCompInfoKeyName()
```




**Returns:**
java.lang.String
### getContentID_internalized() {#getContentID-internalized--}
```
public final String getContentID_internalized()
```


Λαμβάνει ή ορίζει την ιδιότητα ContentID. Η τιμή αυτής της ιδιότητας διαβάζεται και αποθηκεύεται μόνο όταν η Έκδοση είναι >= 8.

**Returns:**
java.lang.String
### getDataLength_Property_internalized() {#getDataLength-Property-internalized--}
```
public int getDataLength_Property_internalized()
```


Λαμβάνει το μήκος των πρόσθετων δεδομένων.

Τιμή: Το μήκος των δεδομένων.

**Returns:**
int
### getDataLength_internalized() {#getDataLength-internalized--}
```
public final long getDataLength_internalized()
```


Λαμβάνει το μήκος των δεδομένων πηγής του συνδέσμου.

**Returns:**
long - Το μήκος των πηγαίων δεδομένων.
### getFileCreator() {#getFileCreator--}
```
public final String getFileCreator()
```


Λαμβάνει ή ορίζει τον δημιουργό του αρχείου στον πόρο PSD μορφής LnkE / Lnk2.

**Returns:**
java.lang.String
### getFileType() {#getFileType--}
```
public final String getFileType()
```


Λαμβάνει ή ορίζει τον τύπο του ενσωματωμένου ή εξωτερικού αρχείου που περιέχει ή συνδέει ο πόρος Adobe® Photoshop® Lnk2 / LnkE.

**Returns:**
java.lang.String
### getItems_internalized() {#getItems-internalized--}
```
public final OSTypeStructure[] getItems_internalized()
```


Λαμβάνει ή ορίζει τον πίνακα OSTypeStructure που ορίζει τις ιδιότητες του πόρου.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLength() {#getLength--}
```
public final long getLength()
```


Λαμβάνει το μήκος της πηγής δεδομένων του συνδέσμου σε bytes.

**Returns:**
long
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


Λαμβάνει το αρχικό ID του τρέχοντος επιλεγμένου Comp για το υπο-έγγραφο, το οποίο θα είναι -1 εάν δεν υπάρχει επιλογή. Αυτή η ιδιότητα λαμβάνει το αρχικό αναγνωριστικό επιλογής layer Comp για Smart Objects.  Layer comps in Smart Objects

**Returns:**
int
### getOriginalFileName() {#getOriginalFileName--}
```
public final String getOriginalFileName()
```


Λαμβάνει το αρχικό όνομα αρχείου της πηγής δεδομένων στον παγκόσμιο πόρο συνδέσμου Adobe® Photoshop®.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Λαμβάνει τον τύπο της παγκόσμιας πηγής δεδομένων Adobe® Photoshop® που μπορεί να είναι ένας από τους παρακάτω ή κανένας: Το ενσωματωμένο συνδεδεμένο αρχείο liFD που αντιστοιχεί στον πόρο PSD Lnk2Resource Το εξωτερικό συνδεδεμένο αρχείο liFE που αντιστοιχεί στον πόρο PSD LnkeResource Το ψευδώνυμο συνδεδεμένου αρχείου liFA

Τιμή: Ο τύπος πηγής δεδομένων συνδέσμου PSD.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final UUID getUniqueId()
```


Λαμβάνει το παγκόσμιο μοναδικό αναγνωριστικό (GUID) της πηγής δεδομένων στον πόρο συνδέσμου PSD.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public final System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getUnknownBytes_internalized() {#getUnknownBytes-internalized--}
```
public final byte[] getUnknownBytes_internalized()
```


Λαμβάνει ή ορίζει τα άγνωστα δεδομένα που προηγούνται των ιδιοτήτων Items OSTypeStructures.

**Returns:**
byte[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Λαμβάνει την έκδοση της πηγής δεδομένων στον πόρο PSD LnkE / Lnk2.

**Returns:**
int
### hasFileOpenDescriptor() {#hasFileOpenDescriptor--}
```
public final boolean hasFileOpenDescriptor()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η πηγή δεδομένων συνδέσμου έχει τον περιγραφέα ανοικτού αρχείου: CompId και OriginalCompId.

Τιμή:  true  εάν αυτή η παρουσία έχει περιγραφέα ανοικτού αρχείου· διαφορετικά,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLibraryLink() {#isLibraryLink--}
```
public final boolean isLibraryLink()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η πηγή δεδομένων συνδέσμου PSD συνδέεται με το στοιχείο Adobe® Photoshop® \u0421\u0421 Library.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public final void save_internalized(StreamContainer streamContainer)
```


Αποθηκεύει τα δεδομένα του μπλοκ πηγής δεδομένων του συνδέσμου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το κοντέινερ ροής στο οποίο θα αποθηκευτεί. |

### setAssetLockedState(boolean value) {#setAssetLockedState-boolean-}
```
public final void setAssetLockedState(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το στοιχείο PSD είναι κλειδωμένο. Η κατάσταση κλειδώματος του στοιχείου, για τα στοιχεία Adobe® Photoshop® \u0421\u0421 Libraries.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setAssetModTime(double value) {#setAssetModTime-double-}
```
public final void setAssetModTime(double value)
```


Λαμβάνει ή ορίζει την ώρα τροποποίησης του στοιχείου, για τα στοιχεία των βιβλιοθηκών Adobe® Photoshop® \\u0421\\u0421.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setChildDocId(String value) {#setChildDocId-java.lang.String-}
```
public final void setChildDocId(String value)
```


Λαμβάνει ή ορίζει το αναγνωριστικό του θυγατρικού εγγράφου στην πηγή δεδομένων liFE ή liFD του πόρου Lnk2 / LnkE του Adobe® Photoshop®.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης του πόρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Λαμβάνει ή ορίζει το όνομα της κλάσης πόρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


Λαμβάνει ή ορίζει το ID του τρέχοντος επιλεγμένου comp για το υπο-έγγραφο, το οποίο θα είναι -1 εάν δεν υπάρχει επιλογή. Τα comps είναι συνθέσεις μιας διάταξης σελίδας που μπορούν να δημιουργήσουν οι σχεδιαστές. Χρησιμοποιώντας layer comps, μπορείτε να δημιουργήσετε, να διαχειριστείτε και να προβάλετε πολλαπλές εκδόσεις μιας διάταξης σε ένα ενιαίο αρχείο Adobe® Photoshop®. Ένα layer comp είναι ένα στιγμιότυπο μιας κατάστασης του πίνακα Layers. Τα layer comps αποθηκεύουν τρεις τύπους επιλογών στρώσεων, αλλά αυτή η ιδιότητα λαμβάνει το αναγνωριστικό επιλογής Layer Comp για Smart Objects.  Layer comps in Smart Objects

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setContentID_internalized(String value) {#setContentID-internalized-java.lang.String-}
```
public final void setContentID_internalized(String value)
```


Λαμβάνει ή ορίζει την ιδιότητα ContentID. Η τιμή αυτής της ιδιότητας διαβάζεται και αποθηκεύεται μόνο όταν η Έκδοση είναι >= 8.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setFileCreator(String value) {#setFileCreator-java.lang.String-}
```
public final void setFileCreator(String value)
```


Λαμβάνει ή ορίζει τον δημιουργό του αρχείου στον πόρο PSD μορφής LnkE / Lnk2.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setFileOpenDescriptor(boolean value) {#setFileOpenDescriptor-boolean-}
```
public final void setFileOpenDescriptor(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η πηγή δεδομένων συνδέσμου έχει τον περιγραφέα ανοικτού αρχείου: CompId και OriginalCompId.

Τιμή:  true  εάν αυτή η παρουσία έχει περιγραφέα ανοικτού αρχείου· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setFileType(String value) {#setFileType-java.lang.String-}
```
public final void setFileType(String value)
```


Λαμβάνει ή ορίζει τον τύπο του ενσωματωμένου ή εξωτερικού αρχείου που περιέχει ή συνδέει ο πόρος Adobe® Photoshop® Lnk2 / LnkE.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setItems_internalized(OSTypeStructure[] value) {#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems_internalized(OSTypeStructure[] value)
```


Λαμβάνει ή ορίζει τον πίνακα OSTypeStructure που ορίζει τις ιδιότητες του πόρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLibraryLink(boolean value) {#setLibraryLink-boolean-}
```
public final void setLibraryLink(boolean value)
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η πηγή δεδομένων συνδέσμου PSD συνδέεται με το στοιχείο Adobe® Photoshop® \u0421\u0421 Library.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setOriginalCompId(int value) {#setOriginalCompId-int-}
```
public final void setOriginalCompId(int value)
```


Λαμβάνει το αρχικό ID του τρέχοντος επιλεγμένου Comp για το υπο-έγγραφο, το οποίο θα είναι -1 εάν δεν υπάρχει επιλογή. Αυτή η ιδιότητα λαμβάνει το αρχικό αναγνωριστικό επιλογής layer Comp για Smart Objects.  Layer comps in Smart Objects

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setOriginalFileName(String value) {#setOriginalFileName-java.lang.String-}
```
public final void setOriginalFileName(String value)
```


Λαμβάνει το αρχικό όνομα αρχείου της πηγής δεδομένων στον παγκόσμιο πόρο συνδέσμου Adobe® Photoshop®.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Ορίζει την τιμή της ιδιότητας με δομή τύπου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Η δομή. |

### setUniqueId(UUID uuid) {#setUniqueId-java.util.UUID-}
```
public final void setUniqueId(UUID uuid)
```


Λαμβάνει το παγκόσμιο μοναδικό αναγνωριστικό (GUID) της πηγής δεδομένων στον πόρο συνδέσμου PSD.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| uuid | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public final void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.ms.System.Guid |  |

### setUnknownBytes_internalized(byte[] value) {#setUnknownBytes-internalized-byte---}
```
public final void setUnknownBytes_internalized(byte[] value)
```


Λαμβάνει ή ορίζει τα άγνωστα δεδομένα που προηγούνται των ιδιοτήτων Items OSTypeStructures.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

