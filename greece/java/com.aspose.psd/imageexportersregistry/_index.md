---
title: "ImageExportersRegistry"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αναπαριστά το μητρώο εξαγωγέων εικόνας"
type: docs
weight: 57
url: /el/java/com.aspose.psd/imageexportersregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageExportersRegistry
```

Αναπαριστά το μητρώο εξαγωγέων εικόνας
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ImageExportersRegistry()](#ImageExportersRegistry--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createFirstSupportedExporter(Image image, ImageOptionsBase options)](#createFirstSupportedExporter-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Δημιουργεί τον πρώτο ευρέθηκε εξαγωγέα που είναι κατάλληλος για τις καθορισμένες επιλογές αποθήκευσης και την εικόνα. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(Image image, ImageOptionsBase options)](#getFirstSupportedDescriptor-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Αποκτά τον πρώτο ευρέθηκε υποστηριζόμενο descriptor που είναι κατάλληλος για τις καθορισμένες επιλογές αποθήκευσης και την εικόνα. |
| [getRegisteredExporterDescriptors()](#getRegisteredExporterDescriptors--) | Αποκτά τους καταχωρημένους descriptor εξαγωγέα. |
| [getRegisteredFormats()](#getRegisteredFormats--) | Αποκτά τις καταχωρημένες μορφές εξαγωγής. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageExporterDescriptor imageExporterDescriptor)](#register-com.aspose.psd.IImageExporterDescriptor-) | Καταχωρεί τον καθορισμένο descriptor εξαγωγέα εικόνας. |
| [registerExporter(IImageExporterDescriptor exporterDescriptor)](#registerExporter-com.aspose.psd.IImageExporterDescriptor-) | Καταχωρεί τον εξαγωγέα. |
| [toString()](#toString--) |  |
| [unregisterExporter(IImageExporterDescriptor exporterDescriptor)](#unregisterExporter-com.aspose.psd.IImageExporterDescriptor-) | Καταργεί την καταχώρηση του εξαγωγέα. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageExportersRegistry() {#ImageExportersRegistry--}
```
public ImageExportersRegistry()
```


### createFirstSupportedExporter(Image image, ImageOptionsBase options) {#createFirstSupportedExporter-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public static IImageExporter createFirstSupportedExporter(Image image, ImageOptionsBase options)
```


Δημιουργεί τον πρώτο ευρέθηκε εξαγωγέα που είναι κατάλληλος για τις καθορισμένες επιλογές αποθήκευσης και την εικόνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Η εικόνα προς εξαγωγή. |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές αποθήκευσης για χρήση στην εξαγωγή. |

--------------------

Ο πρώτος εξαγωγέας θα είναι στην πραγματικότητα ο τελευταίος καταχωρημένος. |

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - The exporter which supports the specified image and save options or null if no such exporter is found.
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
### getFirstSupportedDescriptor(Image image, ImageOptionsBase options) {#getFirstSupportedDescriptor-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public static IImageExporterDescriptor getFirstSupportedDescriptor(Image image, ImageOptionsBase options)
```


Αποκτά τον πρώτο ευρέθηκε υποστηριζόμενο descriptor που είναι κατάλληλος για τις καθορισμένες επιλογές αποθήκευσης και την εικόνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Η εικόνα προς εξαγωγή. |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές. |

--------------------

Ο πρώτος descriptor εξαγωγέα θα είναι στην πραγματικότητα ο τελευταίος καταχωρημένος. |

**Returns:**
[IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) - The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.
### getRegisteredExporterDescriptors() {#getRegisteredExporterDescriptors--}
```
public static IImageExporterDescriptor[] getRegisteredExporterDescriptors()
```


Αποκτά τους καταχωρημένους descriptor εξαγωγέα.

Τιμή: Οι καταχωρημένοι descriptor εξαγωγέα.

**Returns:**
com.aspose.psd.IImageExporterDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Αποκτά τις καταχωρημένες μορφές εξαγωγής.

Τιμή: Οι καταχωρημένες μορφές εξαγωγής.

**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### register(IImageExporterDescriptor imageExporterDescriptor) {#register-com.aspose.psd.IImageExporterDescriptor-}
```
public static void register(IImageExporterDescriptor imageExporterDescriptor)
```


Καταχωρεί τον καθορισμένο descriptor εξαγωγέα εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageExporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | Ο descriptor εξαγωγέα εικόνας. |

### registerExporter(IImageExporterDescriptor exporterDescriptor) {#registerExporter-com.aspose.psd.IImageExporterDescriptor-}
```
public static void registerExporter(IImageExporterDescriptor exporterDescriptor)
```


Καταχωρεί τον εξαγωγέα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | Ο descriptor εξαγωγέα για καταχώρηση. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unregisterExporter(IImageExporterDescriptor exporterDescriptor) {#unregisterExporter-com.aspose.psd.IImageExporterDescriptor-}
```
public static void unregisterExporter(IImageExporterDescriptor exporterDescriptor)
```


Καταργεί την καταχώρηση του εξαγωγέα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | Ο descriptor εξαγωγέα για κατάργηση καταχώρησης. |

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

