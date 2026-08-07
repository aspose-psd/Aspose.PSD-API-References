---
title: "SmartObjectProvider"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ορίζει τον πάροχο έξυπνου αντικειμένου που παρέχει λήψη/ρύθμιση πηγών δεδομένων από παγκόσμιους συνδετικούς πόρους του αρχείου PSD και το περιεχόμενό τους."
type: docs
weight: 17
url: /el/java/com.aspose.psd.fileformats.psd/smartobjectprovider/
---

**Inheritance:**
java.lang.Object
```
public class SmartObjectProvider
```

Ορίζει τον πάροχο έξυπνου αντικειμένου που παρέχει λήψη/ρύθμιση πηγών δεδομένων από παγκόσμιους συνδετικούς πόρους του αρχείου PSD και το περιεχόμενό τους.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [convertToSmartObject(Layer[] layers)](#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---) | Μετατρέπει τα στρώματα σε ενσωματωμένο smart object. |
| [convertToSmartObject(int[] layerNumbers)](#convertToSmartObject-int...-) | Μετατρέπει τα στρώματα σε ενσωματωμένο smart object. |
| [create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider). |
| [embedAllLinked()](#embedAllLinked--) | Ενσωματώνει όλα τα συνδεδεμένα smart objects στην εικόνα. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentType_internalized(System.Guid uniqueId)](#getContentType-internalized-com.aspose.ms.System.Guid-) | Αποκτά τον τύπο του περιεχομένου του στρώματος smart object. |
| [getContents_internalized(System.Guid uniqueId)](#getContents-internalized-com.aspose.ms.System.Guid-) | Αποκτά τα περιεχόμενα του ενσωματωμένου ή συνδεδεμένου αρχείου. |
| [getDataSource_internalized(System.Guid uniqueId)](#getDataSource-internalized-com.aspose.ms.System.Guid-) | Αποκτά την πηγή δεδομένων συνδέσμου με μοναδικό id. |
| [hashCode()](#hashCode--) |  |
| [loadContents_internalized(System.Guid uniqueId, LoadOptions options)](#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-) | Φορτώνει τα περιεχόμενα. |
| [newSmartObjectViaCopy(SmartObjectLayer sourceLayer)](#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-) | Δημιουργεί ένα νέο στρώμα smart object αντιγράφοντας το πηγαίο. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)](#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--) | Αφαιρεί τις πηγές δεδομένων από ενσωματωμένους και εξωτερικούς πόρους που δεν εμφανίζονται στη δοθείσα λίστα έγκυρων GUID. |
| [replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)](#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---) | Αντικαθιστά την πηγή δεδομένων στους παγκόσμιους πόρους με τα παρεχόμενα περιεχόμενα για ενσωμάτωση. |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-) |  |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-) | Αντικαθιστά την πηγή δεδομένων σε έναν παγκόσμιο πόρο LinkResource με τη νεοδημιουργημένη πηγή δεδομένων από εξωτερικό αρχείο. |
| [setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)](#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-) | Ορίζει τα περιεχόμενα του ενσωματωμένου ή εξωτερικού αρχείου. |
| [setDataSource(LinkDataSource dataSource)](#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Ορίζει (αντικαθιστά ή προσθέτει) την πηγή δεδομένων συνδέσμου στον παγκόσμιο πόρο συνδέσμου. |
| [toString()](#toString--) |  |
| [updateAllModifiedContent()](#updateAllModifiedContent--) | Ενημερώνει το περιεχόμενο όλων των τροποποιημένων smart objects στην εικόνα. |
| [updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)](#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-) | Ενημερώνει όλα τα στρώματα smart object μέσα στο container του οποίου το  UniqueId  ταιριάζει με το  oldGuid . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### convertToSmartObject(Layer[] layers) {#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final SmartObjectLayer convertToSmartObject(Layer[] layers)
```


Μετατρέπει τα στρώματα σε ενσωματωμένο smart object.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| layers | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | Οι στρώσεις. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### convertToSmartObject(int[] layerNumbers) {#convertToSmartObject-int...-}
```
public final SmartObjectLayer convertToSmartObject(int[] layerNumbers)
```


Μετατρέπει τα στρώματα σε ενσωματωμένο smart object.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| layerNumbers | int[] | Οι αριθμοί των επιπέδων. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-}
```
public static SmartObjectProvider create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| externalLinkResource | [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) |  |
| embeddedLinkResource | [Lnk2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnk2resource) |  |
| container | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | Το δοχείο. |

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### embedAllLinked() {#embedAllLinked--}
```
public final void embedAllLinked()
```


Ενσωματώνει όλα τα συνδεδεμένα smart objects στην εικόνα.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContentType_internalized(System.Guid uniqueId) {#getContentType-internalized-com.aspose.ms.System.Guid-}
```
public final int getContentType_internalized(System.Guid uniqueId)
```


Αποκτά τον τύπο του περιεχομένου του στρώματος smart object.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Το μοναδικό αναγνωριστικό. |

**Returns:**
int - Ο τύπος του περιεχομένου του επιπέδου έξυπνου αντικειμένου.
### getContents_internalized(System.Guid uniqueId) {#getContents-internalized-com.aspose.ms.System.Guid-}
```
public final byte[] getContents_internalized(System.Guid uniqueId)
```


Αποκτά τα περιεχόμενα του ενσωματωμένου ή συνδεδεμένου αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Το μοναδικό αναγνωριστικό της πηγής δεδομένων του συνδέσμου. |

**Returns:**
byte[] - Τα περιεχόμενα του byte[]
### getDataSource_internalized(System.Guid uniqueId) {#getDataSource-internalized-com.aspose.ms.System.Guid-}
```
public final LinkDataSource getDataSource_internalized(System.Guid uniqueId)
```


Αποκτά την πηγή δεδομένων συνδέσμου με μοναδικό id.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Το μοναδικό αναγνωριστικό. |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) - The [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) instance.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadContents_internalized(System.Guid uniqueId, LoadOptions options) {#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-}
```
public final Image loadContents_internalized(System.Guid uniqueId, LoadOptions options)
```


Φορτώνει τα περιεχόμενα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Το μοναδικό αναγνωριστικό. |
| options | [LoadOptions](../../com.aspose.psd/loadoptions) | Οι επιλογές φόρτωσης. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded  Image  instance.
### newSmartObjectViaCopy(SmartObjectLayer sourceLayer) {#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-}
```
public final SmartObjectLayer newSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```


Δημιουργεί ένα νέο στρώμα smart object αντιγράφοντας το πηγαίο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceLayer | [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | Το επίπεδο προέλευσης. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The cloned [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources) {#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--}
```
public final void removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)
```


Αφαιρεί πηγές δεδομένων από ενσωματωμένους και εξωτερικούς πόρους που δεν εμφανίζονται στη δοθείσα λίστα έγκυρων GUID. Αυτή η μέθοδος καθαρίζει τις ορφανές πηγές δεδομένων συγκρίνοντάς τες με τα τρέχοντα έγκυρα αναγνωριστικά πηγών δεδομένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| actualDataSources | com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Guid> | Η λίστα των έγκυρων GUID πηγών δεδομένων που θα διατηρηθούν. Οι πηγές δεδομένων που δεν βρίσκονται σε αυτή τη λίστα θα αφαιρεθούν. |

### replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents) {#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---}
```
public final System.Guid replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)
```


Αντικαθιστά την πηγή δεδομένων στους παγκόσμιους πόρους με τα παρεχόμενα περιεχόμενα για ενσωμάτωση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| oldUniqueId | com.aspose.ms.System.Guid | Το μοναδικό αναγνωριστικό της υπάρχουσας πηγής δεδομένων. |
| contents | byte[] | Τα δεδομένα για μια νέα πηγή δεδομένων. |

**Returns:**
com.aspose.ms.System.Guid - Το μοναδικό αναγνωριστικό της δημιουργημένης ενσωματωμένης πηγής δεδομένων.  LiFdDataSource .
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) |  |
| linkedPath | java.lang.String |  |

**Returns:**
com.aspose.ms.System.Guid
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)
```


Αντικαθιστά την πηγή δεδομένων σε έναν παγκόσμιο πόρο LinkResource με τη νεοδημιουργημένη πηγή δεδομένων από εξωτερικό αρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Ο τοποθετημένος πόρος. |
| linkedPath | java.lang.String | Η απόλυτη διαδρομή προς το συνδεδεμένο αρχείο. |
| isReplaceOnlyThis | boolean | Εάν είναι true, τότε μην αφαιρέσετε την πηγή δεδομένων στους παγκόσμιους πόρους. |

**Returns:**
com.aspose.ms.System.Guid - Το μοναδικό αναγνωριστικό Guid της δημιουργημένης συνδεδεμένης πηγής δεδομένων. [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).
### setContents_internalized(System.Guid uniqueId, byte[] data, String fileType) {#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-}
```
public final void setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)
```


Ορίζει τα περιεχόμενα του ενσωματωμένου ή εξωτερικού αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Το μοναδικό αναγνωριστικό της πηγής δεδομένων του συνδέσμου. |
| δεδομένα | byte[] | Τα δεδομένα. |
| fileType | java.lang.String | Ο τύπος αρχείου δεδομένων. |

### setDataSource(LinkDataSource dataSource) {#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void setDataSource(LinkDataSource dataSource)
```


Ορίζει (αντικαθιστά ή προσθέτει) την πηγή δεδομένων συνδέσμου στον παγκόσμιο πόρο συνδέσμου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | Η πηγή δεδομένων σύνδεσης. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateAllModifiedContent() {#updateAllModifiedContent--}
```
public final void updateAllModifiedContent()
```


Ενημερώνει το περιεχόμενο όλων των τροποποιημένων smart objects στην εικόνα.

### updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution) {#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-}
```
public final void updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)
```


Ενημερώνει όλα τα επίπεδα έξυπνων αντικειμένων μέσα στο container των οποίων το  UniqueId  ταιριάζει με  oldGuid . Τα UniqueId των ταιριαστών επιπέδων εκχωρούνται ξανά στο  newGuid  και το περιεχόμενό τους ανανεώνεται.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| oldGuid | com.aspose.ms.System.Guid | Το μοναδικό αναγνωριστικό της αρχικής πηγής δεδομένων έξυπνου αντικειμένου που θα αντικατασταθεί. |
| newGuid | com.aspose.ms.System.Guid | Το μοναδικό αναγνωριστικό της νέας πηγής δεδομένων έξυπνου αντικειμένου για ανάθεση. |
| resolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | Οι ρυθμίσεις ανάλυσης που θα εφαρμοστούν κατά την ενημέρωση του περιεχομένου. Εάν  null , χρησιμοποιείται η ανάλυση της εικόνας. |

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

