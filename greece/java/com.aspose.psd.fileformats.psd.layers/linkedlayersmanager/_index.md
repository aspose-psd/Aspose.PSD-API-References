---
title: "LinkedLayersManager"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Κλάση διαχειριστή συνδεδεμένων επιπέδων."
type: docs
weight: 27
url: /el/java/com.aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---

**Inheritance:**
java.lang.Object
```
public final class LinkedLayersManager
```

Κλάση διαχειριστή συνδεδεμένων επιπέδων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [create_internalized(Image container, LinkedLayersRegistry linksRegistry)](#create-internalized-com.aspose.psd.Image-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLayersByLinkGroupId(short linkGroupId)](#getLayersByLinkGroupId-short-) | Λαμβάνει τις στρώσεις με βάση το αναγνωριστικό ομάδας συνδέσμου id. |
| [getLinkGroupId(Layer layer)](#getLinkGroupId-com.aspose.psd.fileformats.psd.layers.Layer-) | Λαμβάνει το αναγνωριστικό ομάδας συνδέσμου (ID) που σχετίζεται με τη στρώση. |
| [hashCode()](#hashCode--) |  |
| [linkLayers(Layer[] layers)](#linkLayers-com.aspose.psd.fileformats.psd.layers.Layer---) | Συνδέει τις εισερχόμενες στρώσεις και επιστρέφει το LingGroupId. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [unlinkLayer(Layer layer)](#unlinkLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | Αποσυνδέει τη στρώση. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(Image container, LinkedLayersRegistry linksRegistry) {#create-internalized-com.aspose.psd.Image-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-}
```
public static LinkedLayersManager create_internalized(Image container, LinkedLayersRegistry linksRegistry)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) |  |
| linksRegistry | com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry |  |

**Returns:**
[LinkedLayersManager](../../com.aspose.psd.fileformats.psd.layers/linkedlayersmanager)
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
### getLayersByLinkGroupId(short linkGroupId) {#getLayersByLinkGroupId-short-}
```
public final Layer[] getLayersByLinkGroupId(short linkGroupId)
```


Λαμβάνει τις στρώσεις με βάση το αναγνωριστικό ομάδας συνδέσμου id.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| linkGroupId | short | Το αναγνωριστικό ομάδας συνδέσμου. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[] - Ο πίνακας στρώσεων.
### getLinkGroupId(Layer layer) {#getLinkGroupId-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final short getLinkGroupId(Layer layer)
```


Λαμβάνει το αναγνωριστικό ομάδας συνδέσμου (ID) που σχετίζεται με τη στρώση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Το στρώμα. |

**Returns:**
short - Το αναγνωριστικό ομάδας συνδέσμου.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### linkLayers(Layer[] layers) {#linkLayers-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final short linkLayers(Layer[] layers)
```


Συνδέει τις εισερχόμενες στρώσεις και επιστρέφει το LingGroupId.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| layers | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | Οι στρώσεις. |

**Returns:**
short - Το αναγνωριστικό ομάδας συνδέσμου.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unlinkLayer(Layer layer) {#unlinkLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void unlinkLayer(Layer layer)
```


Αποσυνδέει τη στρώση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Το στρώμα. |

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

