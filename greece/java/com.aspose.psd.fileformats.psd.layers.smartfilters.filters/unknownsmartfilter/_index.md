---
title: "UnknownSmartFilter"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Η κλάση για την αποθήκευση άγνωστων δεδομένων έξυπνων φίλτρων."
type: docs
weight: 14
url: /el/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/unknownsmartfilter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.smartfilters.filters.SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter)
```
public final class UnknownSmartFilter extends SmartFilter
```

Η κλάση για την αποθήκευση άγνωστων δεδομένων έξυπνων φίλτρων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | Εφαρμόζει το τρέχον φίλτρο στην είσοδο RasterImage εικόνα. |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | Εφαρμόζει το τρέχον φίλτρο στην είσοδο δεδομένων μάσκας [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). |
| [create_internalized(DescriptorStructure sourceDescriptor)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) |  |
| [deepClone()](#deepClone--) | Δημιουργεί το μέλος-προς-μέλος κλώνο της τρέχουσας παρουσίασης του τύπου. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης. |
| [getClass()](#getClass--) |  |
| [getFilterId()](#getFilterId--) | Λαμβάνει το αναγνωριστικό τύπου του έξυπνου φίλτρου. |
| [getName()](#getName--) | Λαμβάνει το όνομα του έξυπνου φίλτρου. |
| [getOpacity()](#getOpacity--) | Λαμβάνει ή ορίζει την τιμή αδιαφάνειας του έξυπνου φίλτρου. |
| [getSourceDescriptor()](#getSourceDescriptor--) | Η δομή περιγραφέα πηγής με δεδομένα έξυπνου φίλτρου. |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | Λαμβάνει ή ορίζει την κατάσταση is enabled του έξυπνου φίλτρου. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Λαμβάνει ή ορίζει την κατάσταση is enabled του έξυπνου φίλτρου. |
| [setOpacity(double value)](#setOpacity-double-) | Λαμβάνει ή ορίζει την τιμή αδιαφάνειας του έξυπνου φίλτρου. |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | Αποθηκεύει τις πληροφορίες του έξυπνου φίλτρου στα δεδομένα [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) και επιστρέφει. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### apply(RasterImage rasterImage) {#apply-com.aspose.psd.RasterImage-}
```
public final void apply(RasterImage rasterImage)
```


Εφαρμόζει το τρέχον φίλτρο στην είσοδο RasterImage εικόνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | Η εικόνα raster. |

### applyToMask(Layer layerWithMask) {#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void applyToMask(Layer layerWithMask)
```


Εφαρμόζει το τρέχον φίλτρο στην είσοδο δεδομένων μάσκας [Layer](../../com.aspose.psd.fileformats.psd.layers/layer).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| layerWithMask | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Το επίπεδο με δεδομένα μάσκας. |

### create_internalized(DescriptorStructure sourceDescriptor) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public static UnknownSmartFilter create_internalized(DescriptorStructure sourceDescriptor)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceDescriptor | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

**Returns:**
[UnknownSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/unknownsmartfilter)
### deepClone() {#deepClone--}
```
public final SmartFilter deepClone()
```


Δημιουργεί το μέλος-προς-μέλος κλώνο της τρέχουσας παρουσίασης του τύπου.

**Returns:**
[SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) - Returns the memberwise clone of the current instance of the type.
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
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFilterId() {#getFilterId--}
```
public int getFilterId()
```


Λαμβάνει το αναγνωριστικό τύπου του έξυπνου φίλτρου.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Λαμβάνει το όνομα του έξυπνου φίλτρου.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Λαμβάνει ή ορίζει την τιμή αδιαφάνειας του έξυπνου φίλτρου.

**Returns:**
double
### getSourceDescriptor() {#getSourceDescriptor--}
```
public final DescriptorStructure getSourceDescriptor()
```


Η δομή περιγραφέα πηγής με δεδομένα έξυπνου φίλτρου.

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```


Λαμβάνει ή ορίζει την κατάσταση is enabled του έξυπνου φίλτρου.

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




### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Λαμβάνει ή ορίζει την κατάσταση is enabled του έξυπνου φίλτρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Λαμβάνει ή ορίζει την τιμή αδιαφάνειας του έξυπνου φίλτρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### toDescriptorStructure_internalized() {#toDescriptorStructure-internalized--}
```
public DescriptorStructure toDescriptorStructure_internalized()
```


Αποθηκεύει τις πληροφορίες του έξυπνου φίλτρου στα δεδομένα [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) και επιστρέφει.

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) - The [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) with saved smart filter information.
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

