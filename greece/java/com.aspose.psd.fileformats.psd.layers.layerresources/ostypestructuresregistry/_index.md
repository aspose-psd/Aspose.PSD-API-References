---
title: "OSTypeStructuresRegistry"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αναπαριστά το μητρώο πόρων."
type: docs
weight: 65
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---

**Inheritance:**
java.lang.Object
```
public final class OSTypeStructuresRegistry
```

Αναπαριστά το [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) μητρώο πόρων.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [OSTypeStructuresRegistry()](#OSTypeStructuresRegistry--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(InputStream stream)](#getFirstSupportedDescriptor-java.io.InputStream-) | Λαμβάνει τον πρώτο υποστηριζόμενο περιγραφέα ανοικτήριου. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Λαμβάνει τον πρώτο υποστηριζόμενο περιγραφέα με βάση το όνομα τύπου του. |
| [getFirstSupportedDescriptor_internalized(System.IO.Stream stream)](#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Λαμβάνει τους καταχωρημένους περιγραφείς. |
| [hashCode()](#hashCode--) |  |
| [isOSTypeStructreExist_internalized(int structureKey)](#isOSTypeStructreExist-internalized-int-) | Εντοπίζει εάν υπάρχει κάποιο απόγονο του OSTypeStructure με το δοσμένο structureKey. |
| [loadDescriptorData_internalized(StreamContainer streamContainer)](#loadDescriptorData-internalized-com.aspose.psd.StreamContainer-) | Φορτώνει τις δομές δεδομένων descriptor από το container ροής. |
| [loadDescriptorData_internalized(StreamContainer streamContainer, String[] className, ClassID[] classId)](#loadDescriptorData-internalized-com.aspose.psd.StreamContainer-java.lang.String---com.aspose.psd.fileformats.psd.layers.layerresources.ClassID---) | Φορτώνει τις δομές δεδομένων descriptor με όνομα κλάσης και αναγνωριστικό κλάσης από το container ροής. |
| [loadResourceByFirstSupportedDescriptor(InputStream stream)](#loadResourceByFirstSupportedDescriptor-java.io.InputStream-) | Φορτώνει το [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) χρησιμοποιώντας τον πρώτο βρεθέντα ανοικτήρα κατάλληλο για τη συγκεκριμένη ροή. |
| [loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream)](#loadResourceByFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerOpener(IOSTypeStructureLoader openerDescriptor)](#registerOpener-com.aspose.psd.fileformats.psd.layers.layerresources.IOSTypeStructureLoader-) | Καταχωρεί το ανοικτήριο. |
| [toString()](#toString--) |  |
| [unregisterOpener(IOSTypeStructureLoader openerDescriptor)](#unregisterOpener-com.aspose.psd.fileformats.psd.layers.layerresources.IOSTypeStructureLoader-) | Καταργεί την καταχώρηση του opener. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OSTypeStructuresRegistry() {#OSTypeStructuresRegistry--}
```
public OSTypeStructuresRegistry()
```


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
### getFirstSupportedDescriptor(InputStream stream) {#getFirstSupportedDescriptor-java.io.InputStream-}
```
public static IOSTypeStructureLoader getFirstSupportedDescriptor(InputStream stream)
```


Λαμβάνει τον πρώτο υποστηριζόμενο περιγραφέα ανοικτήριου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | stream | java.io.InputStream | Η ροή. |

--------------------

Ο πρώτος φορτωτής θα είναι στην πραγματικότητα ο τελευταίος που καταχωρήθηκε. |

**Returns:**
[IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) - The layer resource loader descriptor or null if no loader descriptor supported for such stream.
### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IOSTypeStructureLoader getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Λαμβάνει τον πρώτο υποστηριζόμενο περιγραφέα με βάση το όνομα τύπου του.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | Το όνομα τύπου περιγραφέα. |

--------------------

Ο πρώτος περιγραφέας ανοίκτη θα είναι στην πραγματικότητα ο τελευταίος που καταχωρήθηκε. |

**Returns:**
[IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) - The first found opener descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor_internalized(System.IO.Stream stream) {#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-}
```
public static IOSTypeStructureLoader getFirstSupportedDescriptor_internalized(System.IO.Stream stream)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader)
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IOSTypeStructureLoader[] getRegisteredDescriptors()
```


Λαμβάνει τους καταχωρημένους περιγραφείς.

Τιμή: Οι καταχωρημένοι περιγραφείς.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.IOSTypeStructureLoader[]
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isOSTypeStructreExist_internalized(int structureKey) {#isOSTypeStructreExist-internalized-int-}
```
public static boolean isOSTypeStructreExist_internalized(int structureKey)
```


Εντοπίζει εάν υπάρχει κάποιο απόγονο του OSTypeStructure με το δοσμένο structureKey.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| structureKey | int | StructureKey του OSTypeStructure. |

**Returns:**
boolean -
### loadDescriptorData_internalized(StreamContainer streamContainer) {#loadDescriptorData-internalized-com.aspose.psd.StreamContainer-}
```
public static OSTypeStructure[] loadDescriptorData_internalized(StreamContainer streamContainer)
```


Φορτώνει τις δομές δεδομένων descriptor από το container ροής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Η ροή για ανάγνωση. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - Οι δομές δεδομένων descriptor.
### loadDescriptorData_internalized(StreamContainer streamContainer, String[] className, ClassID[] classId) {#loadDescriptorData-internalized-com.aspose.psd.StreamContainer-java.lang.String---com.aspose.psd.fileformats.psd.layers.layerresources.ClassID---}
```
public static OSTypeStructure[] loadDescriptorData_internalized(StreamContainer streamContainer, String[] className, ClassID[] classId)
```


Φορτώνει τις δομές δεδομένων descriptor με όνομα κλάσης και αναγνωριστικό κλάσης από το container ροής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Η ροή για ανάγνωση. |
| className | java.lang.String[] | Το όνομα κλάσης που διαβάστηκε. |
| classId | [ClassID\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | Το αναγνωριστικό κλάσης που διαβάστηκε. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - Οι δομές δεδομένων descriptor με όνομα κλάσης και αναγνωριστικό κλάσης.
### loadResourceByFirstSupportedDescriptor(InputStream stream) {#loadResourceByFirstSupportedDescriptor-java.io.InputStream-}
```
public static OSTypeStructure loadResourceByFirstSupportedDescriptor(InputStream stream)
```


Φορτώνει το [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) χρησιμοποιώντας τον πρώτο βρεθέντα ανοικτήρα κατάλληλο για τη συγκεκριμένη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | stream | java.io.InputStream | Η ροή. |

--------------------

Ο πρώτος ανοίκτης θα είναι στην πραγματικότητα ο τελευταίος που καταχωρήθηκε. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The loaded [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) or null if no opener is found.
### loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream) {#loadResourceByFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-}
```
public static OSTypeStructure loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### registerOpener(IOSTypeStructureLoader openerDescriptor) {#registerOpener-com.aspose.psd.fileformats.psd.layers.layerresources.IOSTypeStructureLoader-}
```
public static void registerOpener(IOSTypeStructureLoader openerDescriptor)
```


Καταχωρεί το ανοικτήριο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| openerDescriptor | [IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Ο περιγραφέας ανοίκτη για καταχώρηση. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unregisterOpener(IOSTypeStructureLoader openerDescriptor) {#unregisterOpener-com.aspose.psd.fileformats.psd.layers.layerresources.IOSTypeStructureLoader-}
```
public static void unregisterOpener(IOSTypeStructureLoader openerDescriptor)
```


Καταργεί την καταχώρηση του opener.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| openerDescriptor | [IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Ο περιγραφέας ανοίκτη για κατάργηση καταχώρησης. |

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

