---
title: "AddNoiseSmartFilter"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Το έξυπνο φίλτρο AddNoise."
type: docs
weight: 10
url: /el/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.smartfilters.filters.SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter)
```
public final class AddNoiseSmartFilter extends SmartFilter
```

Το έξυπνο φίλτρο AddNoise.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [AddNoiseSmartFilter()](#AddNoiseSmartFilter--) | Αρχικοποιεί μια νέα παρουσία της [AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter) class. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [FilterType](#FilterType) | Το αναγνωριστικό του τρέχοντος έξυπνου φίλτρου. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | Εφαρμόζει το τρέχον φίλτρο στην είσοδο RasterImage εικόνα. |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | Εφαρμόζει το τρέχον φίλτρο στην είσοδο δεδομένων μάσκας [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). |
| [create_internalized(DescriptorStructure sourceDescriptor)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) |  |
| [deepClone()](#deepClone--) | Δημιουργεί το μέλος-προς-μέλος κλώνο της τρέχουσας παρουσίασης του τύπου. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAmountNoise()](#getAmountNoise--) | Λαμβάνει ή ορίζει την ποσότητα της τιμής θορύβου. |
| [getBlendMode()](#getBlendMode--) | Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης. |
| [getClass()](#getClass--) |  |
| [getDistribution()](#getDistribution--) | Λαμβάνει ή ορίζει την κατανομή του φίλτρου θορύβου. |
| [getFilterId()](#getFilterId--) | Λαμβάνει το αναγνωριστικό τύπου του έξυπνου φίλτρου. |
| [getName()](#getName--) | Λαμβάνει το όνομα του έξυπνου φίλτρου. |
| [getOpacity()](#getOpacity--) | Λαμβάνει ή ορίζει την τιμή αδιαφάνειας του έξυπνου φίλτρου. |
| [getSourceDescriptor()](#getSourceDescriptor--) | Η δομή περιγραφέα πηγής με δεδομένα έξυπνου φίλτρου. |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | Λαμβάνει ή ορίζει την κατάσταση is enabled του έξυπνου φίλτρου. |
| [isMonochromatic()](#isMonochromatic--) | Λαμβάνει ή ορίζει την τιμή του μονοχρωματικού. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAmountNoise(double value)](#setAmountNoise-double-) | Λαμβάνει ή ορίζει την ποσότητα της τιμής θορύβου. |
| [setBlendMode(long value)](#setBlendMode-long-) | Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης. |
| [setDistribution(int value)](#setDistribution-int-) | Λαμβάνει ή ορίζει την κατανομή του φίλτρου θορύβου. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Λαμβάνει ή ορίζει την κατάσταση is enabled του έξυπνου φίλτρου. |
| [setMonochromatic(boolean value)](#setMonochromatic-boolean-) | Λαμβάνει ή ορίζει την τιμή του μονοχρωματικού. |
| [setOpacity(double value)](#setOpacity-double-) | Λαμβάνει ή ορίζει την τιμή αδιαφάνειας του έξυπνου φίλτρου. |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | Αποθηκεύει τις πληροφορίες του έξυπνου φίλτρου στα δεδομένα [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) και επιστρέφει. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AddNoiseSmartFilter() {#AddNoiseSmartFilter--}
```
public AddNoiseSmartFilter()
```


Αρχικοποιεί μια νέα παρουσία της [AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter) class.

### FilterType {#FilterType}
```
public static final int FilterType
```


Το αναγνωριστικό του τρέχοντος έξυπνου φίλτρου.

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
public static AddNoiseSmartFilter create_internalized(DescriptorStructure sourceDescriptor)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceDescriptor | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

**Returns:**
[AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter)
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
### getAmountNoise() {#getAmountNoise--}
```
public final double getAmountNoise()
```


Λαμβάνει ή ορίζει την ποσότητα της τιμής θορύβου.

**Returns:**
double
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
### getDistribution() {#getDistribution--}
```
public final int getDistribution()
```


Λαμβάνει ή ορίζει την κατανομή του φίλτρου θορύβου.

**Returns:**
int
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
### isMonochromatic() {#isMonochromatic--}
```
public final boolean isMonochromatic()
```


Λαμβάνει ή ορίζει την τιμή του μονοχρωματικού.

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




### setAmountNoise(double value) {#setAmountNoise-double-}
```
public final void setAmountNoise(double value)
```


Λαμβάνει ή ορίζει την ποσότητα της τιμής θορύβου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setDistribution(int value) {#setDistribution-int-}
```
public final void setDistribution(int value)
```


Λαμβάνει ή ορίζει την κατανομή του φίλτρου θορύβου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Λαμβάνει ή ορίζει την κατάσταση is enabled του έξυπνου φίλτρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setMonochromatic(boolean value) {#setMonochromatic-boolean-}
```
public final void setMonochromatic(boolean value)
```


Λαμβάνει ή ορίζει την τιμή του μονοχρωματικού.

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

